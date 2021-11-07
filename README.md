# gemsw
QC8 and testbeam 

instructions for setting up
```bash
scram p -n QC8Test CMSSW CMSSW_12_1_0_pre3
cd QC8Test/src
cmsenv
git clone https://github.com/DanielEstrada971102/gemqc8.git
scram b -j 10 (-----?-------)
```
