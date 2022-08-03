# cuda-sample
CUDA official sample codes

usage examples:

cd /cuda-sample/1_Utilities/p2pBandwidthLatencyTest


vi Makefile  
#1 edit the `CUDA_PATH` (eg. /usr/local/cuda which is the cuda install path).  
#2 edit the SMS ?= 20 30 35 37 50 52 to SMS ?= 30 35 37 50 52 ( or other meet the capblity value)

make

./p2pBandwidthLatencyTest

