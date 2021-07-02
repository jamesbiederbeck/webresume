# webresume

This is my website which I host at victor.so

I host my website at Linode, the resume file linked is in their S3 compatible storage, and deployment is handled with docker-compose.
If you want to host my website yourself, for some reason, you just need to do

    git clone https://github.com/jamesbiederbeck/webresume.git
    cd webresume
    #edit whatever you need to in the docker-compose.yml by default the container is exposed on 8005
    docker-compose up -d

Content based on https://github.com/StartBootstrap/startbootstrap-resume, used under MIT license.

View live at https://victor.so 
