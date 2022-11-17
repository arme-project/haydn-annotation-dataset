# ARME Haydn Annotation Dataset

The Haydn Annotation Dataset consists of note onset annotations from 24 experiment participants with varying musical experience. The annotation experiments use recordings from the [ARME Virtuoso Strings Dataset](https://github.com/arme-project/virtuoso-strings).

## Links
:microscope: [Paper preprint](http://128.84.21.203/abs/2211.08848) [[pdf](http://128.84.21.203/pdf/2211.08848)]  
:memo: [Onset annotations](/annotations/) used in the experiment  
:musical_score: [Musical score](https://github.com/arme-project/virtuoso-strings/tree/main/docs/scores/Haydn_op74_no1_finale_excerpt) for the first 49 bars from Finale of Haydn's Op. 74 No. 1  
:computer: [Supporting website](https://arme-project.co.uk/demos/onset-annotation) with additional experimental results  

## Looking around
* [`annotations NR12`](/annotations/onsets/Q-JH-VN1-NR/12/): Note onset annotations for the normal (NR) performance condition from take 12 (NR12)
* [`type annotations NR12`](/annotations/types/Q-JH-VN1-NR/12/): Note onset type annotations from an expert annotator for NR12.
* [`annotations NR`](/annotations/onsets/Q-JH-VN1-NR/): Onset annotations for NR condition for takes 1-12
* [`annotations SP`](/annotations/onsets/Q-JH-VN1-SP/): Onset annotations for SP condition for takes 1-12
* [`annotations DP`](/annotations/onsets/Q-JH-VN1-DP/): Onset annotations for DP condition for takes 1-12
* [`metadata`](/metadata/experiment_survey.csv): Survey results from experiment participants 
* [`filenames`](/metadata/experiment_filenames.csv): Filenames with corresponding annotator a_IDs (0-24)

## Conditions
* **Normal (NR)** condition represents a concert style performance.  
* **Speeds (SP)** condition includes accelerando and decelerando spontaneously initiated by a single musician (i.e., the leader) throughout each performance.  
* **Deadpan (DP)** condition represents performances, where musicians were asked to play with minimal expression in tempo and accentuation.

For more details please refer to the [paper](http://128.84.21.203/abs/2211.08848) and [ARME Virtuoso Strings Dataset](https://github.com/arme-project/virtuoso-strings).

## Citation
If you use this dataset in your research, feel free to cite this paper:

```bibtex
@article{tomczak2022annotation,
  title={Annotation of Soft Onsets in String Ensemble Recordings}, 
  author={Tomczak, Maciej and Li, Min Susan and Bradbury, Adrian and Elliott, Mark and Stables, Ryan and Witek, Maria and Goodman, Tom and Abdlkarim, Diar and Di Luca, Massimiliano and Wing, Alan and Hockman, Jason},
  journal={arXiv preprint arXiv:2211.08848},
  year={2022}
}
```

## Acknowledgments
This project is kindly funded by Engineering and Physical Sciences Research Council (EPSRC) grant with reference [EP/V034987/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/V034987/1). 
