+ Visual Studio Code öffnen
+ Menü: File -- Open -- Folder
+ STRG + Ö (Terminal)

+ node -v --> >v10.15.3
+ Update Node.js (Windows Installation) --> https://nodejs.org/de/
+ node -v --> >v12.12.0

+ yarn -v --> >1.15.2
+ Update yarn (Windows Installation) --> https://yarnpkg.com/en/docs/install#windows-stable
+ yarn -v --> >1.19.1

+ npm -v -- >6.9.0
+ npm install --global --production npm-windows-upgrade
+ npm -v -- >6.9.0
+ Run PowerShell as Administrator
    + Set-ExecutionPolicy Unrestricted -Scope CurrentUser -Force
    + npm install -g npm-windows-upgrade
    + npm-windows-upgrade
    + npm-windows-upgrade --npm-version latest
+ npm -v --> >6.12.0

+ npm list -g --depth=0
+ npm outdated -g (npm version 6.9.0: Bei Fehler: https://stackoverflow.com/questions/55440912/npm-outdated-error-cannot-read-property-length-of-undefined)
+ npm update -g (kein Versionssprung)
+ npm outdated -g
+ Update mit Versionssprung
    + >npm install -g create-react-app@3.2.0 --save-dev 
    + >npm install -g firebase-tools@7.6.0 --save-dev 
    + >npm install -g yo@3.1.0 --save-dev 
+ npm outdated -g
+ npm list -g --depth=0

+ [optional]
    + Update bei Versionssprung: install packagename@version --save-dev)
    + npm uninstall -g react-router-dom
    + npm uninstall -g to
    + npm install (Boilerplate im aktuellen Verzeichnis)

+ npx create-react-app my-app
+ yarn create react-app my-app --template typescript

+ cd my-app
+ Menü: File -- Open -- Folder --> my-app

+ npm run start, yarn start

!!! GIT !!!

