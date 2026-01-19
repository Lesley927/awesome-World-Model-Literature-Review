# Awesome Medical World Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome resources on **Medical World Models** for disease progression simulation, treatment planning, and clinical decision support.

<p align="center">
  <img src="assets/overview.png" width="800">
</p>

> Medical World Models are generative models that simulate future disease states conditioned on clinical decisions, enabling AI-driven precision medicine by bridging generative modeling with medical decision-making.

## Table of Contents

- [Survey Papers](#survey-papers)
- [Medical World Models](#medical-world-models)
  - [Disease Progression Simulation](#disease-progression-simulation)
  - [Patient Trajectory Prediction](#patient-trajectory-prediction)
  - [Treatment Response Modeling](#treatment-response-modeling)
- [Patient Digital Twins](#patient-digital-twins)
- [Clinical Decision Support](#clinical-decision-support)
  - [Reinforcement Learning for Healthcare](#reinforcement-learning-for-healthcare)
  - [Dynamic Treatment Regimes](#dynamic-treatment-regimes)
- [Medical Image Synthesis](#medical-image-synthesis)
- [Evaluation & Benchmarks](#evaluation--benchmarks)
- [Datasets](#datasets)
- [Other Resources](#other-resources)
- [Contributing](#contributing)

---

## Survey Papers

- **Reinforcement Learning in Healthcare: A Survey**  
  Chao Yu, Jiming Liu, Shamim Nemati, Guosheng Yin  
  *arXiv, Aug. 2019* | [[PDF]](https://arxiv.org/abs/1908.08796)

- **Analyzing Patient Trajectories With Artificial Intelligence**  
  Ahmed Allam, Stefan Feuerriegel, Michael Rebhan, Michael Krauthammer  
  *J Med Internet Res, Dec. 2021* | [[PDF]](https://www.jmir.org/2021/12/e29812/)

- **Machine Learning in Modeling Disease Trajectory and Treatment Outcomes: An Emerging Enabler for Model-Informed Precision Medicine**  
  Nadia Terranova, et al.  
  *Clinical Pharmacology & Therapeutics, Jan. 2024* | [[PDF]](https://ascpt.onlinelibrary.wiley.com/doi/10.1002/cpt.3153)

- **Reinforcement Learning for Clinical Decision Support in Critical Care: Comprehensive Review**  
  Siqi Liu, Kay Choong See, Kee Yuan Ngiam, Leo Anthony Celi, Xingzhi Sun, Mengling Feng  
  *J Med Internet Res, Jul. 2020* | [[PDF]](https://www.jmir.org/2020/7/e18477)

- **A Primer on Reinforcement Learning in Medicine for Clinicians**  
  Wenhao Zhang, et al.  
  *npj Digital Medicine, Nov. 2024* | [[PDF]](https://www.nature.com/articles/s41746-024-01316-0)

- **Combining Simulation and Machine Learning in Healthcare: A Literature Review**  
  Various Authors  
  *Journal of Simulation, 2025* | [[PDF]](https://www.tandfonline.com/doi/full/10.1080/17477778.2025.2549092)

---

## Medical World Models

### Disease Progression Simulation

Papers focusing on simulating disease dynamics and progression over time.

- **Medical World Model: Generative Simulation of Tumor Evolution for Treatment Planning** [Jun., 2025]  
  Yijun Yang, et al.  
  *arXiv, 2025* | [[PDF]](https://arxiv.org/abs/2506.02327) [[Project]](https://yijun-yang.github.io/MeWM/)
  > The first world model in medicine that visually predicts future disease states based on clinical decisions.

### Patient Trajectory Prediction

Papers on predicting patient health trajectories and future states.

- **Zero Shot Health Trajectory Prediction Using Transformer** [Sep., 2024]  
  Pawel Renc, et al.  
  *npj Digital Medicine, 2024* | [[PDF]](https://www.nature.com/articles/s41746-024-01235-0)
  > ETHOS: Enhanced Transformer for Health Outcome Simulation using Patient Health Timelines.

- **Large Language Models Forecast Patient Health Trajectories Enabling Digital Twins** [Oct., 2025]  
  Various Authors  
  *npj Digital Medicine, 2025* | [[PDF]](https://www.nature.com/articles/s41746-025-02004-3)
  > DT-GPT: Digital Twin Generative Pretrained Transformer for clinical trajectory prediction.

- **Predicting Healthcare Trajectories from Medical Records: A Deep Learning Approach** [Apr., 2017]  
  Trang Pham, Truyen Tran, Dinh Phung, Svetha Venkatesh  
  *Journal of Biomedical Informatics, 2017* | [[PDF]](https://www.sciencedirect.com/science/article/pii/S1532046417300710)
  > DeepCare: end-to-end deep dynamic neural network for patient trajectory modeling.

- **Modelling Patient Trajectories Using Multimodal Information** [Sep., 2022]  
  Various Authors  
  *Journal of Biomedical Informatics, 2022* | [[PDF]](https://www.sciencedirect.com/science/article/pii/S1532046422002003)

- **Trajectory-Ordered Objectives for Self-Supervised Representation Learning of Temporal Healthcare Data Using Transformers** [Jun., 2025]  
  Various Authors  
  *JMIR Medical Informatics, 2025* | [[PDF]](https://medinform.jmir.org/2025/1/e68138)
  > TOO-BERT: Transformer-based model for EHR trajectory modeling.

- **Real-world Patient Trajectory Prediction from Clinical Notes Using Artificial Neural Networks and UMLS-Based Extraction of Concepts**  
  Various Authors  
  *PMC, 2022* | [[PDF]](https://pmc.ncbi.nlm.nih.gov/articles/PMC8982755/)

### Treatment Response Modeling

Papers on modeling and predicting treatment responses.

- **Simultaneous Forecasting of Vital Sign Trajectories in the ICU** [Apr., 2025]  
  Various Authors  
  *Scientific Reports, 2025* | [[PDF]](https://www.nature.com/articles/s41598-025-99719-w)
  > TFT-multi: Global model for predicting multiple vital trajectories simultaneously.

---

## Patient Digital Twins

Papers on creating digital representations of patients for simulation and prediction.

- **Large Language Models Forecast Patient Health Trajectories Enabling Digital Twins** [Oct., 2025]  
  Various Authors  
  *npj Digital Medicine, 2025* | [[PDF]](https://www.nature.com/articles/s41746-025-02004-3)

- **Simulation of a Machine Learning Enabled Learning Health System for Risk Prediction Using Synthetic Patient Data** [Oct., 2022]  
  Various Authors  
  *Scientific Reports, 2022* | [[PDF]](https://www.nature.com/articles/s41598-022-23011-4)

---

## Clinical Decision Support

### Reinforcement Learning for Healthcare

Papers applying RL to healthcare decision-making.

- **Reinforcement Learning and Its Clinical Applications Within Healthcare: A Systematic Review of Precision Medicine and Dynamic Treatment Regimes** [Jul., 2025]  
  Various Authors  
  *Healthcare, 2025* | [[PDF]](https://www.mdpi.com/2227-9032/13/14/1752)

- **Reinforcement Learning in Personalized Medicine: A Comprehensive Review of Treatment Optimization Strategies**  
  Various Authors  
  *PMC, 2025* | [[PDF]](https://pmc.ncbi.nlm.nih.gov/articles/PMC12096033/)

- **Language Agents for Hypothesis-driven Clinical Decision Making with Reinforcement Learning** [Jun., 2025]  
  Paul Stangel, et al.  
  *arXiv, 2025* | [[PDF]](https://arxiv.org/abs/2506.13474)

### Dynamic Treatment Regimes

Papers on adaptive treatment strategies.

- **Reinforcement Learning in Healthcare: A Survey**  
  Chao Yu, Jiming Liu, Shamim Nemati, Guosheng Yin  
  *arXiv, Aug. 2019* | [[PDF]](https://arxiv.org/abs/1908.08796)

---

## Medical Image Synthesis

Papers on generating synthetic medical images for simulation.


---

## Evaluation & Benchmarks

| Benchmark | Task | Modality | Paper |
|-----------|------|----------|-------|
| MIMIC-III | Trajectory Prediction | EHR | [Link](https://physionet.org/content/mimiciii/1.4/) |
| MIMIC-IV | Clinical Prediction | EHR | [Link](https://physionet.org/content/mimiciv/2.2/) |
| MIMIC-CDM | Clinical Decision Making | EHR + Notes | [Link](https://arxiv.org/abs/2506.13474) |

---

## Datasets

| Dataset | Description | Size | Modality | Link |
|---------|-------------|------|----------|------|
| MIMIC-III | Critical care database | 40K+ patients | EHR | [Link](https://physionet.org/content/mimiciii/1.4/) |
| MIMIC-IV | Updated critical care database | 300K+ patients | EHR | [Link](https://physionet.org/content/mimiciv/2.2/) |
| eICU | Multi-center ICU database | 200K+ patients | EHR | [Link](https://eicu-crd.mit.edu/) |
| Synthea | Synthetic patient generator | Customizable | Synthetic EHR | [Link](https://synthetichealth.github.io/synthea/) |

---

## Other Resources

### Tutorials & Courses

- [Reinforcement Learning in Healthcare - Stanford CS](https://web.stanford.edu/class/cs234/)
- [Machine Learning for Healthcare - MIT](https://mlhc.github.io/)

### Related Awesome Lists

- [awesome-healthcare-foundation-models](https://github.com/Jianing-Qiu/Awesome-Healthcare-Foundation-Models)
- [awesome-medical-vision-language-models](https://github.com/yangzhou12/awesome-medical-vision-language-models)
- [awesome-multimodal-in-medical-imaging](https://github.com/richard-peng-xia/awesome-multimodal-in-medical-imaging)

### Tools & Libraries

| Tool | Description | Link |
|------|-------------|------|
| Synthea | Synthetic patient data generator | [GitHub](https://github.com/synthetichealth/synthea) |
| RL4H | Reinforcement Learning for Healthcare toolkit | [GitHub](https://github.com/rl4h) |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a paper:
1. Fork this repository
2. Add paper information following the format above
3. Submit a pull request

### Paper Format

```markdown
- **[Paper Title](link)** [Mon., Year]  
  Author1, Author2, et al.  
  *Venue, Year* | [[PDF]](link) [[Code]](link) [[Project]](link)
```

---

## Citation

If you find this repository useful, please consider citing:

```bibtex
@misc{awesome-medical-world-models,
  author = {Your Name},
  title = {Awesome Medical World Models},
  year = {2025},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/yourusername/awesome-medical-world-models}}
}
```

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/awesome-medical-world-models&type=Date)](https://star-history.com/#yourusername/awesome-medical-world-models&Date)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Last Updated:** January 2025

**Maintainer:** [Lesley LI](https://github.com/Lesley927)

---

<p align="center">
  <i>If you find this resource helpful, please give it a ⭐️!</i>
</p>
