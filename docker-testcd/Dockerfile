# Utiliser l'image officielle de Python
FROM python:3.9

# D‚finir le dossier de travail dans le conteneur
WORKDIR /app

# Copier les fichiers du projet dans le conteneur
COPY . .

# Installer les d‚pendances
RUN pip install -r requirements.txt

# Exposer le port 5000
EXPOSE 5000

# D‚marrer l'application
CMD ["python", "app.py"]

