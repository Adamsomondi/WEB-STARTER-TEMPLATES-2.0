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
```

# Angular Project
<p>A minimal Angular project setup using Node,Angular CLI Version  19 and NPM package manager.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
  <pre>
angular-project/
├── README.md
├── angular.json
├── package.json
├── tsconfig.json
├── src/
│   ├── app/
│   │   ├── app.component.html
│   │   ├── app.component.scss
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   └── ...
│   ├── assets/
│   ├── environments/
│   ├── index.html
│   ├── main.ts
│   ├── styles.scss
│   └── ...
├── e2e/
└── ...
  </pre>

   <p><b>Clone this repository</b></p>
   
  Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues.
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-2.0.git
cd  WEB-STARTER-TEMPLATES-2.0/angular-project
npm install
npm run dev
```

# Vue Project

<p>A minimal vue project setup using Node and NPM package manager.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
  <pre>
  vue-project/
├── README.md
├── node_modules/
├── public/
│   ├── favicon.ico
│   └── index.html
├── src/
│   ├── assets/
│   │   └── logo.png
│   ├── components/
│   │   └── HelloWorld.vue
│   ├── App.vue
│   ├── main.js
├── .gitignore
├── package.json
├── package-lock.json
├── babel.config.js
├── vue.config.js
└── ...
  </pre>

     <p><b>Clone this repository</b></p>
     
   Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues.
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-2.0.git
cd  WEB-STARTER-TEMPLATES-2.0/vue-project
npm install
npm run format
npm run dev
```

# fastapi project

<p>A minimal fastapi project setup using Node and NPM package manager,Included with fastapi standard tools.Perfect for quick learning,prototyping and can be scaled for any projects and application</p>
  <pre>
  fastapi_project/
├── app/
│   ├── init.py
│   ├── main.py
│   ├── routers/
│   │   ├── init.py
│   │   └── items.py
│   ├── models/
│   │   ├── init.py
│   │   └── item.py
│   ├── schemas/
│   │   ├── init.py
│   │   └── item.py
│   └── db.py
├── tests/
│   ├── init.py
│   └── test_main.py
├── .gitignore
├── requirements.txt
└── README.md
  </pre>
  
  <p><b>Clone this repository</b></p>
  
   Run   <b>cd ~</b> on linux or <b>cd $HOME</b>  on windows to avoid permission issues before git clone in <b>Anaconda Powershell</b>.
  
 ```sh
git clone https://github.com/Adamsomondi/WEB-STARTER-TEMPLATES-2.0.git
cd  WEB-STARTER-TEMPLATES-2.0/fastapi-project
python -m venv my_env
 .\my_env\Scripts\activate
pip install -r requirements.txt
python -m uvicorn app.main:app --reload --port 8080
```
