# Ubuntu 16.04 Building instructions

git clone https://github.com/LIZ-project/lizus-core.git

cd lizus-core/src

chmod 755 leveldb/*

make -f makefile.unix

### For builds check releases

Node port: 19700

JSON port: 19701
