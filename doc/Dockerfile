FROM nvidia/cuda:11.8.0-devel-ubuntu22.04

RUN apt-get update
RUN apt-get install -y python3 python3-pip

RUN pip3 install torch==1.13.1
RUN pip3 install torchvision==0.14.1
RUN pip3 install torchsummary==1.5.1

RUN pip3 install jupyter notebook
RUN pip3 install numpy==1.24.2
RUN pip3 install pandas==1.5.3 
RUN pip3 install scipy==1.10.0
RUN pip3 install tqdm==4.64.1
RUN pip3 install scikit-learn==1.2.1
RUN pip3 install matplotlib==3.6.3
RUN pip3 install seaborn==0.12.2
RUN pip3 install plotly==5.13.0
RUN pip3 install requests==2.28.2
RUN pip3 install beautifulsoup4==4.11.2
RUN pip3 install Pillow==9.4.0
RUN pip3 install opencv-python==4.7.0.68

RUN pip3 install mlxtend==0.21.0
RUN pip3 install efficientnet-pytorch==0.7.1



#RUN pip3 install graphviz==0.20.1
#RUN pip3 install torchviz==0.0.2


WORKDIR /work

#COPY save/____.py /work/

ENV LIBRARY_PATH /usr/local/cuda/lib64/stubs