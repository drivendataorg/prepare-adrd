This readme file was generated on [2024-08-25] by [Wei Bo]

GENERAL INFORMATION

Title of Dataset: Global Vocal Biomarkers for AD/ADRD Recognition
Abstract: Alzheimer's Disease and Related Dementias (AD/ADRD) affect over 55 million people globally, presenting significant challenges for early detection, particularly in underserved communities. To address this, we curated a comprehensive dataset centered on digital voice biomarkers, offering a language-agnostic, non-invasive, and accessible way for early AD/ADRD detection. 
Our curation process involved the careful evaluation, selection, and refinement of speech samples from multiple corpora, ensuring diverse representation of subject demographics and assessment types and prioritizing data completeness, quality, and relevance. Advanced speaker diarization techniques, combined with manual checks and corrections, were employed to ensure that final audio clips—each no longer than 30 seconds—contain only the subject's voice. This meticulous approach guarantees that the curated dataset is robust, reliable, and ideally suited for developing predictive models.
By focusing on early speech and language changes—key indicators of cognitive decline—we extracted essential acoustic features such as pitch, formants, and speech rate. These features, can be combined with comprehensive demographic and clinical data, form the foundation for language-agnostic machine learning models capable of detecting early signs of AD/ADRD. Integrating these models into telehealth platforms aims to improve diagnostic accessibility and accuracy, particularly in under-resourced areas. This work is poised to make a significant contribution to digital diagnostics and cognitive health, providing a scalable and effective solution for early AD/ADRD detection.



Author/Principal Investigator Information
Name: Wei Bo (Author/PI), Wenyao Xu (Team Captain)
ORCID: https://orcid.org/0000-0002-8064-496X


Date of data collection: 
The data spans from 1983 to 2023 across different corpora, with the majority collected after 2015.

Geographic location of data collection: 
The data collection varies across corpora, with contributions from a range of organizations, including hospitals, high schools, and multiple universities. These institutions are located in different countries, including the USA, Canada, China, and Spain.


Information about funding sources that supported the collection of the data: 
The curated dataset includes various corpora from different countries, each supported by a range of funding sources. These include grants from national health and research institutes (e.g., NIH, NIA, Alzheimer’s Assocation), contributions from private foundations, and donations from individual donors. 


ABSTRACT:
We have curated an extensive dataset of speech samples collected from various corpora across different countries. The dataset encompasses individuals with a range of cognitive statuses, including Alzheimer's Disease (AD), probable AD, mild cognitive impairment (MCI), and primary progressive aphasia (PPA), as well as healthy controls. These speech samples, sourced from structured clinical interviews conducted both in person and via telephone, provide a rich and diverse collection of data. To address the inherent variability and complexity of the original datasets, we implemented a comprehensive curation process. This involved structuring and unifying the data to ensure consistency, preprocessing and manually checking the audios for speaker diarization and segmentation to increase the usability, and systematically organizing the associated demographic, geographic, and clinical information to further enhance the dataset's comprehensiveness and reliability.
The curated dataset, which is more coherent, organized, and accessible, holds significant potential for advancing digital diagnostics in Alzheimer's Disease and Related Dementias (AD/ADRD). By leveraging acoustic features extracted from the speech samples, in conjunction with the enriched demographic and cognitive data, researchers can develop machine learning models capable of detecting early signs of cognitive decline. These models are designed to be language-agnostic, ensuring broad applicability across diverse linguistic populations. Moreover, the potential integration of these models into telehealth platforms offers a scalable and accessible solution, particularly beneficial for under-resourced communities, thereby democratizing access to essential diagnostic tools.



