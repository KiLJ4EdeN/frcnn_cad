```bash
sudo yum install protobuf* leveldb-devel snappy* opencv-devel boost-devel hdf5-devel --skip-broken --nogpgcheck
sudo yum install gflags-devel glog-devel lmdb*
```

```bash
git clone https://github.com/BVLC/caffe
pip install Cython numpy scipy scikit-image matplotlib ipython h5py leveldb networkx nose pandas python-dateutil protobuf python-gflags pyyaml Pillow six
```

```bash
sudo nano Makefile.config
```

```bash
CPU_ONLY := 1
/usr/lib64/python2.7/site-packages/numpy/core/include
/usr/lib64/python3.9/site-packages/numpy/core/include/
BLAS := open
BLAS_INCLUDE := /usr/include/openblas
```

```bash
sudo make all
```