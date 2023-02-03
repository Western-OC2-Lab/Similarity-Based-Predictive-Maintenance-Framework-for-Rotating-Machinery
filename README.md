# Similarity-Based Predictive Maintenance Framework for Rotating Machinery

This is the code for the paper entitled "**Similarity-Based Predictive Maintenance Framework for Rotating Machinery**", presented in the Fifth International Conference on Communications, Signal Processing, and their Applications (ICCSPA’22), Cairo, Egypt, 27-29 December 2022. <br>
Authors: Sulaiman Aburakhia, Tareq Tayeh, Ryan Myers, and Abdallah Shami. <br>
Organization: The Optimized Computing and Communications (OC2) Lab, ECE Department, Western University, London, Canada. <br>

**The paper received the ICCSPA'22 Best Paper Award.**

Within smart manufacturing, data driven techniques are commonly adopted for condition monitoring and fault diagnosis of rotating machinery. Classical approaches use supervised learning where a classifier is trained on labeled data to predict or classify different operational states of the machine. However, in most industrial applications, labeled data is limited in terms of its size and type. Hence, it cannot serve the training purpose. In this paper, this problem is tackled by addressing the classification task as a similarity measure to a reference sample rather than a supervised classification task. Similarity-based approaches require a limited amount of labeled data and hence, meet the requirements of real-world industrial applications. Accordingly, the paper introduces a similarity-based framework for predictive maintenance (PdM) of rotating machinery. 

<p float>
<img src="https://github.com/Western-OC2-Lab/Similarity-Based-Predictive-Maintenance-Framework-for-Rotating-Machinery/blob/main/genral_framework.png"/> 
</p>

The main aspects of the framework are feature extraction and similarity measure. Extracted features should be selected so that they satisfy two main conditions:
<ul>
<li>Describe the inherent characteristics of all operational conditions “classes” in the data.
<li>Have high-discrimination degree between the different operational conditions in the data. 
<br>
</ul>

To perform similarity measure, a reference sample from each operational condition (class) should be available. Since the similarity measure provides a
quantitative value, it can be used to assess the probability that the reference sample and test sample belong to the same operational condition. The higher the similarity, the higher the probability that they belong to the same condition. For more details, please refer to [the paper.](https://ieeexplore.ieee.org/document/10019121)<bR>
  
<p>
<img src="https://github.com/Western-OC2-Lab/Similarity-Based-Predictive-Maintenance-Framework-for-Rotating-Machinery/blob/main/FFT.png"/> 
</p>  
<p>
<img src="https://github.com/Western-OC2-Lab/Similarity-Based-Predictive-Maintenance-Framework-for-Rotating-Machinery/blob/main/STFT.png"/> 
</p>  

 The Performance of the proposed method is evaluated on [the Case Western Reserve University (CWRU) bearing dataset](https://engineering.case.edu/bearingdatacenter). The framework is implemented in Python and Jupyter notebook provided. A function for processing .mat vibration files and creating the dataset is included in the notebook as well.<br>


## Contact Information
For all inquiries or collaboration opportunities please contact: <br>

Email : saburakh@uwo.ca or Abdallah.Shami@uwo.ca <br>
Github: [SulAburakhia](https://github.com/SulAburakhia) or [Western OC2 Lab](https://github.com/Western-OC2-Lab) <br>
Google Scholar: [OC2 Lab](https://scholar.google.com.eg/citations?user=oiebNboAAAAJ&hl=en); [Sulaiman Aburakhia](https://scholar.google.com/citations?user=8x-pPSYAAAAJ&hl=en)



## Citation

If you find this repository useful in your research, please cite as:

S. Aburakhia, T. Tayeh, R. Myers and A. Shami, "Similarity-Based Predictive Maintenance Framework for Rotating Machinery,"2022 5th International Conference on Communications, Signal Processing, and their Applications (ICCSPA), Cairo, Egypt, 2022, pp. 1-6, doi: 10.1109/ICCSPA55860.2022.10019121.

```
@INPROCEEDINGS{10019121,
  author={Aburakhia, Sulaiman and Tayeh, Tareq and Myers, Ryan and Shami, Abdallah},
  booktitle={2022 5th International Conference on Communications, Signal Processing, and their Applications (ICCSPA)}, 
  title={Similarity-Based Predictive Maintenance Framework for Rotating Machinery}, 
  year={2022},
  volume={},
  number={},
  pages={1-6},
  doi={10.1109/ICCSPA55860.2022.10019121}}
```


## Publication

Pre-print is available [here](https://arxiv.org/abs/2212.14550). <br>

