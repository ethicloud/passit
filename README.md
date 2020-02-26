Docker-compose comprenant Passit, une base de données ainsi qu'un reverse proxy.


## PASSIT
* Lors du premier lancement, NE PAS OUBLIER DE LANCER LES MIGRATIONS 
```bash
python manage.py migrate
```
* Configuré pour fonctionner avec le SMTP de GMAIL

### SMTP GMAIL
* [Activer l'autorisation pour les applications moins sécurisées](https://support.google.com/accounts/answer/6010255?hl=fr)

## BDD
* Base PostgreSQL exposée sur le port 5432.

## REVERSE PROXY
* Reverse proxy Nginx avec TLS activé, certificat autosigné.