BACKGROUND:
As global populations age, the incidence of Alzheimer's Disease and Related Dementias (AD/ADRD) is increasing, driving the need for early diagnostic tools and interventions. Early detection is crucial for effective management, enabling timely interventions that can potentially slow disease progression. In this context, the availability of comprehensive and accessible datasets is vital for training and validating new diagnostic models. Our curated dataset, derived from multiple international corpora, focuses on speech and language patterns and plays a pivotal role in developing tools that detect subtle cognitive changes before severe symptoms appear.
The field of speech analysis has advanced significantly, particularly in using speech and language patterns as biomarkers for cognitive decline. A growing trend in healthcare involves the application of artificial intelligence (AI) and machine learning techniques to analyze complex acoustic features for diagnosing AD/ADRD. This curated dataset is instrumental in developing AI-driven, language-agnostic, non-invasive, scalable, and efficient diagnostic solutions.
One of the main challenges in utilizing large datasets like ours is ensuring data quality and consistency, especially when the data comes from multiple, diverse corpora. Our curation process addresses this by standardizing and organizing the data, removing noise, and isolating subjects' voices, thus enabling effective analysis and model training. This approach ensures the dataset's consistency and reliability across diverse demographic and geographic backgrounds, enhancing its utility in AD/ADRD detection.
Moreover, traditional AD/ADRD research often struggles with inclusivity, frequently underrepresenting minority and underserved populations. Our curated dataset, with its diverse and comprehensive demographic information, helps bridge this gap, improving the generalizability and fairness of research outcomes. By incorporating a wide range of demographic and cognitive data, the dataset supports the development of advanced diagnostic models that are broadly applicable across different linguistic and cultural contexts.
Additionally, the focus on digital voice biomarkers aligns with the broader expansion of telehealth services, particularly in remote diagnostics. The dataset’s potential use in remote assessment tools is especially valuable for reaching patients in underserved or remote areas, extending the reach of healthcare services and making early diagnostic tools more accessible.
In conclusion, this curated dataset is a critical resource for advancing early detection of AD/ADRD, addressing challenges in data quality and inclusivity, and supporting the development of innovative diagnostic tools that are accessible to diverse populations worldwide.



METHODS:
Our approach to utilizing an extensive dataset of speech samples from individuals across a wide range of cognitive statuses, including healthy controls, probable Alzheimer's Disease (AD), AD, mild cognitive impairment (MCI), and primary progressive aphasia (PPA), conducts a comprehensive and meticulous data curation process to ensure consistency, quality, and reliability, making it a valuable resource for advancing research in cognitive decline detection.


Description of methods used for collection/generation of data: 
The collection and generation of data were carried out within the framework of standardized clinical protocols, ensuring that the dataset is both reliable and relevant to AD/ADRD research.
Structured Clinical Interviews: The primary method of data collection involved structured clinical interviews, conducted either in-person or over the telephone to accommodate the diverse needs and circumstances of subjects. These interviews were designed to elicit rich linguistic data that could reveal cognitive impairments characteristic of AD/ADRD. Subjects engaged in narrative speech tasks, picture description tasks, and other language-based activities sensitive to cognitive changes. The interview protocols adhered to established standards in the field, such as the AphasiaBank discourse protocol that enable the interviews elicited comprehensive language samples that could be analyzed for a range of linguistic features, like fluency, coherence, and lexical diversity, ensuring consistency and comparability across the dataset.
Cognitive Assessments: In addition to the interviews, subjects in some corpora underwent a series of cognitive tests aimed at assessing various aspects of cognitive function that might be impacted by AD/ADRD. These tests included widely recognized assessments such as the Montreal Cognitive Assessment (MoCA) and the Mini-Mental State Examination (MMSE), along with other specialized tasks tailored to detect specific cognitive deficits. The results from these assessments provided a quantitative foundation for classifying the cognitive status of subjects.
Data Recording and Archival: All interviews and cognitive test sessions were recorded in digital audio format (MP3), ensuring high-quality, consistent audio data for analysis. The recordings were archived systematically, allowing for easy retrieval and cross-referencing with structured demographic and cognitive data.
References: 
MacWhinney, B., Fromm, D., Forbes, M. & Holland, A. (2011). AphasiaBank: Methods for studying discourse. Aphasiology, 25,1286-1307.
Nasreddine, Z.S., & Julayanont, P. (2017). "Montreal Cognitive Assessment (MoCA): Concept and clinical review." In Cognitive Screening Instruments: A Practical Approach.
Arevalo-Rodriguez, I., Smailagic, N., Roqué i Figuls, M., Ciapponi, A., Sanchez-Perez, E., Giannakou, A., Pedraza, O.L., Bonfill Cosp, X., & Cullum, S. (2015). "Mini-Mental State Examination (MMSE) for the detection of Alzheimer's disease and other dementias in people with mild cognitive impairment (MCI)." Cochrane Database of Systematic Reviews, 3.


