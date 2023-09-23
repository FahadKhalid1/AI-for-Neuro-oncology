# AI-for-Neuro-oncology

# Diffuse Intrinsic Pontine Glioma (DIPG) Analysis
The Diffuse Intrinsic Pontine Glioma (DIPG) is a highly aggressive pediatric tumor, characterized by a median overall survival of approximately 11 months. As the tumor is inoperable, radiotherapy emerges as the primary treatment option, typically resulting in a transient improvement.

Genomic analyses reveal that a significant portion of DIPG patients have mutations in genes encoding for histone H3, leading to a lysine 27 to methionine substitution (H3-K27M). This disease is classified under the new WHO designation as diffuse midline gliomas, H3 K27-altered, with the most common alterations being H3.1 and H3.3 variants.

Radiomics & MRI
Multi-modal MRI images are a standard diagnostic tool. The field of Radiomics aims to provide a comprehensive quantification of the radiographic phenotype, aiding clinicians in their diagnostic and treatment strategies. This approach encompasses post-processing of medical images and feature computation from specific regions of interest. A variety of metrics, including morphological, global image intensity, and texture indices, are considered, potentially reflecting the biological intricacies of tumors.

MRI, due to its high spatial resolution, is the preferred imaging method for pediatric patients with central nervous system tumors. However, MRI intensities being non-standardized necessitate specific standardization methods for robust radiomic feature extraction. Efforts focus on addressing intensity variations stemming from various sources, with strategies like Z-score normalization and using a reference tissue for normalization.

In developing our comprehensive approach, we encountered challenges such as missing data and limited available data for training. A multi-model strategy was subsequently adopted, harnessing all available data types, including clinical data and various MRI modalities.
