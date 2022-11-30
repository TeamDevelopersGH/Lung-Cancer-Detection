# lung-cancer-detection (https://www.kaggle.com/c/data-science-bowl-2017)
This is a project based on Data Science Bowl 2017. We tried to propose a solution for the problem but we are still new to Deep Learning so our solution is not the optimal one but it can definitely be improved with some fine tuning and better resources (running with a cloud GPU cluster).

## Overview

Lung cancer claims the lives of 225,000 people annually and costs the healthcare system $12 billion. To provide patients the best chance of rehabilitation and survival, early detection is essential.

Two years ago, the office of the U.S. Vice President spearheaded a bold new initiative, the Cancer Moonshot, to make a decade's worth of progress in cancer prevention, diagnosis, and treatment in just 5 years.

In 2017, the Data Science Bowl was critical milestone in support of the Cancer Moonshot by convening the data science and medical communities to develop lung cancer detection algorithms.

**Using a data set of thousands of high-resolution lung scans provided by the National Cancer Institute, participants developed algorithms that accurately determine when lesions in the lungs are cancerous. This will dramatically reduce the false positive rate that plagues the current detection technology, get patients earlier access to life-saving interventions, and give radiologists more time to spend with their patients.**


In this dataset, you are given over a thousand low-dose CT images from high-risk patients in DICOM format. Each image contains a series with multiple axial slices of the chest cavity. Each image has a variable number of 2D slices, which can vary based on the machine taking the scan and patient.

The DICOM files have a header that contains the necessary information about the patient id, as well as scan parameters such as the slice thickness.

The competition task is to create an automated method capable of determining whether or not the patient will be diagnosed with lung cancer within one year of the date the scan was taken. The ground truth labels were confirmed by pathology diagnosis.

The images in this dataset come from many sources and will vary in quality. For example, older scans were imaged with less sophisticated equipment. You should expect the stage 2 data to be, on the whole, more recent and higher quality than the stage 1 data.
