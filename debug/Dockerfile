FROM almalinux:9
RUN dnf install telnet net-tools iputils bind-utils -y 
RUN useradd roboshop
USER useradd 
USER roboshop
CMD ["sleep" ,"1000"]