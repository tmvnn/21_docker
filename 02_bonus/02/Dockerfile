FROM debian

MAINTAINER lbellona

RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y build-essential manpages-dev vim git make curl zsh

RUN sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

CMD zsh


#docker build -t cdev .
#docker run -itd --name cdev cdev
#docker exec -it cdev zsh
#git vim gcc zsh