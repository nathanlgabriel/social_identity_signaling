All I have to share right now is the code and [some presentation slides](https://github.com/nathanlgabriel/social_identity_signaling/blob/main/gid03_presentation05.pdf). I will upload an early draft of the paper when it is ready.



The .ipynb files are the notebooks used to run simulations. Specifically, I've included a notebook for [a basic version of the model](https://github.com/nathanlgabriel/social_identity_signaling/blob/main/genBS_v0055k_assort_repNOexec_sm_sweep_Merced_top212signals-Copy1.ipynb) from section 2.5 of the paper (of slide 16 of the presentation) and a notebook for producing the [hierarchical double embedding topology](https://github.com/nathanlgabriel/social_identity_signaling/blob/main/genBS_v0055k_repEXEC_sm_sweep_Merced_topC-Copy17.ipynb) (section 2.9.3 of the paper or slide 30 of the presentation). Both notebooks call functions from [this file](https://github.com/nathanlgabriel/social_identity_signaling/blob/main/FNs_genBachStravinsky_v0055k_assort_rep_execNULLsig_SMARTmutation.py), which should be located in the same directory as the notebooks for them to function. The code was only commented for my own use, and I am happy to provide further explainations of the code via email correspondence. I always record the random entropy used to seed the random number generators so results can be replicated exactly if the need arises.




Some varialble names are suboptimal, my appologies. E.g. the notebook for the basic version fo the model prints out "count error", which should not be interpreted as a programming error or a problem with the model. It is merely a lable that was attached to outcomes other than the ones which were being explicitly measured.
