# WEB-STARTER-TEMPLATES 2.0
Get started quickly with pre-configured setups.

### Before gitclone
```sh
git config --global http.postBuffer 524288000
git config --global core.compression 0
```
# Flask Project

<p>A minimal Flask project setup using Anaconda Distribution.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
  <pre>
flask_Project/
├── venv/
├── app/
│   ├── init.py
│   ├── routes.py
│   ├── models.py
│   └── templates/
│       └── index.html
├── run.py
├── requirements.txt
├── .env
└── .gitignore
  </pre>
  
   <p><b>Clone this repository</b></p>

   Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues before git clone in <b>Anaconda Powershell</b>.
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-2.0.git
cd  WEB-STARTER-TEMPLATES-2.0/flask-Project
python -m venv my_env
 .\my_env\Scripts\activate
pip install -r requirements.txt
```
## Run the Applicaion
```sh
flask run
```
# React Project
<p>A minimal react project setup using Node and NPM package manager with vite build tool.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
  <pre>
react-project/
├── index.html
├── package.json
├── public/
│   └── favicon.ico
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
├── vite.config.js
└── node_modules/
</pre>
<p><b>Clone this repository</b></p>

Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues.
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-2.0.git
cd  WEB-STARTER-TEMPLATES-2.0/react-project
npm install
npm run dev
