![](/Logo.png)

### An unbalance three-phase OPF integrated with OpenDSS - version beta 0.1
### Valentin Rigoni and Andrew Keane 
### University College Dublin, Ireland 
email: valentinrigoni09@gmail.com

It has been widely demonstrated that active network management (ANM) strategies will be required to avoid the violation of network      operational limits in distribution networks with a rich presence of distributed energy resources (DERs). With the characteristics of     different ANM strategies been varied, e.g. centralized or decentralized, a platform where the benefits and drawbacks of multiple approaches can be easily quantified and benchmarked is required. This work introduces a three-phase optimal power flow (OPF) method which can be directly formulated from any network modelled in OpenDSS. The proposed platform provides the following benefits:

1.	Both OpenDSS and OPF models can be integrated into the same Python script, opening a wide range of simulation opportunities.
2.	It can facilitate the benchmark of decentralized solutions, implemented in OpenDSS, with OPF solutions.
3.	The OPF formulation is flexible and can include any DER model. The objective function and constraints can be modified to explore more decentralized formulations.
4.	With many publicly available OpenDSS distribution networks models, it can expedite the validation of ANM solutions under multiple network topologies.

A test case is generated with a real British low voltage (LV) network. The network consists of residential customers that have adopted domestic-scale PVs. 


### License:
This model is open source software and publicly available. It is published under GNU General Public License 3          (http://www.gnu.org/licenses/). The license guarantees you the freedoms to use, study, share (copy), and modify the software. It is a copyleft license, which means that you can distribute derived works only under the same license terms.

### Citation:
When using this model and any of the provided functions and modified network models, please cite our paper which describes them: 
##### V. Rigoni and A. Keane, "An Open-Source Optimal Power Flow Formulation: Integrating Pyomo & OpenDSS in Python", 2020 IEEE Power and Energy Society General Meeting, Montreal, 2020. *Under review*
    
### Prior to run:
Make sure that you have the Pyomo library in Python and have installed OpenDSS

Check TUTORIALS folder

MAIN_Unbalanced_OPF_RUN runs the main script
