#  RE:TERNAL
-------------

<img src="https://i.postimg.cc/7hwhx4Dp/reternal.png" alt="Drawing" style="width: 300px;"/>

![version](https://img.shields.io/badge/Version-Alpha_0.0.1-orange.svg)

---------------------

RE:TERNAL is a centralised purple team simulation platform. Reternal uses agents installed on a simulation network to execute various known
red-teaming techniques in order to test blue-teaming capabilities. The simulations are mapped to the MITRE ATT&CK framework. This repo contains configuration files that map reternal commands to MITRE techniques. The current techniques are based on the existing META configuration  (https://github.com/uber-common/metta) but reformatted to support reternal's internal command scheduler (+ implemented several structual changes to the format). The script to directly import the mapping files to the reternal backend is available in the Quickstart repository.

#### Reternal components
- **API:** https://github.com/d3vzer0/reternal-backend.git
- **UI:** https://github.com/d3vzer0/reternal-ui.git
- **Agent:** https://github.com/d3vzer0/reternal-agent.git
- **C2:** https://github.com/d3vzer0/reternal-c2.git
- **Quickstart:** https://github.com/d3vzer0/reternal-quickstart.git
- **Mitre/Command Mapping:** https://github.com/d3vzer0/reternal-mitre.git


#### Component installation
Please visit https://github.com/d3vzer0/reternal-quickstart for a quickstart tutorial in order to get all the components running.

