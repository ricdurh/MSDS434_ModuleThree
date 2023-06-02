# MSDS434_ModuleThree

ls
mkdir golangdockertest
cd golangdockertest/

cat hello.go   #see the file


# edit the file (ctrl + Z 2x to leave)
vi hello.go
vi go.mod
vi Dockerfile

sudo snap install docker
sudo docker build -t golangdockertest  .
sudo docker run -p 8080:8080  -tid golangdockertest
   
