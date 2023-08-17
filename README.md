# Embeddings for LOINC & SNOMED CT Codes and Descriptions

This repository contains data and embeddings for SNOMED and LOINC ontology codes. The ontology codes and their corresponding descriptions were generated using the OpenAI API key. The descriptions for LOINC codes were generated using the GPT-3.5 model, while the descriptions for SNOMED codes were generated by François Remy. The details of the citation for the SNOMED descriptions are as follows:

**Citation for SNOMED Descriptions:**
@misc{remy-and-demeester-2023-glossary,
title = "Automatic Glossary of Clinical Terminology: a Large-Scale Dictionary of Biomedical Definitions Generated from Ontological Knowledge",
author = "Remy, François and Demeester, Thomas",
year = 2023
}


## Dataset and Model Information

The dataset containing the generated descriptions and embeddings can be accessed through the Hugging Face model hub. The link to the Hugging Face dataset is [FremyCompany/AGCT-Dataset](https://huggingface.co/datasets/FremyCompany/AGCT-Dataset). This dataset includes both SNOMED and LOINC codes, along with their generated descriptions and embeddings.

## Embeddings Generation

All embeddings for the descriptions and code labels were generated using the ADAv2 model. The ADAv2 model is a powerful language model developed by OpenAI. The generated embeddings capture semantic relationships and meanings in the clinical ontology codes' descriptions and labels.

## Citations

If you use the SNOMED descriptions generated by François Remy, please cite the following paper:

**François Remy and Thomas Demeester. (2023). "Automatic Glossary of Clinical Terminology: a Large-Scale Dictionary of Biomedical Definitions Generated from Ontological Knowledge."**

The paper appeared at ACL BioNLP 2023.

For the use of OpenAI's ADAv2 model for generating embeddings, please follow OpenAI's citation guidelines, which can be found on the OpenAI website.

Please note that access to the dataset and model may require appropriate permissions and adherence to the associated licenses.

Feel free to explore the dataset, embeddings, and utilize them for various research and applications related to clinical terminology and ontology codes. If you have any questions or need further assistance, don't hesitate to reach out!


https://arxiv.org/abs/2306.00665
https://huggingface.co/datasets/FremyCompany/AGCT-Dataset

I found the following facts about _______ in SNOMED CT:
- is a _______
- _______ -> _______
- _______ -> _______

Based on this, write a short description of _______.

----------

I found the following facts about cat scratch disease in SNOMED CT:
- is a Bartonellosis
- Pathological process -> Infection process
- Causative agent -> Genus Bartonella

Based on this, write a short description of CSD.
