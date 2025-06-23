# QUEST Dataset Repository  

This repository contains the DocILE dataset splits and corresponding ground truth annotations used in the paper "QUEST: Quality-aware Semi-supervised Table Extraction for Business Documents". The data is derived from the original DocILE dataset and processed following the methodology described in our paper.  

## Repository Structure  

- DOCILE_QUEST/  
    - A-train/  
        - GT_train/ # Ground truth annotations for training set  
        - img_and_ocr_train/ # Images and OCR files for training set  
    - A-val/  
        - GT_val/ # Ground truth annotations for validation set  
        - img_and_ocr_val/ # Images and OCR files for validation set  
    - A-test/  
        - GT_test/ # Ground truth annotations for test set  
        - img_and_ocr_test/ # Images and OCR files for test set  

## Dataset Information  

The dataset consists of 958 annotated tables split into:  
- Training set: 670 tables  
- Validation set: 143 tables  
- Test set: 145 tables  

Each subset directory contains:  
- **GT_{mode}/**: Ground truth annotations in JSON format  
- **img_and_ocr_{mode}/**: Corresponding document images (PNG) and OCR files  

## Citations  

If you use this dataset in your research, please cite:  

```bibtex  
@misc{thomas2025questqualityawaresemisupervisedtable,
      title={QUEST: Quality-aware Semi-supervised Table Extraction for Business Documents}, 
      author={Eliott Thomas and Mickael Coustaty and Aurelie Joseph and Gaspar Deloin and Elodie Carel and Vincent Poulain D'Andecy and Jean-Marc Ogier},
      year={2025},
      eprint={2506.14568},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2506.14568}, 
}

@inproceedings{vSimsa2023DocILEBF,  
    title={DocILE Benchmark for Document Information Localization and Extraction},  
    author={vStvep'an vSimsa and Milan vSulc and Michal Uvrivc'avr and Yash J. Patel and Ahmed Hamdi and Matvej Koci'an and Maty'avs Skalick'y and Jivr'i Matas and Antoine Doucet and Micka{\"e}l Coustaty and Dimosthenis Karatzas},  
    booktitle={IEEE International Conference on Document Analysis and Recognition},  
    year={2023},  
    url={https://api.semanticscholar.org/CorpusID:256827641}  
}
