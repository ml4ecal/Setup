# Setup machine

Installation on MiB machine

    pip3 install --upgrade pip
    pip3 install grpcio
    pip3 install tensorflow
    pip3 show keras

    
then you can run

    python3 test.py
    

Alternatively, use dockers:

    https://docs.docker.com/engine/install/centos/
    https://www.tensorflow.org/install/docker
    
    docker run --runtime=nvidia -d -p 8888:8888 --name=jupyter tensorflow/tensorflow:latest-gpu-py3-jupyter
    
    