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
cd flask-Project
python -m venv my_env
 .\my_env\Scripts\activate
pip install -r requirements.txt
```
## Run the Applicaion
```sh
flask run
```

