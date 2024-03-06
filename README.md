<p align="center"><img src="https://www.nginx.com/wp-content/uploads/2018/08/NGINX-logo-rgb-large.png" width="100" alt="norsiide"></p>

## Config nginx vhost
[![WebSite](https://img.shields.io/website?down_message=Offline&label=WebSite&up_message=Online&url=https%3A%2F%2Fnorsiide.be)](https://norsiide.be)
[![Discord](https://img.shields.io/discord/1126981605785866341?color=5865f2&label=Discord&logo=discord&logoColor=fff&style=flat-square)](https://discord.gg/EV3fAhFZJT)
* **Contact**
    - Discord [Rejoin notre communauté](https://discord.gg/EV3fAhFZJT)
    - Facebook [Suis nous](https://www.facebook.com/norsiide.dev/)
    - Twitter ( X ) [Follow nous](https://twitter.com/norsiide)
 
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
