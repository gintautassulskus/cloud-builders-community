FROM node:lts-stretch-slim

RUN npm i -g firebase-tools@7.3.2

ADD firebase.bash /usr/bin
RUN chmod +x /usr/bin/firebase.bash

ENTRYPOINT [ "/usr/bin/firebase.bash" ]
