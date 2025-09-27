---
title: "Research"
permalink: /research/
layout: single
---

{% capture biomarker_desc %}
This project is sponsored by the *Indian Council of Medical Research (ICMR)*:
- Proposes an n-cylindrical biomarker by combining Eigen Value Decomposition, FFT, and DWT for interictal epilepsy diagnosis.
- Serves as an assistive tool in doubtful epilepsy cases where MRI and video EEG are normal.
- Introduces a novel ICMR-Epilepsy clinical EEG dataset of 140 subjects (70 epileptic, 70 healthy control).
- Outperforms benchmarks on Siena, CHB-MIT, and Bonn datasets.
{% endcapture %}

{% include research-card.html 
   title="Development of a Novel Biomarker for Epilepsy Diagnosis and Seizure Detection"
   img="/assets/img/research1.jpg"
   desc=biomarker_desc
%}

---

{% capture ht_plv_desc %}
Sponsored by *ICMR*, this project develops a novel ht-PLV (ht-Phase Locking Value) feature:
- ht-PLV feature fed into deep learning models to analyze functional connectivity.
- Helps in doubtful cases where MRI and EEG are normal.
- Contributes a novel ICMR Epilepsy-Mimicker EEG dataset (50 epileptic, 50 mimickers).
- Outperforms benchmarks on Siena dataset.
{% endcapture %}

{% include research-card.html 
   title="Novel ht-PLV Feature for Epilepsy vs Mimickers"
   img="/assets/img/research2.jpg"
   desc=ht_plv_desc
%}

---

{% capture meg_mri_desc %}
Using data from the **BIOMAG-2022 International Data Analysis Competition**:
- Applies LCMV beamforming and kurtosis to localize epileptic hub nodes with sublobar resolution.
- Proposes a pipeline to compute nodal strength of hub nodes over time.
- Studies the network dynamics of epileptic hubs.
{% endcapture %}

{% include research-card.html 
   title="Localization of Epileptic Sites with MEG-MRI"
   img="/assets/img/research3.jpg"
   desc=meg_mri_desc
%}

---

{% capture cogitate_desc %}
As part of the **BIOMAG-2024 Cogitate Connectivity Challenge**:
- Localized conscious content in alpha, beta, and gamma bands using the DICS beamforming technique.
- Proposed a pipeline for network connectivity and hub node identification of conscious states.
{% endcapture %}

{% include research-card.html 
   title="Cogitate Connectivity Challenge (Consciousness Study)"
   img="/assets/img/research4.jpg"
   desc=cogitate_desc
%}

---

{% capture wearneuronet_desc %}
- Proposed a novel WearNeuroNet architecture along with explainable AI (layerwise relevance propagation).  
- Developed for ictal–interictal classification using limited-channel EEG wearables.  

[Read Publication](https://ieeexplore.ieee.org/abstract/document/10570304)
{% endcapture %}

{% include research-card.html 
   title="WearNeuroNet Architecture (Explainable AI)"
   img="/assets/img/research5.jpg"
   desc=wearneuronet_desc
   link="https://ieeexplore.ieee.org/abstract/document/10570304"
   link_text="Read Publication"
   button_link="https://ieeexplore.ieee.org/abstract/document/10570304"
   button_text="Explore More"
%}
