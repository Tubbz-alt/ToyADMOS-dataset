# ToyADMOS dataset
ToyADMOS dataset is a machine operating sounds dataset of approximately 540 hours of normal machine operating sounds and over 12,000 samples of anomalous sounds collected with four microphones at a 48kHz sampling rate, prepared by Yuma Koizumi and members in NTT Media Intelligence Laboratories. The ToyADMOS dataset is designed for anomaly detection in machine operating sounds (ADMOS) research. We have collected normal and anomalous operating sounds of miniature machines by deliberately damaging their components. It is designed for three tasks of ADMOS: product inspection (toy car), fault diagnosis for fixed machine (toy conveyor), and fault diagnosis for moving machine (toy train). For more information, refer to the paper [1]. If you use the ToyADMOS dataset in your work, please cite this paper where it was introduced.

>[1] Yuma Koizumi, Shoichiro Saito, Noboru Harada, Hisashi Uematsu and Keisuke Imoto, "ToyADMOS: A Dataset of Miniature-Machine Operating Sounds for Anomalous Sound Detection," in Proc of Workshop on Applications of Signal Processing to Audio and Acoustics (WASPAA), 2019.
> Paper URL: hogehoge

## Downoads:
Since the total size of each sub-dataset is over 100GB, each sub-dataset is split into 7-9 files by 7-zip (7z-format). The total size of the compressed dataset is approximately 60GB. Download the zip files corresponding to the dataset of interest and use your favorite compression tool to unzip these split zip files. Each sub-dataset can be download at 
- ToyCar: 
 - ToyConveyor
 - ToyTrain

## Detailed description
See the file named DETAIL.pdf

## Usage examples

### Requierment
Chainer: 4.5.0
NumPy: 1.16.2
CuPy:
  CuPy Version          : 4.1.0
  CUDA Build Version    : 9000
  CUDA Driver Version   : 10000
  CUDA Runtime Version  : 9000
  cuDNN Build Version   : 7104
  cuDNN Version         : 7600

hogehoge

## Licence: 
See the file named LICENSE.pdf

## Authors and Contact
- Yuma Koizumi (<koizumi.yuma@ieee.org>, <https://sites.google.com/site/yumakoizumiweb/profile-english>)
- Shoichiro Saito
- Noboru Harada
- Hisashi Uematsu
- Keisuke Imoto
