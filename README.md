# HRTF_relearning_data
This repository holds the dataset for the study "Adaptation rate and persistence across multiple sets of spectral cues for sound localisation" 
by Paul Friedrich and Marc Schönwiesner, 2024

The dataset has the following folder structure:

Participant ID / Condition 

Each participant/condition folder contains:
- a <participant_id>.sofa file, which stores the raw measured DTFs
- a folder "processed_hrtf" containing the processed DTFs
- the results of the localization tests as pickle files, titled "localization_'participant-id'_'date'", 
  which were created using the trialsequence class of the "slab" python package
- the folder "in_ear_recordings" containing the recordings obtained from the in-ear microphones, which were used to compute the DTFs

please refer to the methods section for a detailed description of recording, DTF calculation and processing
