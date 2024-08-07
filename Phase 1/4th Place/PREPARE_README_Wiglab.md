This readme file was generated on 2024-07-18 by Gagan Wig, Ziwei Zhang, & Micaela Chan

# GENERAL INFORMATION

Title of Dataset: 
ADNI Resting-state Functional Brain Networks 

Abstract:
The dataset consists of functional MRI brain networks of healthy and cognitively impaired individuals, collected under the Alzheimer's Disease Neuroimaging Initiative (ADNI). Recent work from our group using similar datasets as that included in the current package has demonstrated that measures of large-scale functional brain network organization differ in relation to both healthy aging and Alzheimer's Disease (AD) dementia severity (Zhang et al., 2023) and that changes in functional brain network organization are prognostic of AD dementia beyond known markers of disease risk (Chan et al., 2021). These observations indicate that brain network organization can provide unique information towards AD characterization and prediction. The dataset provided includes neuroimaging data from multiple ADNI cohorts. Brain networks were created for participants that had usable resting-state fMRI data, after preprocessing and data cleaning procedures that minimized known sources of artifact. In addition to each individual's brain networks, target measures of their AD-related cognitive impairment are included, defined by the clinical dementia rating (CDR and CDR sum-of-boxes). These measures were clinically assessed within one year of the resting-state fMRI scan. The dataset includes participants with both cross-sectional data (i.e., 1 scan session of neuroimaging data) and those with longitudinal data (i.e., multiple scan sessions over time). Cross-sectionally, the dataset includes 393 healthy participants (CDR = 0), 326 very mild dementia (CDR = 0.5), 71 mild dementia (CDR = 1) and 17 moderate dementia (CDR = 2) patients (age range: 55 – 96 years old, Female = 422); this totals to 807 unique participants. Out of the 807 participants, 385 have longitudinal MRI scans and with CDR scores at multiple timepoints, some of which exhibit a progression of cognitive impairment over time (ranging from 2 to 10 scans, age range: 55 – 94 years old, Female=191). The dataset lends itself examination of large-scale brain network organization and multivariate models of AD dementia severity and prediction. 

__Author/Principal Investigator Information__

* Name: Gagan Wig
* ORCID: 0000-0002-6432-5192

__Date of data collection:__ 2005-08-01 - 2023-9-14 

