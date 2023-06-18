# icx

### Download and Install oneAPI

Download the oneAPI installer
```
wget https://registrationcenter-download.intel.com/akdlm/irc_nas/18673/l_BaseKit_p_2022.2.0.262_offline.sh
#Install oneAPI
sudo sh ./l_BaseKit_p_2022.2.0.262_offline.sh
```

### Setup ICX(oneAPI) environment variable
```
nano ~/.bashrc
source /opt/intel/oneapi/setvars.sh
export PATH=$PATH:/opt/intel/oneapi/compiler/2022.1.0/linux/bin
```

### Check the version of ICX
```
icx --version
```
