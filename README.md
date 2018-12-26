# Histopathologic Cancer Detection 

## Background

Early cancer diagnosis and treatment play a crucial role in improving patients' survival rate. One of the most  important early diagnosis is to detect metastasis in lymph nodes through microscopic examination of hematoxylin and eosin (H&E) stained histopathology slides.

Significant discordance on detection results among different pathologist has also been reported.

## References

- Deep Learning for Identifying Metastatic Breast Cancer [[arxiv](<https://arxiv.org/pdf/1606.05718.pdf>)].
- Detecting Cancer Metastases on Gigapixel Pathology Images [[arxiv](https://arxiv.org/pdf/1703.02442.pdf)]
- Pathology-images-analysis-using-CNN (<https://github.com/sdw95927/pathology-images-analysis-using-CNN>)
- Localize the tissue regions in whole slide pathology images. (<https://github.com/PingjunChen/tissueloc>)
- Cancer metastasis detection with neural conditional random field (NCRF) [pdf](https://openreview.net/pdf?id=S1aY66iiM) [[github](https://github.com/baidu-research/NCRF)]

## Dataset

PatchCamelyon (PCAM) benchmark dataset [[github](https://github.com/basveeling/pcam)].

It consists of 327.680 color images (96x96 px) extracted from histopathologic scans of lymph node sections. Each image is annotated with a binary label indicating presence of metastatic tissue.  

## Concepts

- **Whole slide imaging (WSI)**

  Refers to scanning of conventional glass slides in order to produce digital slides, is the most recent imaging modality being employed by pathology departments worldwide.
