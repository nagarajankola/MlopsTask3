FROM centos:latest

RUN dnf install wget -y
RUN yum install python36 -y


RUN pip3 install --upgrade pip
RUN pip3 install numpy
RUN pip3 install pandas
RUN pip3 install scikit-learn



ENTRYPOINT  [ "python3" ]
CMD  [ "/DWS/default.py" ]
