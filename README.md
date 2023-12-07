# NMRbox condor configuration 

## Machine attributes

The following attributes are defined on NMRbox:
- **Production** is a machine with [NMRbox software](https://nmrbox.nmrhub.org/software) installed. By default, jobs are 
   limited to production machines.
- **Release** is a machine version as listed on the [hardware](https://nmrbox.nmrhub.org/hardware) page.
- Slightly modified software versions are available as attributes. Underscores and dashes in software names
  are removed.
    - *NMRpipe* versions will be implemented as **NMRPIPE**.
    - *CcpNmr Analysis Assign* is implemented as **CCPNMRANALYSISASSIGN**. 

## Version
NMRbox is currently running HTCondor version 10. We expect to upgrade to HTCondor 23 late 2023 or early 2024.

## Tutorial
See the [NMRbox HtCondor tutorial](https://github.com/NMRbox/htcondor-tutorial) for a walkthrough on how to
use the NMRbox environment.


