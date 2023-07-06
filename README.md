
Here we are calling the authenticate url without creating the user  
![](https://lh6.googleusercontent.com/w-yWepLhKamKncdGxwYo4CYZfkOLw7HGXj23FuFLMMr9xTIb1mQTseAEzyDTd2QSCUFnKAtUFE9ky2Ephlzsvht4lwfiis3Spi3xt7lWDb6Jfi8XPl4fSYYO0pgoIXP5bxHFMnCS3dkYjBMJiieTCFw)

The token returned is null because the credentials are invalid  
Lets try to signup a user

![](https://lh3.googleusercontent.com/7lWVxjGnA1ay1p4cHjpgskiAsJ6bCoDW-rqiaLa883DqkhVrgIx0DQ4Ad_BaFuhWAZUoY8ngbl_Wu6vbSycvYbKA37qlThmP7aW-Hp6WP1trvUPkOxpZOWDkvt8RW9-ixlF3gs5Z156h0pHi4E2Mndo)

After the successful signup lets try to login once more

![](https://lh5.googleusercontent.com/x7FuBeSWfzLyOsl87BYfT1PIr3xnGJhuqur5fwqmvKsZB97HIw3XmROd5ML5wR8QLBg0auKYXOuD9llgaLsvFemXRpvk3B1KPBQRRZtj-h5Oa8f90Mcn1E0C_5rsQtFGF6R1N1Us-NPwk7eF4bxmsHo)

Here we can see that a JSON web token has been generated

Now lets try to invoke the get users endpoint without the token![](https://lh5.googleusercontent.com/5ZI2XioYd7JfO4MIfvpnb9W0yo3u6mY0IPMT0KGmuQa-rSqWH9kK-AQ0zpWUkSxMWhKTFxN8VTC_Bz_tpIgz12J5WEVbVq5QGgHRL_ZBk1pqunfmuXOa3c0SUQwKHu5FTU-Ofm3wGXhWINmmjaNQiag)

It is showing unauthorized

Lets try to put the token and try fetching the users once again

![](https://lh5.googleusercontent.com/hOMQqiuY6P6BbGUgu07uLhCcdYcpygLqSHmO0QAXgAxr3Gc728Hnnq08elbMgjklt2B7J2vaD7MfxRVnhYFwRk9Le1sPWln0MyD_8wDgZe9lDCw2IBNJefB4QwmFb0ArlGLoJ3l1X7eAcIp4RBTreeM)

We can now access the authorized content

**![](https://lh6.googleusercontent.com/Y7ZVBNqdIYOhoScP1BUfj24lHqESrMWSc8lCWbWLT_d-Ycx3catTWg2a2TNPbn8_lKd_MYNDPXHX_e0E6mIzfV07nyCtfUOvbs_-w0u3GOHyMQRwrKihB_26OevtcAYuTkiD9uSTqvavsdM4lK7gHMU)**


