# HRTF_relearning_data
This repository holds the dataset for the study "Adaptation rate and persistence across multiple sets of spectral cues for sound localisation" 
by Paul Friedrich and Marc Schönwiesner, 2024

The dataset has the following folder structure:
Participant ID / Condition 
Each participant/condition folder contains:
- a <participant_id>.sofa file, which stores the raw measured DTFs
- the results of the consecutive localization tests as pickle files, titled "localization_<participant id>_<date>,
  which can easily be read with the "slab" python package, using the trialsequence class
- the folder "processed_hrtf> containing the processed DTFs 
- the folder "in_ear_recordings "containing the recordings with the in-ear microphones that were used to compute the DTFs

please refer to the methods section for a detailed description of recording, DTF calculation and processing
