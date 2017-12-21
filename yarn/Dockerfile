FROM node:carbon
# Change register
RUN echo 'sass_binary_site=https://npm.taobao.org/mirrors/node-sass/\nphantomjs_cdnurl=https://npm.taobao.org/mirrors/phantomjs/\nelectron_mirror=https://npm.taobao.org/mirrors/electron/' >> /root/.npmrc
# Install yarn
VOLUME /data
WORKDIR /data
RUN npm i -g yarn && npm i -g nrm
EXPOSE 8080
CMD [ "bash" ]
