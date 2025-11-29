<p align="center"><img src="https://blog.desdelinux.net/wp-content/uploads/2022/05/Nginx.jpg" width="auto" alt="norsiide"></p>

### Lien utiles

* **Discord** : [Rejoins notre communauté](https://discord.gg/EV3fAhFZJT)
* **Website** : [Plus d'information](https://norsiide.be)
 
**configation d'un vhost nginx par default**

# Installations du vhost

(1) on créer le fichier 

```
nano /etc/nginx/sites-available/domaine.tld.conf
```

(2) puis on configure le fichier 
 
(3) ensuite on copier le contenue dedans
 
```
ctrl + x puis yes 
```
(4) puis on copier le ficher dans le ( /etc/nginx/sites-enabled )
 
```
 sudo ln -s /etc/nginx/sites-available/domaine.tld.conf /etc/nginx/sites-enabled/
``` 
(5) maintenant on test est on redemarre nginx
 
```
 sudo nginx -t && sudo systemctl restart nginx
```