Methods for processing the data:
Our data processing approach involved a comprehensive curation and standardization process, integrating data from multiple corpora, ensuring consistency across formats, and maintaining high-quality standards.
Data Integration and Standardization: We began by integrating data from various corpora, each containing individuals who had undergone cognitive and neurological assessments for AD/ADRD. The selected resources included both diagnosed cases and cognitively healthy controls, with the selection criteria emphasizing the size of cohorts, diversity of assessments, and the completeness of demographic data. Corpora with missing or poor-quality audio, or lacking key demographic information were excluded from the final dataset. The integration process involved aligning data stored in different formats—audio files in MP3, demographic information in CHAT format, and cognitive results in Excel or Word documents—into a single, unified database. Audio files were matched with corresponding CHAT file based on subjects' IDs. Simultaneously, additional demographic and cognitive test results from Excel or Word files were linked to the audios using the same unique subject IDs, ensuring a coherent and comprehensive dataset.
Data Cleaning and Quality Assurance: To maintain the integrity of the dataset, we conducted rigorous data cleaning and quality assurance procedures. Initial automated scripts were used to identify and flag missing files, incomplete data entries, and outliers in cognitive scores. Following this, a manual verification process was undertaken to resolve any ambiguities or inconsistencies in the data. Entries with missing audio files or significant data fields, such as age marked as 'NA,' were excluded from the dataset. Additionally, data points that did not meet the quality standards for acoustic analysis—due to poor audio quality—were also removed. This thorough cleaning process ensured that only high-quality, reliable data were retained for further analysis.
Data De-identification and Privacy Protection: In compliance with privacy regulations, all personally identifiable information (PII) was removed or anonymized. This included the removal of names, specific dates, and geographical identifiers beyond the regional level. Subjects were assigned pseudonyms and numeric codes, and any references to specific locations or corpus were generalized or removed to prevent identification. This de-identification process ensured that the dataset adhered to ethical standards while preserving the integrity of the data for research purposes.
Diarization and Audio Curation: During the curation process, we used Pyannote for initial diarization, identifying the patient as the speaker with the longest duration and concatenating their speech segments. To ensure the highest data quality, diarization errors were manually corrected using Audacity. Audio files that did not meet quality standards were excluded. A second round of diarization with WhisperX further refined the segmentation, ensuring that the curated dataset was robust and well-suited for the research objectives of this challenge. To optimize the use of language-agnostic features as biomarkers, audio lengths were curated based on specific criteria. For segments longer than 30 seconds, we selected the 5 to 35-second portion to minimize interruptions from other speakers. For shorter segments, the entire recording was retained. This careful selection process ensured the consistency and reliability of the data for predictive modeling.


Instrument- or software-specific information needed to interpret the data: 
To effectively interpret and analyze the data in this curated dataset, several specific software tools and libraries can be utilized. Below are the recommended software packages and their versions, including necessary libraries and packages:

Python
Version: 3.8
Packages:
numpy: For numerical operations and handling large arrays and matrices.
pandas: For data manipulation, analysis, and handling structured data.
scikit-learn: For machine learning and predictive data analysis, including classification, regression, and clustering algorithms.
matplotlib: For creating static, interactive, and animated visualizations, particularly useful in data exploration and reporting.
librosa: For music and audio analysis, including the extraction of features such as MFCCs (Mel-frequency cepstral coefficients) and chroma features, essential for speech analysis.

R: A Language and Environment for Statistical Computing
Version: 4.0.2
Packages:
tidyverse: For data manipulation and visualization.
lme4: For linear and mixed-effects models.
caret: For machine learning workflows.
ggplot2: For creating advanced graphics and visualizations.

Praat: Doing Phonetics by Computer
Version: 6.1.09
Usage: Praat can be used for acoustic analysis, allowing the extraction of features such as pitch, formants, intensity, and duration from audio recordings.

These software tools and libraries are suggested for optimal data analysis and interpretation, but alternatives may be used based on personal preference or specific project requirements.


