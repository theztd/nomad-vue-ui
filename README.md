# Simple nomad dashboard
---

Nomad sily proof of concept dashboard implemented in Vuejs.


```bash

docker run -it --rm -p 8080:80 \
    -v $PWD/:/usr/share/nginx/html/ \
    -v $PWD/default.conf:/etc/nginx/conf.d/default.conf \
    --name nginx nginx

```

This docker staff is required because CORS...
