[<img src='https://s3.amazonaws.com/drivendata-public-assets/logo-white-blue.png' width='600'>](https://www.drivendata.org/)
<br><br>

[<img src='https://s3.amazonaws.com/drivendata-public-assets/prepare-challenge-image-notitle.jpeg'>](https://www.drivendata.org/competitions/group/nih-nia-alzheimers-adrd-competition/)

# The Pioneering Research for Early Prediction of Alzheimer's and Related Dementias EUREKA Challenge

## Goal of the Competition

[Alzheimer's disease and Alzheimer's disease-related dementias (AD/ADRD)](https://www.nia.nih.gov/health/alzheimers) are a group of brain disorders characterized by progressive cognitive impairments that severely impact daily functioning. Early prediction of AD/ADRD is crucial for [potential disease modification through emerging treatments](https://www.nia.nih.gov/health/alzheimers-treatment/how-alzheimers-disease-treated), but current methods are not sensitive enough to reliably detect the disease in its early or presymptomatic stages.

The [PREPARE: Pioneering Research for Early Prediction of Alzheimer's and Related Dementias EUREKA Challenge](https://www.drivendata.org/competitions/group/nih-nia-alzheimers-adrd-competition/) was a multi-year innovation competition supported by the National Institute on Aging (NIA) that advanced methods and data for early prediction of AD/ADRD. Through three phases, over 1,000 participants submitted solutions for open data and innovative methods:

- **Phase 1 - Find IT!**: Solvers from across academia and industry found, curated, or contributed representative and open datasets that can be used for early prediction of AD/ADRD across a range of modalities including neuroimagery, synthetic electronic health records, survey, speech, and mobile apps. [Read more about the results of Phase 1 here.](https://drivendata.co/blog/prepare-phase1-winners)
- **Phase 2 - Build IT!**: Data science solvers advanced algorithms and analytic approaches for early prediction of AD/ADRD, with an emphasis on explainability of predictions, in two data tracks focused on [acoustic voice data](https://www.drivendata.org/competitions/299/competition-nih-alzheimers-acoustic-2/) and [social determinants of health survey data](https://www.drivendata.org/competitions/300/competition-nih-alzheimers-sdoh-2/). [Read more about the results of Phase 2 here.](https://drivendata.co/blog/prepare-phase2-winners)
- **Phase 3 - Put IT All Together!**: Ten top teams from Phase 2 refined their algorithmic approaches, working to make their solutions more rigorous and generalizable to a real-world context. Included a public virtual pitch event, and an in-person winner showcase at the NIH. [Read more about the results of Phase 3 here.](https://drivendata.co/blog/prepare-phase3-winners).

## What's in this Repository

This repository contains submissions from winning competitors in the qualitatively judged [PREPARE Challenge](https://www.drivendata.org/competitions/group/nih-nia-alzheimers-adrd-competition/) DrivenData challenge.

_In this challenge, participants submitted written reports for each phase rather than code solutions. Solution code was reviewed during verification, but earning prizes did not require open-source licensing. If teams have voluntarily shared their code a public repository, the link is included in an .md file in the team's directory._

**Winning submissions for other DrivenData competitions is available in the [competition-winners repository](https://github.com/drivendataorg/competition-winners).**

# Winning Submissions

## Phase 1

| Place | Team or User | Data Summary |
|-------|--------------|--------------|
| **1st Place** | **VBM_CSE_UB** | Provided audio recordings, acoustic features, demographics, and clinical labels for 2,086 participants from [DementiaBank](https://dementia.talkbank.org/). |
| **2nd Place** | **zedlab** | Released 2M synthetic patient records generated from EHR-based models trained on the Truven MarketScan database MarketScan and University of Chicago data. |
| **3rd Place + Disproportionate Impact Bonus** | **IGCPHARMA** | Contributed survey data from 26,839 older adults from [MHAS](https://www.mhasweb.org/Home/index.aspx) and [Mex-Cog](https://www.mhasweb.org/DataProducts/AncillaryStudies.aspx), aligned with the [HCAP](https://hcap.isr.umich.edu/) cognitive protocol. |
| **4th Place** | **gaganwig** | Shared pre-processed resting-state fMRI scans for 1,491 subjects from the [ADNI](https://adni.loni.usc.edu/) neuroimaging initiative. |
| **5th Place** | **EngrDynamics** | Provided survey data from ~1M respondents in the U.S. [NHIS](https://www.cdc.gov/nchs/nhis/index.htm). |
| **Data Idea** | **korinreidellisonlabs** | Proposed a community-driven, de-identified AD-risk dataset combining EHR/claims with biomarker-rich data (e.g., [ADNI](https://adni.loni.usc.edu/)). |
| **Data Idea** | **msundman** | Proposed use of dental radiographs as scalable early AD-risk biomarkers. |
| **Data Idea** | **stephanieruth.young** | Proposed open mobile cognitive screening data via the [MyCog App](https://nihtoolbox.org/mycog/). |

Additional submission details can be found inside the directory for each prize winner.

**Winners Blog Post: [Meet the winners for Phase 1 of the PREPARE Challenge](https://drivendata.co/blog/prepare-phase1-winners)**

## Phase 2

### Acoustic Track

| Place | Team or User | Approach Highlights |
|-------|--------------|---------------------|
| **1st Place** | **ExplainableAD (sheep and cecelia)** | [Whisper](https://github.com/openai/whisper) encoder, using two-stage training (full dataset, then language-specific fine-tuning) with [CAM](https://en.wikipedia.org/wiki/Class_activation_mapping)-based temporal interpretability. |
| **2nd Place** | **Harris and Kielo** | Ensemble combining [eGeMAPS-v2](https://audeering.github.io/opensmile/models/gemaps/) acoustic features with [XGBoost](https://github.com/dmlc/xgboost), and two fine-tuned [Whisper](https://github.com/openai/whisper) classifiers (one using triplet loss) with [all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) semantic clustering preprocessing and XGBoost meta-learner aggregation. |
| **3rd Place + Explainability Bonus**| **team SALEN** | Ensemble combining [Whisper](https://github.com/openai/whisper) encoder voiceprint analysis, [BERT](https://docs.nvidia.com/nemo-framework/user-guide/24.07/nemotoolkit/nlp/information_retrieval.html) semantic embeddings, and EfficientNet mel-spectrogram processing with weighted softmax fusion, enhanced by [SHAP](https://github.com/shap/shap) and [CAM](https://en.wikipedia.org/wiki/Class_activation_mapping) interpretability for clinical decision support.|
| **Special Recognition (data processing) + Explainability Bonus** | **SpeechCARE** | Multi-lingual acoustic–linguistic pipeline combining [eGeMAPS-v2](https://audeering.github.io/opensmile/models/gemaps/) features, transformer embeddings from [wav2vec2](https://huggingface.co/docs/transformers/en/model_doc/wav2vec2) and [Whisper](https://github.com/openai/whisper), extensive preprocessing (noise filtering, anomaly detection, task-ID classification), and multimodal SHAP-enhanced explanations. |
| **Special Recognition (generalizability)** | **IGC Pharma** | Multi-lingual acoustic baseline using fine-tuned [Whisper](https://github.com/openai/whisper) encoder embeddings with comprehensive audio preprocessing and augmentation.|
| **Special Recognition (generalizability)** | **BrainSignsLab** | Developed a hybrid feature extraction pipeline combining traditional acoustic features ([eGeMAPSv2](https://audeering.github.io/opensmile-python/#feature-sets)), transformer embeddings ([Wav2Vec2](https://huggingface.co/docs/transformers/en/model_doc/wav2vec2), [Whisper](https://github.com/openai/whisper)), and demographic data in a feature-selected [XGBoost](https://github.com/dmlc/xgboost)classifier.|

Additional submission details can be found inside the directory for each prize winner.

All solutions in the Acoustic Track were developed using data from the DementiaBank. 

>Lanzi, A. M., Saylor, A. K., Fromm, D., Liu, H., MacWhinney, B., & Cohen, M. (2023). DementiaBank: Theoretical rationale, protocol, and illustrative analyses. American Journal of Speech-Language Pathology. [doi.org/10.1044/2022_AJSLP-22-00281](https://pubs.asha.org/doi/10.1044/2022_AJSLP-22-00281)


### Social Determinants Track

| Place | Team or User | Approach Highlights |
|-------|--------------|---------------------|
| **1st Place** | **RASKA-Team** | Used [TabPFN](https://github.com/PriorLabs/TabPFN)-derived features, engineered demographic and temporal representations, and sequential prediction of three decision trees ([CatBoost](https://github.com/catboost/catboost), [LightGBM](https://github.com/microsoft/LightGBM), [XGBoost](https://github.com/dmlc/xgboost)) followed by regularized regression. |
| **2nd Place** | **NxGTR** | Built a minimal-complexity decision tree-based model ([LightGBM](https://github.com/microsoft/LightGBM)) to predict both speed and acceleration of cognitive decline.|
| **3rd Place** | **Cassandre** | Ensemble of decision tree-based models ([LightGBM](https://github.com/microsoft/LightGBM)), and included controls for age and education. |
| **Special Recognition (feature selection)** | **GiaPaoDawei** | Applied large-scale feature selection using [CatBoost](https://github.com/catboost/catboost) with SHAP-guided recursive removal, and trained a decision tree ensemble ([LightGBM](https://github.com/microsoft/LightGBM), [CatBoost](https://github.com/catboost/catboost)). |
| **Explainability Bonus** | **Nick and Ry** | Prediction explainer report included predicted cognitive score and critical contextual information for non-technical audience understanding, with scores based on appropriate technical methods. |

Additional submission details can be found inside the directory for each prize winner.

All solutions in the Social Determinants Track were developed using data from the MHAS (Mexican Health and Aging Study). 

> MHAS is partly sponsored by the National Institutes of Health/National Institute on Aging (grant number NIH R01AG018016) in the United States and the Instituto Nacional de Estadística y Geografía (INEGI) in Mexico. Data files and documentation are public use and available at [www.MHASweb.org](https://www.mhasweb.org/Home/index.aspx).

**Winners Blog Post: [Meet the winners for Phase 2 of the PREPARE Challenge](https://drivendata.co/blog/prepare-phase2-winners)**

## Phase 3

| Place | Team or User | Track | Approach Highlights |
|-------|--------------|-------|---------------------|
| **1st Place and Clean Code Bonus** | **RASKA-Team** | **Social Determinants** | Harmonized four additional international datasets from the [HCAP network](https://hcap.isr.umich.edu/) and trained an ensemble of [LightGBM](https://github.com/microsoft/LightGBM), [CatBoost](https://github.com/catboost/catboost), and [XGBoost](https://github.com/dmlc/xgboost) with embedded fairness weighting. |
| **2nd Place** | **ExplainableAD** | **Acoustic** | Used non-native and corpus-diverse speech from WLS, PITT, IVANOVA, VAS, and DELAWARE in [DementiaBank](https://dementia.talkbank.org/) plus [Mispeech/Speechocean762](https://huggingface.co/datasets/mispeech/speechocean762) and the [Qwen2.5-omni-3b](https://github.com/QwenLM/Qwen2.5) model to train a fluency-focused disfluency model and deploy an explainable clinical demo. |
| **Runner-up** | **NxGTR** | **Social Determinants** | Incorporated six independent datasets (including from [HCAP network](https://hcap.isr.umich.edu/), [NACC](https://naccdata.org/)) with a unified [LightGBM](https://github.com/microsoft/LightGBM) ADRDModel adaptable to dataset-specific feature sets. |
| **Runner-up** | **Harris and Kielo** | **Acoustic** | Leveraged healthy-speech data from [Mozilla Common Voice](https://commonvoice.mozilla.org/) and synthetic ADRD-symptom text with a hierarchical Bayesian model combining a [BART](https://doi.org/10.1214/09-AOAS285) linguistic module and a CNN–Transformer encoder ([CNN–Transformer overview](https://arxiv.org/abs/2101.01169)) trained on [GeMAPS](https://doi.org/10.1016/j.csl.2016.01.001) features. |

### Additional Clean Code Bonus Winners

- **IGCPharma** (Acoustic)
- **SpeechCARE** (Acoustic)