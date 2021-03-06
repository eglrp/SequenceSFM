# Sequence SfM

This program is a demo to show structure from motion for sequence images input. The program is based on https://github.com/royshil/SfM-Toy-Library, but we fix some bugs and use Qt as the interface. You can add more advanced tricks such used in PTAM or ORB-SLAM, to make it faster and robust. 

## Plateform:
Only test on Linux Mint 17.1 and Linux Mint 18 (64-bit). 

## Requirements:
* **SuiteSparse**: `sudo apt-get install libsuitesparse-dev`
* **Qt4**: `sudo apt-get install libqt4-core libqt4-dev`

## Build: 
```
mkdir build; cd build
cmake ..
make
```

## Usage:
```
./SequenceSFM fn_in=../data/img_sfm_1s
```
    
## Screenshot:
-![alt text](https://raw.githubusercontent.com/bushuhui/SequenceSFM/master/data/SequenceSfM.png "Screenshot 1")


## Project homepage:
http://www.adv-ci.com/blog/source/sequence-sfm/
