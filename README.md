# Trained Multiple Sclerosis SuStaIn models

This repository includes the trained model mentioned in the Eshaghi et al 2020 paper (see below for the link). The model has been saved with Python 3's `Pickle` package and can easily be loaded using the same package as a Python dictionary. 

Please check the [pySuStaIn software](https://github.com/ucl-pond/pySuStaIn) and the simulation runs to use this `Pickle` file. The `.pkl` or `Pickle` file has all the information that a trained model has in the simulation run shown in the same repository. The best way to implement it is to load the pickle file and explore the variables inside it. The name of these variables will help you to match where in the simulation runs this `Pickle` file can be used.  

Training and design of this model is explained [here](https://www.medrxiv.org/content/10.1101/19011080v2), which is under peer-review at the time of writing.  

Order of appearance of variables, and their Z-scores, in the sequence array in the `Pickle` file is as follows:

- volume_DGM
- volume_Frontal_lobe
- volume_Limbic_cortex
- volume_Occipital_lobe
- volume_Parietal_lobe
- volume_Temporal_lobe
- t1t2ratio_Cerebellum_White_Matter
- t1t2ratio_Cingulate_White_Matter
- t1t2ratio_Frontal_White_Matter
- t1t2ratio_Parietal_White_Matter
- t1t2ratio_Temporal_White_Matter
- t1t2ratio_Corpus_Callosum
- T2-Flair Lesion load
![Three subtype model](https://github.com/armaneshaghi/trained_models_MS_SuStaIn/blob/main/_3subtypes.png)
