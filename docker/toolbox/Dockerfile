FROM alpine
RUN apk add --update --no-cache curl py-pip 
RUN pip install awscli
RUN apk --purge -v del py-pip
CMD tail -f /dev/null