i2ctools:

cd i2ctools
make
cd lib
export LD_LIBRARY_PATH=`pwd`
cd ../tools
./i2cdetect  -l
