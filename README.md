# MMK-Summation

Two eyes, Two views, and finally, One summary! Towards Multi-modal Multi-tasking Knowledge-Infused Medical Dialogue Summarization

# Abstract
We often summarize a multi-party conversation in two stages: chunking with homogeneous units and summarizing the chunks. Thus, we hypothesize that there exists a correlation between homogeneous speaker chunking and overall summarization tasks. In this work, we investigate the effectiveness of a multifaceted approach that simultaneously produces summaries of medical concerns, doctor impressions, and an overall view. We introduce a multi-modal, multi-tasking, knowledge-infused medical dialogue summary generation (MMK-Summation) model, which is incorporated with adapter-based fine-tuning through a gated mechanism for multi-modal information integration. The model, MMK-Summation, takes dialogues as input, extracts pertinent external knowledge based on the context, integrates the knowledge and visual cues from the dialogues into the textual content, and ultimately generates concise summaries encompassing medical concerns, doctor impressions, and a comprehensive overview. The introduced model surpasses multiple baselines and traditional summarization models across all evaluation metrics (including human evaluation), which firmly demonstrates the efficacy of the knowledge-guided multi-tasking, multimodal medical conversation summarization

### Please create a new environment for the dependencies using the following command:

	conda env create -f environment.yml

### Activate conda environment after installation by using the command:

	conda activate environment
	
### PreProcessing:

	 python pre_processing.py (Inside Data folder)
   
### Training and Testing:
 
 #### For MM-MDS
  
    python MM-MDS.py
    
####  For MMK-Summation
    
    python MMK-Summation.py
    
#### For Ablation Study, please go to folder named AS

    python MM-MDS with MCS.py
    -------------------------

# Citation
If you find this code useful in your research, please consider citing:
```
@article{saha2024two,
  title={Two eyes, Two views, and finally, One summary! Towards Multi-modal Multi-tasking Knowledge-Infused Medical Dialogue Summarization},
  author={Saha, Anisha and Tiwari, Abhisek and Ruthvik, Sai and Saha, Sriparna},
  journal={arXiv preprint arXiv:2407.15237},
  year={2024}
}
```
    
