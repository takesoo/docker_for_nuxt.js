# build container

```
$ docker-compose build
```

# create project

define APP_NAME in .env
```
$ docker-compose run --rm -w /src nuxt npx create-nuxt-app <project-name>
```

# chage listen host to '0.0.0.0'
https://ja.nuxtjs.org/faq/host-port/

# start server

```
$ docker-compose up -d
```

# stop server

```
$ docker-compose down
```

# npm instrall

```
$ docker-compose exec nuxt bash

# npm install blabla
```

# 参考元
[docker で nuxt.js を開発環境を建てるだけ](https://qiita.com/kitsuki00/items/ed51dbb254bcc6c94fbd)
