# ia-assistant-vocale

:: Créer un environnement virtuel
python -m venv venv

:: Activer l'environnement virtuel
venv\Scripts\activate

:: Installer les dépendances depuis le dossier packages
pip install --no-index --find-links=packages -r requirements.txt

:: Démarrer l'application
python main.py


