# App Blog

Using docker for build simple blog website, make sure your server has docker installed.

source: [Digital Ocean](https://www.digitalocean.com/community/tutorials/how-to-make-a-web-application-using-flask-in-python-3)

After clone this repository, just run command below.
> Build Image
```
docker build -t app-blog app1/.
```

> Run Container App

```
docker run -dit --name ct-app-blog -p 5000:5000 app-blog
```

Access your app using web browser on <IP-address:5000>