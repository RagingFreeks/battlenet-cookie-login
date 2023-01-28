# Battle.net-Cookie-Login
Log into Battle.net Accounts using a cookie

How to use the script.

Before you start, open a cmd and cd into the folder you've downloaded (With the python file, the bat, and the requirements.txt) and 
type "pip install -r requirements.txt"

1. Install https://mitmproxy.org/
2. After mitmproxy is installed, click the windows key and search "Proxy settings".
3. Open the Proxy Settings and scroll down until you see "Use a proxy server". Enable it.
4. For Address enter "127.0.0.1" and for the port enter "8080". Click save.
5. Open a command prompt and type "mitmdump", keep this open for now.
6. Open a web browser and go to "mitm.it".
Manual Installation
Double-click the P12 file to start the import wizard.
Select a certificate store location. This determines who will trust the certificate – only the current Windows user or everyone on the machine. Click Next.
Click Next again.
Leave Password blank and click Next.
Select Place all certificates in the following store, then click Browse, and select Trusted Root Certification Authorities.
Click OK and Next.
Click Finish.
Click Yes to confirm the warning dialog.
7. When the page loads, follow the instructions for the windows certificate installation.
8. Once the certificate is installed, run the "LoadScript.bat" by double clicking it. You can now close the "mitmdump" console window.
9. When the console asks to paste a cookie, paste it and click enter.
10. Launch the Battle.net Client, if the cookie is valid the account will be signed in.


![GIF](https://i.imgur.com/rapXLEg.gif)
