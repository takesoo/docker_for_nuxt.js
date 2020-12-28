# nodeのバージョンは推奨版を使用する
FROM node:lts

# locale & timezone (Asia/Tokyo)
# https://github.com/moby/moby/issues/12084
ENV LANG C.UTF-8
ENV TZ Asia/Tokyo

# system update
RUN apt-get update && \
    apt-get install -y vim less git

# install vue-cli
RUN npm install -g npm && \
    npm install -g @vue/cli @vue/cli-init && \
    npm install -g create-nuxt-app
# copy application code from host.
ADD src /src

EXPOSE 3000
