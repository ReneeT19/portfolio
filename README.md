Preview the site with Docker:

```bash
cd html/
docker run --name website -p 80:80 -v $(pwd):/usr/share/nginx/html:ro -d nginx
```

`docker container restart website`
