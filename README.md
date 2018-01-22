# mv_gen
mviewer generator

Configuration
--------------

La configuration s'effectue dans le fichier config.json. La configuration se d�compose en 3 sections.
La premi�re section concerne le param�trage global de l'application

#### param�tres 

* **upload_service**: Service web utilis� pour stocker les configurations mviewer cr��es avec le g�n�rateur. Valeur par d�faut : ``srv/store.php``. Il est �galement possible d'utiliser le service "Doc service" de Georchestra. exemple  ``../mapfishapp/ws/mviewer/``. Dans le dernier cas, les fichiers de configuration sont stock�s dans la base georchestra.
* **export_conf_folder**: Dossier utilis� pour le stockage des fichiers de configuration mviewer g�n�r�s. Ce param�tre est utilis� si le param�tre pr�c�dent est ``srv/store.php``.
* **mviewer_instance**: url de l'instance mviewer utilis�e. exemple : http://localhost/mviewer/
* **conf_path_from_mviewer**: Chemin permettant de charger le fichier de configuration g�n�r� depuis le mviewer. le chemin peut �tre relatif. Exemple ../mviewer/conf/
* **map** : Param�trage du cadrage initial de la carte gr�ce aux propri�t�s center et zoom.

La deuxi�me section concerne le param�trage des fonds de plan


La derni�re section concerne le param�trage des diff�rents fournisseurs de donn�es

