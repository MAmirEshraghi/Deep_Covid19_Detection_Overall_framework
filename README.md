# Deep_Covid19_Detection_Overall_framework
# Efficient Framework for Detection of COVID-19 Omicron and Delta Variant Based on Two Intelligent Phases of CNN Models (X-ray and CT-Scan images)

Due to the COVID-19 pandemic and the imminent collapse of healthcare systems following the excessive consumption of financial, hospital, and medicinal resources, the World Health Organization (WHO) changed the alert level on the COVID-19 pandemic from high to very high. Meanwhile, the world began to favor less expensive and more precise COVID-19 detection methods. Machine vision-based COVID-19 detection methods especially Deep learning as a diagnostic technique in the early stages of the disease have found great importance during the pandemic.

Fig 1: The proposed framework for detection COVID-19 based on two phase of CNN models and Radiology modalities:


![Model](https://user-images.githubusercontent.com/92205834/146656597-0aa7871a-af92-4050-ae58-9e946bc7a77e.png)


- Results of detection Models:

1- First phase (X-Ray images):
![image](https://user-images.githubusercontent.com/92205834/152779627-1838e708-0c30-4725-9344-cd70274ff317.png)
![image](https://user-images.githubusercontent.com/92205834/152779656-ea08457a-1204-492d-a0aa-b0d5414839b6.png)

2- Second phase(CT-scan imagse):
![image](https://user-images.githubusercontent.com/92205834/152779773-c840785e-3f90-417e-8dd7-dd73ce872e22.png)
![image](https://user-images.githubusercontent.com/92205834/152779781-ac99f6ba-fe58-42ba-84e0-ca4f2c3961ae.png)


Results of detection on 25 random samples from the test set. “N” is image index number, “P” is predicted value and “GT” is grand truth label. Caption in green color means correct detection and red means wrong:

![image](https://user-images.githubusercontent.com/92205834/152779135-de6a777b-469b-42ea-99f5-01e5f1408a41.png)
![image](https://user-images.githubusercontent.com/92205834/152779227-a68a9bbf-c60b-472b-9212-9a2b2ea61b51.png)


We also made available a large public COVID-19 lung CT scan dataset. it contains 14,482 CT scans which include 12,231 positive cases (COVID-19 infection) and 2251 negative ones (normal and non-COVID-19). Data is available as 512×512px JPG images and also made available a small public COVID-19 chest X-Ray dataset. it contains 341 X-Ray images which include 111 positive cases (COVID-19 infection) and 230 negative ones (normal and non-COVID-19). Data is available as 512×512px JPG images and have been collected from real patients in radiology centers of teaching hospitals of Tehran, Iran. 
The aim of this datasets is to encourage the research and development of effective and innovative methods such as deep CNNs which are able to identify if a person is infected by COVID-19 through the analysis of his/her CT scans and X-rays. As a baseline for this datasets, we used a CNN-based approach inspired by transfer learning which we could achieve an accuracy of 99.7% for CT-Scan and 98.83% for X-ray dataset which is very promising.

CT-Scan Dataset is available at: ---Soon.
X-ray Dataset is available at: ----Soon.

You may also access the paper: ----Soon.

