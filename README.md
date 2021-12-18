# Deep_Covid19_Detection_Overall_framework
#Efficient Framework for Detection of COVID-19 Delta Variant Based on Two Intelligent Phases of CNN Models (X-ray and CT-Scan images)

Due to the COVID-19 pandemic and the imminent collapse of healthcare systems following the excessive consumption of financial, hospital, and medicinal resources, the World Health Organization (WHO) changed the alert level on the COVID-19 pandemic from high to very high. Meanwhile, the world began to favor less expensive and more precise COVID-19 detection methods. Machine vision-based COVID-19 detection methods especially Deep learning as a diagnostic technique in the early stages of the disease have found great importance during the pandemic.

Fig 1: The proposed framework for detection  COVID-19 based on two phase of CNN models and Radiology modalities:

![Model](https://user-images.githubusercontent.com/92205834/146656597-0aa7871a-af92-4050-ae58-9e946bc7a77e.png)


Results of detection on 25 random samples from the test set. “N” is image index number, “P” is predicted value and “GT” is grand truth label. Caption in green color means correct detection and red means wrong:

![test-result](https://user-images.githubusercontent.com/92205834/146656592-3aa1b3b7-9bda-49d1-a367-5e56901d8a22.png)

![test_result](https://user-images.githubusercontent.com/92205834/146656605-600443ae-df0b-44c3-a0a3-48c9e9934fbe.png)

We also made available a large public COVID-19 lung CT scan dataset. it contains 14,482 CT scans which include 12,231 positive cases (COVID-19 infection) and 2251 negative ones (normal and non-COVID-19). Data is available as 512×512px JPG images and also made available a small public COVID-19 chest X-Ray dataset. it contains 341 X-Ray images which include 111 positive cases (COVID-19 infection) and 230 negative ones (normal and non-COVID-19). Data is available as 512×512px JPG images and have been collected from real patients in radiology centers of teaching hospitals of Tehran, Iran. 
The aim of this datasets is to encourage the research and development of effective and innovative methods such as deep CNNs which are able to identify if a person is infected by COVID-19 through the analysis of his/her CT scans and X-rays. As a baseline for this datasets, we used a CNN-based approach inspired by transfer learning which we could achieve an accuracy of 99.7% for CT-Scan and 98.83% for X-ray dataset which is very promising.

X-ray Dataset is available at: -------.
CT-Scan Dataset is available at: -------.
You may also access the paper: --------.

