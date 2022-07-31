FROM python:3.6
LABEL maintainer="David Ferreira"

RUN useradd www && \
    mkdir /app && \
    mkdir /log && \
    chown www /log

USER www
VOLUME [ "/log" ]
WORKDIR /app
EXPOSE 8000

# O processo que será executado no momento em que o container for executado
ENTRYPOINT [ "/usr/local/bin/python" ]
# Parametro que será passado ao ENTRYPOINT, ou seja, ele vai chamar o python e executar o 'run.py'
CMD [ "run.py" ]