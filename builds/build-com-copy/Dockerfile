FROM nginx:latest
LABEL maintainer="David Ferreira"

RUN echo '<h1>Sem conteudo</h1>' > /usr/share/nginx/html/content.html
# Vai copiar o arquivo index.html para a pasta especificada
COPY index.html /usr/share/nginx/html/