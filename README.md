# kuberneteFROM    nginx
RUN     rm -rf /usr/share/nginx/html/*
RUN     echo Hello World >/usr/share/nginx/html/index.htmls