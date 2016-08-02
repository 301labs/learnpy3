# install pyenv 

```shell

yum install -y zlib-devel bzip2 bzip2-devel readline-devel sqlite sqlite-devel openssl-devel
yum install -y libxml2 libxml2-devel libxml2-python libxslt libxslt-devel

curl -L https://raw.githubusercontent.com/yyuu/pyenv-installer/master/bin/pyenv-installer | bash

echo 'export PATH="/root/.pyenv/bin:$PATH"' >> /root/.bash_profile
echo 'eval "$(pyenv init -)"' >> /root/.bash_profile
echo 'eval "$(pyenv virtualenv-init -)" ' >> /root/.bash_profile

source /root/.bash_profile

time pyenv install 2.7.11
time pyenv install 3.4.5
time pyenv install 3.5.1

```
