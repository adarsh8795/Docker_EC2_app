commands on ec2
sudo yum install git 

git clone repo

sudo yum install maven 

mvn clean package 

sudo yum install docker

sudo systemctl start docker

sudo systemctl enable docker

sudo docker build -t bootimg .

sudo docker images

sudo docker run -d -p 8080:8080  imageid

done
access it through ip:8080
