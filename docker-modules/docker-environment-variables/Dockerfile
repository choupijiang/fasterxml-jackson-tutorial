FROM alpine:3.18.3

ARG name
ENV env_name $name

COPY greetings.sh .

RUN chmod +x /greetings.sh

CMD ["/greetings.sh"]