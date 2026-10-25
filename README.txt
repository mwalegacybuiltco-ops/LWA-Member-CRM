LWA MEMBER HUB - PRIVATE OFFLINE-FIRST PWA

IMPORTANT: A PWA requires initial HTTPS hosting to install on iPhone. This package is not itself a live link. Upload these files unchanged to an HTTPS static host (e.g. GitHub Pages or Firebase Hosting), then open that URL in Safari and use Share > Add to Home Screen > Add. Launch it once with internet, then test in Airplane Mode. After installation, the member records stay on the phone and do not get uploaded to a server by this app. The code and assets are publicly accessible at the hosting URL unless hosting access controls are added. Do not put member data in these source files.

No PIN or account login. This is convenient but not suitable for highly sensitive information. The data lives in local browser storage and does not sync or survive every form of app removal/cleanup. Export JSON backups regularly and protect the backup files. iPhone alerts do not fire when the app is closed; follow-ups are flagged on opening. No push notification service is configured.

To test locally on a computer, serve this folder via localhost (for example: python3 -m http.server 8000) and visit http://localhost:8000. Service workers work on localhost or HTTPS. Opening index.html as a file may prevent offline installation and is not the intended deployment method.
