FROM selenium/standalone-firefox:2.53.1-beryllium

RUN sudo apt-get update && \
    sudo apt-get install python python-pip vim -y

RUN pip install PyVirtualDisplay==0.2.1 selenium==2.53.6

CMD bash
