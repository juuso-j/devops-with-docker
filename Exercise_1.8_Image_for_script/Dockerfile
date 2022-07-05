FROM ubuntu

# Note:
# apt-get did not find curl without first executing:
# apt-get update

RUN apt-get update && apt-get install -y curl

COPY ./script.sh .
RUN chmod +x script.sh

CMD ./script.sh




