# Skin Cancer Detection

## Contents

- [Overview](#overview)
  - [Description](#description)
  - [Dataset](#dataset)
- [Journals](#journals)
- [References](#references)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

Skin cancer can be deadly if not caught early, but many populations lack specialized dermatologic care. Over the past several years, dermoscopy-based AI algorithms have been shown to benefit clinicians in diagnosing melanoma, basal cell, and squamous cell carcinoma. However, determining which individuals should see a clinician in the first place has great potential impact. Triaging applications have a significant potential to benefit underserved populations and improve early skin cancer detection, the key factor in long-term patient outcomes.

### Description

This project is about developing image-based algorithms to identify histologically confirmed skin cancer cases with single-lesion crops from 3D total body photos (TBP). The image quality resembles close-up smartphone photos, which are regularly submitted for telehealth purposes.

This project is part of the ISIC 2024 - Skin Cancer Detection with 3D-TBP.
To find more information about the competition, visit the [ISIC 2024 - Skin Cancer Detection with 3D-TBP](https://challenge2024.isic-archive.com/).

### Dataset

The dataset consists of diagnostically labelled images with additional metadata. The images are JPEGs. The associated .csv file contains a binary diagnostic label (target), potential input variables (e.g. age_approx, sex, anatom_site_general, etc.), and additional attributes (e.g. image source and precise diagnosis).

The datasets contains 15mm-by-15mm field-of-view cropped images, centered on distinct lesions, that were extracted from 3D total body photographs. The official training dataset for the challenge is the SLICE-3D Dataset: 400,000 skin lesion image crops extracted from 3D TBP for skin cancer detection. The official testing dataset contain tiles from a separate set of patients.

Datasets were curated by the International Skin Imaging Collaboration (ISIC) from images contributed from the following sources:

- Memorial Sloan Kettering Cancer Center (USA)
- Hospital Clinic de Barcelona (Spain)
- The University of Queensland (Australia)
- Medical University of Vienna (Austria)
- University of Athens (Greece)
- Melanoma Institute Australia (Australia)
- University Hospital of Basel (Switzerland)
- Alfred Hospital (Australia)
- FNQH Cairns (Australia)

## Journals

- [Linux Setup](bin/README.md)
- [Prerequisite](journal/prerequisite.md)
- [Documentation](journal/documentation.md)

## References

- [ISIC 2024 - Skin Cancer Detection with 3D-TBP](https://challenge2024.isic-archive.com/)
- [ISIC 2024 Kaggle](https://www.kaggle.com/competitions/isic-2024-challenge)
- [KerasCV Starter](https://www.kaggle.com/code/awsaf49/isic2024-kerascv-starter/)
- [Data Descriptor](https://www.nature.com/articles/s41597-024-03743-w)

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the Apache License, Version 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [ISIC 2024 - Skin Cancer Detection with 3D-TBP](https://challenge2024.isic-archive.com/)
- [KerasCV Starter](https://www.kaggle.com/code/awsaf49/isic2024-kerascv-starter/)
- [ISIC 2024 Kaggle](https://www.kaggle.com/competitions/isic-2024-challenge)
- [International Skin Imaging Collaboration (ISIC)](https://www.isic-archive.com/)
- [Memorial Sloan Kettering Cancer Center (USA)](https://www.mskcc.org/)
- [Hospital Clinic de Barcelona (Spain)](https://www.clinicbarcelona.org/)
- [The University of Queensland (Australia)](https://www.uq.edu.au/)
- [Medical University of Vienna (Austria)](https://www.meduniwien.ac.at/web/en/)
- [University of Athens (Greece)](https://en.uoa.gr/)
- [Melanoma Institute Australia (Australia)](https://www.melanoma.org.au/)
- [University Hospital of Basel (Switzerland)](https://www.unispital-basel.ch/)
- [Alfred Hospital (Australia)](https://www.alfredhealth.org.au/)
- [FNQH Cairns (Australia)](https://fnqh.com.au/)
- [Kaggle](https://www.kaggle.com/)
