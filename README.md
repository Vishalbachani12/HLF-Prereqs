# HLF-Prereqs

# Ubuntu 16.04/18.04 OS

**If you have ubuntu installed on your machine then you dont need to setup VirtualBox or vagrant for this demo.**

#### Please give the executable permission for all the shell script files
```
cd scripts
sudo chmod +x *.sh
```

#### For Docker Installation
```
cd scripts
sudo ./docker.sh
```

#### For GOLANG Installation
```
cd scripts
sudo ./go.sh
```

**Please logout and login again.**

#### For Verfying the Docker Installation
```
docker --version
docker-compose --version
```
This commands will display the version of the docker installed on your machine.

#### For Verfying the GOLANG Installation
```
go version
```
This commands will display the version of the docker installed on your machine.

#### For Installation of Hyperledger Fabric Binaries
```
cd scripts
sudo -E ./fabric-setup.sh
```
This will download all the necessary binaries of the hyperledger fabric. Script may take upto 30-40 Minutes dependind on your internet speed. It will download approx **1.5GB to 2.5GB**.

#### For Verfying the Installation of all the binaries of Hyperledger Fabric
```
docker images
```
This commands will display all the binaries of the Hyperledger Fabric.

#### For Installation of Hyperledger Certification Authority Binaries
```
cd scripts
sudo -E ./caserver-setup.sh
```
This will download the binaries of the certification authority for the hyperledger fabric.

#### For Installation of JQ - The commandline JSON Processor
```
cd scripts
sudo ./jq.sh
```

#### For Verfying the Installation of JQ
```
jq
```
This commands will display the jq help guide.

#### For Installation of CouchDB
```
cd scripts
sudo ./couchdb.sh
```

# Windows 10 OS

**If you have windows installed on your machine then have to download VirtualBox on your machine.**
- Please download the VirtualBox from [here](https://www.virtualbox.org/wiki/Downloads)
- Help Guide [here](https://itsfoss.com/install-linux-in-virtualbox/)

### Attention

- After succesful installation of Ubuntu 16.04/18.04 on VirtualBox you need to follow all the steps of [ubuntu installation](#ubuntu-16.04-18.04-os) section of this document.