Standards and calibration information, if appropriate:
When analyzing this curated dataset, it is essential to adhere to specific standards and calibration practices to ensure the accuracy and reliability of the results.
Speech analysis calibration: It's important to standardize the process of feature extraction. This includes setting consistent parameters for filters, such as high-pass or low-pass filters, to ensure uniformity across all audio files. Additionally, the methods for segmenting audio and determining overlapping windows should be applied consistently. When calculating statistical acoustic features—such as pitch, formants, intensity, and duration—using standardized time frames and measurement techniques across all samples is essential for maintaining the integrity of the analysis.
Statistical analysis standards: Data normalization is a critical step. To account for variations due to factors like age, gender, and baseline cognitive performance, procedures for normalizing data should be standardized. This could involve techniques like z-scoring to ensure meaningful comparisons across different groups within the dataset. In the context of machine learning, model parameters should be calibrated using a validation dataset to prevent overfitting and to ensure that the model generalizes well to new data. Cross-validation techniques, such as k-fold cross-validation, should be implemented to validate the model settings, thereby optimizing performance and ensuring that the results are robust and reliable.


Environmental/experimental conditions:
When analyzing this curated dataset, it's important to maintain consistency in the computational environment to ensure the reliability and reproducibility of the results. The following considerations should be noted:
Software Versions: Use consistent software versions and tools throughout the entire project. Discrepancies can arise from updates or changes in software, which could affect the outcomes of analyses. Ensuring uniformity in software versions helps to maintain the integrity of the data analysis process.
Hardware Consistency: Ensure that the hardware used for analysis and model training is sufficiently powerful to manage the computational demands, particularly when working with large datasets or complex machine learning models. Consistency in hardware setups is also crucial, as different hardware configurations can affect computational efficiency and the reproducibility of results.
Randomness Control: For computational tasks that involve parallel processing or random number generation—such as splitting data into training and test sets—it's essential to set a seed for randomness control. This practice ensures that the results are reproducible across different runs of the analysis, providing consistency and reliability in the outcomes.
 

Describe any quality-assurance procedures performed on the data:
To ensure the highest standards of data quality and reliability, several quality-assurance procedures were implemented during the curation and analysis of the dataset. These procedures were designed to maintain the integrity of the data and enhance the accuracy of the analyses conducted on the dataset.
Data Integration and Standardization: We began by integrating data from various corpora, including both diagnosed AD/ADRD cases and cognitively healthy controls. The corpora inclusion criterion includes a detailed categorization of cognitive status and rigorous data collection procedures, such as following standard interviews, cognitive tests, and language-based tasks. Our further selection criteria emphasized the size of subject cohorts, diversity of assessments, and the completeness of demographic data. Corpora with missing or poor-quality audio, or those lacking key demographic information, were excluded from the final dataset to ensure robustness. The integration process involved aligning data stored in different formats—audio files in MP3, demographic or cognitive information in CHAT format or Excel or Word documents—into a single, unified database. Audio files were matched with their labels and all other information based on subject IDs. This systematic approach ensured that the dataset was coherent, comprehensive, and ready for in-depth analysis.
Data Cleaning and Quality Assurance: To maintain the dataset's integrity, rigorous data cleaning and quality assurance procedures were implemented. Initial automated scripts were used to identify and flag missing files, incomplete data entries, and outliers in cognitive scores. Entries with missing audio files or significant data fields, such as age and gender marked as 'NA,' were excluded from the dataset. Additionally, data points that did not meet the quality standards for acoustic analysis—due to poor audio quality—were removed. 
Additional Quality Assurance Measures: Advanced speaker diarization techniques, combined with manual checks and corrections, were employed to ensure that final audio clips—each no longer than 30 seconds—contain only the subject's voice with high audio quality. And the use of the eGeMAPS V02 set of acoustic features for predictive analysis was proposed as an additional quality assurance measure. This standardized set of features ensures that the acoustic properties analyzed are relevant and consistent, aiding in the accurate identification of speech patterns indicative of cognitive decline.
 

DATA DESCRIPTION:
[Outline the structure and content of the dataset, including its modules and key variables.]

