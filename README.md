## Install and run the ntuples:

```
cmsrel CMSSW_11_1_2_patch2
cd CMSSW_11_1_2_patch2/src/
cmsenv

git clone https://github.com/aman0404/GEMDOC_Ntuplemaker.git
scram b -j 5

cd MuDPGAnalysis/MuonDPGNtuples/test/
cmsRun muDpgNtuples_cfg.py
```
