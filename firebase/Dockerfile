FROM node

RUN npm i -g firebase-tools@6.11.0
ADD firebase.bash /usr/bin
RUN chmod +x /usr/bin/firebase.bash

ENTRYPOINT [ "/usr/bin/firebase.bash" ]