File List: 
• PREPARE_README_v1.txt: includes all meta data, such as overview of the project, description of the GloVoAD dataset and curation methodology, dataset usage instructions, and details on input/output formats.
• GloVoAD_Structural_v1.csv: include all structural data for each subject, such as labels indicating cognitive status, demographic details (e.g., age, gender, race), and cognitive assessments (e.g., Mini-Mental State Examination (MMSE) and Montreal Cognitive Assessment (MoCA) scores). Each subject is identified by a unique pseudonym code.
• GloVoAD.zip: include all post-diarization audios with 30-second or shorter length, the audios are categorized by label (AD, ProbableAD, PPA, MCI and Control)
• acoustic_data.csv: includes eGeMAPS V02 acoustic features extracted from GloVoAD audios, where each audio is segmented into 200ms clips with a 100ms overlap for acoustic feature extraction. Additionally, it contains all structural information for each subject.
• feature_extraction_samplecode.py: python example code for extracting eGeMAPS V02 acoustic features from GloVoAD audios.
• Data Dictionary and Data Schema.xlsx: contains detailed descriptions about file 'GloVoAD_Structural_v1.csv', such as the names, types, definition and descriptions of each variable or data field. 
• Dataset Instruction for Structural Data.pdf: provides detailed guidance on the structure, organization, and content of the file 'GloVoAD_Structural_v1.csv', outlining the criteria for subject inclusion and the arrangement of demographic and cognitive data.
• Data Management Plan.pdf: outlines the strategies and protocols for the collection, curation, storage, and sharing of the dataset, with a focus on maintaining data quality, subject confidentiality, and adherence to ethical standards.
• Data Use Agreement for Data Science Challenge.pdf: defines the terms and conditions under which the dataset can be accessed and used by authorized individuals. It includes legal and ethical obligations, privacy considerations, and any restrictions on data sharing or publication. The agreement must be signed by users to ensure compliance with the dataset's usage policies. 


Relationship between files, if important: A unique pseudonym identifier for each subject is used to link audio recordings and structured data for each subject.


Additional related data collected that was not included in the current data package: NA


Are there multiple versions of the dataset? No
If yes, name of file(s) that was updated: 
Why was the file updated? 
When was the file updated? 


RELEASE NOTES:
This is the first version of the Global Vocal Biomarkers for AD/ADRD Recognition dataset, which includes audio clips of no more than 30 seconds per subject along with the corresponding structural information. The dataset has undergone extensive curation to unify the varied corpora and systematically organize the demographic, geographic, and clinical data.


ETHICS:
The ethical review process for this curated dataset involved several key measures to ensure the protection of patient privacy and the responsible use of data. 
The curated dataset and accompanying documents are accessible only through the TalkBank database, which is password protected and restricted to participants of the PREPARE Challenge Phase 2. This restricted access ensures that the data is used ethically and in accordance with privacy and consent guidelines.
To access the curated dataset, researchers must register on both the DrivenData platform and the data access page, and they must sign the Data Use Agreement. This agreement establishes a controlled environment for data use, prioritizing the confidentiality and privacy of the data subjects, and ensuring that the dataset is utilized solely for legitimate research purposes.
The dataset is governed by the Creative Commons CC BY-NC-SA 3.0 copyright license, which further stipulates ethical use by allowing sharing and adaptation of the data under non-commercial terms, provided that proper attribution is given.
During the curation process, all specific information that could potentially identify individuals, such as locational details and detailed cognitive assessment information, was excluded. Each subject was assigned a unique pseudonym identifier to ensure anonymity. The curated data includes only general attributes such as age, gender, and health status, thereby minimizing the risk of personal identification and safeguarding the privacy of the participants. These measures collectively ensure that the data is handled with the highest ethical standards.


CONFLICTS OF INTEREST:NA


REFERENCES:
1. TalkBank, August 30, 2017. https://talkbank.org/.
2. “Creative Commons.” CC BY-NC-SA 3.0 Deed | Attribution-NonCommercial-ShareAlike 3.0 Unported | Creative Commons, n.d. https://creativecommons.org/licenses/by-nc-sa/3.0/.
3. “Basic Rules for Data Usage.” TalkBank, n.d. https://talkbank.org/share/rules.html.

ACCESS:
[Detail access policies, licensing information, and any required training for dataset use.]

Licenses/restrictions placed on the data: 
The dataset is governed by the Creative Commons CC BY-NC-SA 3.0 copyright license.
More details can be found at https://talkbank.org/share/ and https://talkbank.org/share/rules.html

Links to publications that cite or use the data: https://talkbank.org/share/citation.html

Links to other publicly accessible locations of the data: NA

Links/relationships to ancillary data sets: NA

Was data derived from another source?
If yes, list source(s): Yes, the raw data source is Talkbank.

Recommended citation for this dataset: TalkBank(2014), from https://talkbank.org/.

DISCOVERY: NA

VERSIONS:
Version 1, release at August 30, 2024.