__Geographic location of data collection:__
ADNI, multi-site across states, USA (see https://adni.loni.usc.edu/about/centers-cores/study-sites/)

__Information about funding sources that supported the collection of the data:__

Data collection and sharing for this project was funded by the Alzheimer's Disease Neuroimaging Initiative (ADNI) (National Institutes of Health Grant U01 AG024904) and DOD ADNI (Department of Defense award number W81XWH-12-2-0012). ADNI is funded by the National Institute on Aging, the National Institute of Biomedical Imaging and Bioengineering, and through generous contributions from the following: AbbVie, Alzheimer's Association; Alzheimer's Drug Discovery Foundation; Araclon Biotech; BioClinica, Inc.; Biogen; Bristol-Myers Squibb Company; CereSpir, Inc.; Cogstate; Eisai Inc.; Elan Pharmaceuticals, Inc.; Eli Lilly and Company; EuroImmun; F. Hoffmann-La Roche Ltd and its affiliated company Genentech, Inc.; Fujirebio; GE Healthcare; IXICO Ltd.;Janssen Alzheimer Immunotherapy Research & Development, LLC.; Johnson & Johnson Pharmaceutical Research & Development LLC.; Lumosity; Lundbeck; Merck & Co., Inc.;Meso Scale Diagnostics, LLC.; NeuroRx Research; Neurotrack Technologies; Novartis Pharmaceuticals Corporation; Pfizer Inc.; Piramal Imaging; Servier; Takeda Pharmaceutical Company; and Transition Therapeutics. The Canadian Institutes of Health Research is providing funds to support ADNI clinical sites in Canada. Private sector contributions are facilitated by the Foundation for the National Institutes of Health (www.fnih.org). The grantee organization is the Northern California Institute for Research and Education, and the study is coordinated by the Alzheimer's Therapeutic Research Institute at the University of Southern California. ADNI data are disseminated by the Laboratory for Neuro Imaging at the University of Southern California.

# ABSTRACT:
The dataset consists of functional MRI brain networks of healthy and cognitively impaired individuals, collected under the Alzheimer's Disease Neuroimaging Initiative (ADNI). Recent work from our group using similar datasets as that included in the current package has demonstrated that measures of large-scale functional brain network organization differ in relation to both healthy aging and Alzheimer's Disease (AD) dementia severity (Zhang et al., 2023) and that changes in functional brain network organization are prognostic of AD dementia beyond known markers of disease risk (Chan et al., 2021). These observations indicate that brain network organization can provide unique information towards AD characterization and prediction. The dataset provided includes neuroimaging data from multiple ADNI cohorts. Brain networks were created for participants that had usable resting-state fMRI data, after preprocessing and data cleaning procedures that minimized known sources of artifact. In addition to each individual's brain networks, target measures of their AD-related cognitive impairment are included, defined by the clinical dementia rating (CDR and CDR sum-of-boxes). These measures were clinically assessed within one year of the resting-state fMRI scan. The dataset includes participants with both cross-sectional data (i.e., 1 scan session of neuroimaging data) and those with longitudinal data (i.e., multiple scan sessions over time). Cross-sectionally, the dataset includes 393 healthy participants (CDR = 0), 326 very mild dementia (CDR = 0.5), 71 mild dementia (CDR = 1) and 17 moderate dementia (CDR = 2) patients (age range: 55 – 96 years old, Female = 422); this totals to 807 unique participants. Out of the 807 participants, 385 have longitudinal MRI scans and with CDR scores at multiple timepoints, some of which exhibit a progression of cognitive impairment over time (ranging from 2 to 10 scans, age range: 55 – 94 years old, Female=191). The dataset lends itself examination of large-scale brain network organization and multivariate models of AD dementia severity and prediction.  


# BACKGROUND:
The dominant model of Alzheimer’s Disease (AD) formalizes measurement of brain pathology and structural degeneration towards AD characterization and prediction (AT(N); Jack et al., 2016). However, at a given level of pathological burden and atrophy, there is variability in cognitive function; in fact, some individuals can exhibit a high degree of amyloid yet be cognitively healthy (i.e., “Reserve”; Stern, 2009). It is clear that missing variables related to brain function need to be accounted for to better understand disease expression, which would improve onset detection and diagnosis. Functional brain networks are a way of representing the organization and function of the brain (Rubinov & Sporns, 2010; Wig, 2017). Recent work from our group using similar datasets as that included in the current package has demonstrated that measures of large-scale functional brain network organization differ between healthy aging and AD severity (Zhang et al., 2023) and that changes in functional brain network organization are prognostic of AD (Chan et al., 2021). These observations indicate that brain network organization can provide unique information towards AD characterization and prediction.

The unique offering of the present dataset are individual functional brain networks, derived from rigorously processed resting-state fMRI data. The utility of incorporating measures of brain network organization and function in models of AD prediction necessitates careful processing and curating the relevant data types. Functional MRI data is notoriously susceptible to artifacts from the scanner, cardiac and respiratory signals, and head- motion (Power et al., 2012; Van Dijk et al., 2012), which are known to alter the correlation of resting-state signals (Power et al., 2014; Satterthwaite et al., 2013; Van Dijk et al., 2012). Our team has helped develop processing pipelines for effectively cleaning this data (Han et al., 2018, 2024; Savalia et al., 2017). The data provided have underwent rigorous preprocessing and quality checking to ensure that variance related to these known artifacts have been attenuated (Zhang et al., 2023).

# METHODS:
Description of methods used for collection/generation of data: 
Participants included in the current study were recruited through the Alzheimer’s Disease Neuroimaging Initiative (ADNI; for detailed information on the project, see http://www.adni-info.org). Data were collected under ADNI GO, ADNI 2, and ADNI 3 studies, and data were downloaded directly from the ADNI database, all before September 14, 2023. Written consent was obtained from all participants, and each study was approved by the Institutional Review Board at each participating institution.

MRI scans were obtained on 3T scanners in multiple scanning sites using standard scanning protocols under the ADNI protocol. General information about scanning protocols can be found at https://adni.loni.usc.edu/methods/mri-tool/mri-analysis/.

Methods for processing the data:
The structural and functional neuroimaging data underwent rigorous preprocessing and quality checking to attenuate variance related to several sources of known artifacts, using methods developed by both our laboratory and others. Description of data cleaning below is focused on both structural and functional (resting-state) brain images. 

i. Pre-processing of structural images 

The processing of structural images was performed using FreeSurfer 6.0 to create cortical surface images. Structural processing included brain extraction, tissue segmentation, generation of white matter and pial surfaces, inflating surfaces to a sphere, and surface shaped-based spherical registration for the participant’s native surface to fsaverage surface (Dale et al., 1999; Fischl et al., 1999). A single deformation map was created for each participant. The map combined two different deformation maps: one was generated when registering an individual’s native surface to FreeSurfer’s fsaverage atlas, and the other was generated through registering fsaverage-aligned data to a hybrid left–right fsaverage surface (fs_LR; Van Essen et al., 2012). Each individual’s native FreeSurfer generated output was registered to fs_LR using the single deformation map in a one-step resampling procedure.  

ii. Pre-processing of fMRI resting-state images 

To obtain measures of functional connectivity, accurate measurement of brain structure is also necessary (i.e., to map the cortical surface, to identify sub-cortical regions of interest, etc.). As such, the description below begins with our procedures for processing structural magnetic resonance imaging (MRI) images, followed by details on pre-processing functional MRI images.

The processing of structural images (T1-weighted MRI images) was performed using FreeSurfer 6.0 to create cortical surface images. Structural processing included brain extraction, tissue segmentation, generation of white matter and pial surfaces, inflating surfaces to a sphere, and surface shaped-based spherical registration for the participant’s native surface to fsaverage surface (Dale et al., 1999; Fischl et al., 1999). A single deformation map was created for each participant. The map combined two different deformation maps: one was generated when registering an individual’s native surface to FreeSurfer’s fsaverage atlas, and the other was generated through registering fsaverage-aligned data to a hybrid left–right fsaverage surface (fs_LR; (Van Essen et al., 2012). Each individual’s native FreeSurfer generated output was registered to fs_LR using the single deformation map in a one-step resampling procedure.  

Resting-state fMRI images (blood oxygen dependent imaging; BOLD) were processed using a standard fMRI preprocessing pipeline using Nipype 0.8.0. The preprocessing steps included the following: (1) slice-timing correction because of interleaved slice acquisition; (2) rigid body correction for estimating and correcting head movement between frames; and (3) realignment to the T1-weighted image from the same session. All steps were performed using FSL 6.0, except for realignment between frames and rigid body correction. SPM8 was used for realignment and rigid body correction, as it provided more accurate estimates in our processing stream.

After initial fMRI preprocessing, resting-state functional correlation (RSFC) processing was applied to the preprocessed fMRI data using the following steps: (i) demean/detrend, (ii) multiple regression of tissue signal (grey matter [global signal regression], white matter, ventricle) and Friston 24 motion regressor (Friston et al., 1996), (iii) motion “scrubbing” (Power et al., 2014) where motion-contaminated frames were interpolated and replaced (contaminated frames were identified as having > 0.3mm frame-wise displacement [FD; a measure of head-motion from one volume to the next, calculated as the sum of the absolute values of the differentiated realignment estimates] or were between two contaminated frames that were less than 5 frames apart), (iv) bandpass filtering (0.009-0.8Hz), and (iv) removal of interpolated frames used for preserving time series during bandpass filtering in step (iii). 

Considerable evidence has shown that older age is associated with greater amounts of head movement (Mowinckel et al., 2012; Van Dijk et al., 2012; Savalia et al., 2017), which has been shown to systematically alter the correlation structure of resting-state signals (Van Dijk et al., 2012; Satterthwaite et al., 2013; Yan et al., 2013; Power et al., 2014, 2015; Zeng et al., 2014). To this end, while a part of the global signal may contain variance related to general levels of arousal and neural activity (Schölvinck et al., 2010; Keller et al., 2013), a major component of the global signal includes spatially nonspecific signal artifacts related to head motion, cardiac signals and breathing (Satterthwaite et al., 2013; Power et al., 2014, 2015, 2017). Removing the global signal thus helps control these known influences of artifact (Yan et al., 2013; Power et al., 2014, 2017). As no method presently exists for denoising known artifactual signals while retaining all remaining “real” signals, the alternate option of retaining the global signal in each participant is likely to result in misestimation of correlations and the resultant network measures. Based on these considerations, the RSFC processing description above includes a series of motion-processing procedures, including global signal regression (GSR) together with data- censoring (“scrubbing”) and signal-processing procedures, as these procedures have been shown to best reduce global and distance-dependent artifacts (Power et al., 2014; Ciric et al., 2017). As such, the resulting RSFC data have been processed to greatly reduce variance attributable to motion-, respiration- and cardiac-related signals that could artifactually inflate functional correlation between brain areas that are close to each other in acquisition space (i.e., 3D voxel space). 

iii. Quality control

Quality control (QC) for structural images was performed by manually inspecting images for skull-stripping quality, functional to anatomical registration, and anatomical to group-atlas registration. Any scans with subpar skull-stripping or registration were reprocessed with custom parameters. Structural data that failed skull-stripping or registration were excluded from further processing/analysis. 

QC for functional images include checking the quality of signal by calculating the mean, standard deviation, and signal to noise ratio (SNR) for each voxel (across time) for each scan session. This step detects the outliers of fMRI signal in voxel-level signal. After removing of head motion related artifacts (i.e., scrubbing), only sessions with at least 100 BOLD frames remaining were retained for further analysis.  
After functional data were mapped to the brain surfaces, surface-mapping QC included manual inspection of the mapped image. Data that did not contain full converge of the cortex or failed the mapping process were excluded. 

iv. Brain network construction

Brain networks were constructed using the preprocessed resting-state data, for each individual(s) MRI session(s) that passed quality checks (as described above). 

Our generation of brain networks are based on first defining biologically plausible brain network nodes (Wig et al., 2011). In the case of the functional MRI data we are processing, these nodes correspond to brain areas and plausible sub-divisions of brain areas. We have led and been involved with the development of methods to achieve this parcellation task (e.g., Power et al., 2011; Chan et al., 2014; Wig et al., 2014b, 2014a; Han et al., 2018). 

For the present dataset, a functional correlation matrix was constructed for each participant. The correlation matrix was generated with 441 surface-based cortical nodes that were defined with boundary-based analyses (Chan et al., 2014; Wig et al., 2014b), and 61 volume-based subcortical nodes (Seitzman et al., 2020). Cortical nodes were generated with the following steps: (1) identifying putative area centers that were the local minima of a previously published RSFC-boundary map (Cohen et al., 2008; Wig et al., 2014b); (2) creating disks with a radius of 3 mm around the identified area centers to avoid area borders that may exhibit more variance between individuals. Subcortical nodes were 4.5mm radius sphere created using MNI coordinates provided by Seitzman et al. (2020), resulting in the following 61 subcortical and cerebellar nodes: hippocampus (4), amygdala (2), basal ganglia (16), thalamus (12), cerebellum (27). 

The pairwise Fisher’s z-transformed correlation of all nodes was computed to create a correlation matrix (brain network). The first 100 cleaned RSFC frames were used for this analysis, to limit the bias introduced by using unequal number of frames in derivation of resting-state matrices (Han et al., 2024). 

Each cortical/subcortical node was assigned to a large-scale functional system (Power et al., 2011). For cortical nodes, all vertices within a node disk were identified based on their spatial overlap with an a priori vertex-wise community map in the same fs_LR space (Power et al., 2011), where each disk was labeled with a functional system based on a winner-take-all approach. The subcortical nodes were assigned to the same a priori vertex wise community map (Power et al., 2011) based on the similarity of their patterns of resting-state correlations to the cortical systems. Specifically, functional timeseries of the voxels in the subcortex (Morel, 2007) and cerebellum (Diedrichsen et al., 2009) were correlated with the mean cortical network timeseries (after partialing out the other networks), and assigned to a specific cortical network (Seitzman et al., 2020). The anatomical parcel was assigned to a cortical network based on a winner-take-all approach, and sphere regions of interest (ROIs) were created in those parcels and labeled based on the same cortical network. 


__Instrument- or software-specific information needed to interpret the data:__
None; data are provided as plain text files.

__Standards and calibration information, if appropriate:__ N/A

__Environmental/experimental conditions:__ N/A

__Describe any quality-assurance procedures performed on the data:__
Quality control (QC) for structural images were performed by manually inspecting for skull-stripping quality, functional to anatomical registration, anatomical to group-atlas registration. Any scans with subpar skull-stripping or registration were reprocessed with custom parameters. Structural data that failed skull-stripping or registration were excluded from further processing/analysis. QC for functional images include checking the quality of signal by calculating the mean, standard deviation, and signal to noise ratio (SNR) for each voxel (across time) for each scan session. This step detects the outliers of fMRI signal in voxel-level signal. After removing of head motion related artifacts (i.e., scrubbing), only sessions with at least 100 frames remaining were retained for further analysis. After functional data were mapped to the brain surfaces, surface-mapping QC included manual inspection of the mapped image. Data that did not contain full converge of the cortex or failed the mapping process were excluded. 

# DATA DESCRIPTION:

__File List:__

1. individual MRI session functional brain network matrices
2. spreadsheet of target variables and other predictor variables
3. data dictionary for spreadsheet data
4. brain network community assignment for node set
5. relevant articles for derived measures provided

__Relationship between files, if important:__

* brain network community assignment (4) describes the sub-network assignment of network nodes in the brain network matrices (1; each row/column is a node of the network)
* data dictionary (3) includes description for each column in the spreadsheet (2)

__Additional related data collected that was not included in the current data package:__
 
The ADNI repository includes additional information on participant demographics and cognitive and clinical assessments. In addition, ADNI includes genetic data, PET imaging data (AD-related pathology [amyloid and tau deposition], FDG), and biospecimen data obtained from blood, urine and cerebrospinal fluid (CSF) samples. 

__Are there multiple versions of the dataset?__ 
No

__If yes, name of file(s) that was updated:__ 
N/A

__Why was the file updated?__
N/A

__When was the file updated?__
N/A

# RELEASE NOTES:
1.0 - Initial Version

# ETHICS:
Participants included in the current study were recruited through the Alzheimer’s Disease Neuroimaging Initiative (ADNI; for detailed information on the project, see http://www.adni-info.org). Data were collected under ADNI GO, ADNI 2, and ADNI 3 studies. Written consent was obtained from all participants, and each study was approved by the Institutional Review Board at each participating institution.

Personally identifiable information (PII) is collected as part of ADNI, the data is de-identified in the accessible dataset to minimize the risk of re-identification. Information that directly identifies a participant (i.e., direct identifiers) such as name, contact info (e.g., phone, email, address) are not included in the de-identified data. Some indirect identifiers that may indirectly identify participants when combined with other information are available (e.g., year/month of birth, race, gender). 

# CONFLICTS OF INTEREST:
None.

# PRIMARY REFERENCES:
* Zhang Z, Chan MY, Han L, Carreno CA, Winter-Nelson E, Wig GS, et al. Dissociable Effects of Alzheimer’s Disease-Related Cognitive Dysfunction and Aging on Functional Brain Network Segregation. J Neurosci. 2023 Nov 15;43(46):7879–92. doi: 10.1523/JNEUROSCI.0579-23.2023
* General protocols of ADNI MRI data collection can be found at: https://adni.loni.usc.edu/methods/documents/



# ACCESS:

__Licenses/restrictions placed on the data:__

Researchers interested in using the ADNI data need to submit a data access request to ADNI, which is reviewed by the ADNI Data and Publications Committee (DPC; https://adni.loni.usc.edu/data-samples/access- data/#access_data). The review process does not judge the merit of the scientific question, but largely exist to ensure compliance that the data is being shared with the scientific community; thus, the review process is quick and is used to check whether the applicant is affiliated with a scientific or educational institution, or has a legitimate reason to request the data. Being part of this competition should meet the requirement for data access. 
Once the researcher is approved by the DPC, they will be provided with a login to access the IDA https://ida.loni.usc.edu/. After logging in, the researcher is free to access the relevant data. The functional network products produced by our project team will be propagated back to ADNI and be available via the ADNI data access portal. 

__Links to publications that cite or use the data:__ https://adni.loni.usc.edu/news-publications/publications/

__Links to other publicly accessible locations of the data:__ N/A

__Links/relationships to ancillary data sets:__ N/A

__Was data derived from another source?__ No, only ADNI data was used to derive the included data.

__If yes, list source(s):__ N/A

__Recommended citation for this dataset:__ Zhang Z, Chan MY, Han L, Carreno CA, Winter-Nelson E, Wig GS, et al. Dissociable Effects of Alzheimer’s Disease-Related Cognitive Dysfunction and Aging on Functional Brain Network Segregation. J Neurosci. 2023 Nov 15;43(46):7879–92. doi: 10.1523/JNEUROSCI.0579-23.2023

# DISCOVERY:

1.	Zhang Z, Chan MY, Han L, Carreno CA, Winter-Nelson E, Wig GS, et al. Dissociable Effects of Alzheimer’s Disease-Related Cognitive Dysfunction and Aging on Functional Brain Network Segregation. J Neurosci. 2023 Nov 15;43(46):7879–92. doi: 10.1523/JNEUROSCI.0579-23.2023

This study from our group (Zhang et al. 2023) demonstrates that the functional brain networks extracted from an earlier version of this dataset contain informative signals differentiating AD from normal aging, and differentiating severity of AD-related cognitive dysfunction.


# VERSIONS: 
1.0

# FILES: 
* PREPARE_wigneurolab_README.md
* ADNI_target_and_other_predictor_N1526_20240620.csv
* data_dictionary_20240510.csv
* network_node_information_Chan441_Seitzman61.txt
* rsfc_brain_network_matrices/<PTID>_<fMRI_Date>_502x502_rsfc_network_Chan441Seitzman61.txt


# DATA-SPECIFIC INFORMATION FOR : 
* README.md
    + README file describing the dataset.
* ADNI_target_and_other_predictor_N1526_20240620.csv
    + Spreadsheet data containing target and additional predictor variables (e.g., demographic); see data_dictionary_20240510.csv for variable description
* data_dictionary_20240510.csv
    + Data dictionary for target_and_other_predictor.csv
* network_node_information_Chan441_Seitzman61.txt
    + Network nodes' community assignment to functional system; used for grouping RSFC network nodes together for extracting summary metrics.
* rsfc_brain_network_matrices/ (sub-directory)
    + Resting-state functional correlation matrix for each MRI session. File name for each session is named by the participant's PTID and the session's fMRI_Date (in YYYYMMDD format). 

__Number of variables:__ 10 variables 

__Number of cases/rows/samples:__ 1526 rows

__Variable List:__ Variables included in the target_and_other_predictor.csv are as follow: participant ID, age, sex, education, fMRI session date, Global CDR score, CDR sum of boxes (CDR-SOB) score. CDR assessment date, pre-scrubbing FD and post-scrubbing FD. For details about these variables, please see data dictionary.

__Missing data codes:__ NA=Not Available

__Specialized formats or other abbreviations used:__ none.
