# aws_eks
## Install or update the AWS CLI
To update your current installation of AWS CLI, download a new installer each time you update to overwrite previous versions. Follow these steps from the command line to install the AWS CLI on Linux.
```
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
```
```
unzip awscliv2.zip
```
```
sudo ./aws/install
```

## To install or update eksctl on Linux

* Download and extract the latest release of eksctl with the following command.
```
curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp
````
* Move the extracted binary to /usr/local/bin.
 ```
sudo mv /tmp/eksctl /usr/local/bin
```
* Test that your installation was successful with the following command.
```
eksctl version
````

## Install using other package management

If you are on Ubuntu or another Linux distribution that supports the snap package manager, kubectl is available as a snap application.
```
snap install kubectl --classic
kubectl version --client
```