FILES:
• PREPARE_README_v1.txt: includes all meta data, such as overview of the project, description of the GloVoAD dataset and curation methodology, dataset usage instructions, and details on input/output formats.
• GloVoAD_Structural_v1.csv: include all structural data for each subject, such as labels indicating cognitive status, demographic details (e.g., age, gender, race), and cognitive assessments (e.g., Mini-Mental State Examination (MMSE) and Montreal Cognitive Assessment (MoCA) scores). Each subject is identified by a unique pseudonym code.
• GloVoAD.zip: include all post-diarization audios with 30-second or shorter length, the audios are categorized by label (AD, ProbableAD, PPA, MCI and Control)
• acoustic_data.csv: includes eGeMAPS V02 acoustic features extracted from GloVoAD audios, where each audio is segmented into 200ms clips with a 100ms overlap for acoustic feature extraction. Additionally, it contains all structural information for each subject.
• feature_extraction_samplecode.py: python example code for extracting eGeMAPS V02 acoustic features from GloVoAD audios.
• Data Dictionary and Data Schema.xlsx: contains detailed descriptions about file 'GloVoAD_Structural_v1.csv', such as the names, types, definition and descriptions of each variable or data field. 
• Dataset Instruction for Structural Data.pdf: provides detailed guidance on the structure, organization, and content of the file 'GloVoAD_Structural_v1.csv', outlining the criteria for subject inclusion and the arrangement of demographic and cognitive data.
• Data Management Plan.pdf: outlines the strategies and protocols for the collection, curation, storage, and sharing of the dataset, with a focus on maintaining data quality, subject confidentiality, and adherence to ethical standards.
• Data Use Agreement for Data Science Challenge.pdf: defines the terms and conditions under which the dataset can be accessed and used by authorized individuals. It includes legal and ethical obligations, privacy considerations, and any restrictions on data sharing or publication. The agreement must be signed by users to ensure compliance with the dataset's usage policies. 

DATA-SPECIFIC INFORMATION FOR: GloVoAD_Structural_v1.csv

Number of variables: 2058

Number of cases/rows/samples: 2058

Variable List: 
Variable name: Pseudonym
Description: A pseudonym scheme of Subject's ID.
Unit: None
Variable type: VARCHAR(255)
Constraints: Primary Key, Unique, Not Null

Variable name: Diagnosis
Description: Clinical diagnosis of the subject concerning cognitive conditions, including AD, ProbableAD, MCI (mild cognitive impairment), PPA (primary progressive aphasia) and control.
Unit: None
Variable type: VARCHAR(50)
Constraints: Not Null, Limited to specific categories such as 'AD', 'ProbableAD', 'MCI', 'PPA' and 'Control'

Variable name: Age
Description: Subject's age in years at the time of data collection.
Unit: None
Variable type: INT
Constraints: Not Null, Positive Integer

Variable name: Gender
Description: Gender identity of the subject.
Unit: None
Variable type: VARCHAR(10)
Constraints: Not Null, Limited to specific categories such as 'male' and 'female'

Variable name: Race
Description: Racial or ethnic background of the subject.
Unit: None
Variable type: VARCHAR(100)
Constraints: Nullable, Optional field, label value can be 'White', 'Asia', 'African American', 'Other' and NA/blanks.

Variable name: Language
Description: Language used during the recording of the session. 
Unit: None
Variable type: VARCHAR(10)
Constraints: Not Null, label value can be 'English', 'Mandarin' and 'Spanish'.

Variable name: Handedness
Description: Dominant hand of the subject.
Unit: None
Variable type: VARCHAR(10)
Constraints: Nullable, Optional field, Limited to 'Right', 'Left' and 'Ambidextrous'

Variable name: Education
Description: Highest level of educational attainment by the subject, measured in years or degrees.
Unit: None
Variable type: VARCHAR(10)
Constraints: Nullable, Optional field

Variable name: MoCA
Description: Score from the Montreal Cognitive Assessment, where applicable.
Unit: None
Variable type: VARCHAR(10)
Constraints: Nullable, Optional field, Range typically 0-30

Variable name: MMSE
Description: Score from the Mini-Mental State Examination, where applicable.
Unit: None
Variable type: VARCHAR(10)
Constraints: Nullable, Optional field, Range typically 0-32


Missing data codes: if the data is missing, we use NA or make it blank.

Specialized formats or other abbreviations used: NA
