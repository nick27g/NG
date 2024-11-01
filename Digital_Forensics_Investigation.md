### Abstract 

This forensic investigation project, conducted within a virtual lab environment using Autopsy, aimed to examine digital evidence on a workstation associated with a fictitious individual working for an oil company, John Smith. The investigation entailed creating a structured forensic case file, selecting the appropriate data source, and performing an in-depth analysis of files for confidential or suspicious content. Key findings included documents and images labeled as proprietary to the oil company, alongside materials outlining methods for anonymous cryptocurrency transactions and money laundering. Through detailed keyword searches, file type reviews, and metadata analysis, the investigation identified multiple files containing sensitive business strategies, drilling methodologies, and schematics. The presence of these materials suggested a potential violation of company policies, including a non-disclosure agreement (NDA) and acceptable use policy (AUP). Although there was no direct evidence of intent to sell information, the findings raise concerns about unauthorized access and potential risks to the company’s proprietary data. This report summarizes the forensic process, findings, and implications for the oil company's management to consider for further action.

---

### Tool Used
  - Autopsy

---

### Creation of Forensic System Case File in Autopsy

My investigation began by creating a new case in Autopsy. I named the case after the fictitious individual under investigation "JohnSmith". I then saved the case within a folder titled "Evidence Files".

<img width="468" alt="image" src="https://github.com/user-attachments/assets/b8b3550c-e9b2-4059-ba83-7ed2ded6f434">

I then assigned the case number and examiner name.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/063ae501-1f36-49f9-ae31-f2055755f79d">

I kept the default settings on the "Select Host" screen.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/580d1cc3-59da-481b-9acc-d26e4d33f697">

On the "Select Data Source Type" screen, I kept the default selection of "Disk Image or VM File".

<img width="468" alt="image" src="https://github.com/user-attachments/assets/8e900a62-de9d-43d1-ae25-f96f7b87d78c">

On the "Select Data Source screen, I navigated to and selected the JSmith_Q1.001 file as the data source. All other fields were left blank or unchanged.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/142d5397-3e6b-430a-bf51-07a84d171855">

On the "Configure Ingest" screen, I accepted all default configurations.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/9c999679-7029-4e1c-a189-f66ec874c3e9">

Autopsy then loaded the data source previously selected and performed an initial analysis based on previous configurations

<img width="468" alt="image" src="https://github.com/user-attachments/assets/60caf891-e7b7-4005-b3f5-c8846fbf62f8">

---

### Analysis

My analysis began by expanding and reviewing the trees on the left-hand side of the screen. This allowed me to gain a broad, initial perspective of files on the host data source.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/d4891839-9d58-4478-8d32-5b298e9d91e3">

I then reviewed the File Types. There were 379 images discovered and 11 PDF files, including 12 total deleted files.

<img width="93" alt="image" src="https://github.com/user-attachments/assets/2f111ef6-2781-4dc3-8200-0e499d3a897c">

After initial review, I went back to the Data Sources tree and began investigating individual files, most notably files with suspicious names. Upon review, a variety of interesting files were revealed. I first found a confidential document titled "Oil Company data strategy.pdf", which i then exported to an evidence folder

<img width="468" alt="image" src="https://github.com/user-attachments/assets/3241feaa-bb2f-4f16-9edc-cf1fa2bb80ea">

I also found a PDF article about how to anonymously launder money through Cryptocurrency. This file was also exported.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/98e54c59-a4ef-4deb-81ba-d0d831bf6c0f">

I then returned to the File Types tree and reviewd each image by thumbnail. The five images highlighted in the screenshot below reveal schematics for the oil company that John Smith works at.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/965d09a7-8484-4aaf-89bf-cdd864780170">

After reviewing the different file types, I then reviewed all deleted files. More confidential information was found. Documents highlighting business strategy and drilling methodology were exported to an evidence folder

<img width="468" alt="image" src="https://github.com/user-attachments/assets/556beee8-ca6d-4bf7-8229-67371e516177">

I then reviewed the metadata available.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/9b56abe1-dd8e-49c8-be66-71e25a99ffb1">

To make sure nothing was missed, I then performed a keyword search for "condifential" files. 12 results populated, one of which being an image previously found containing schematics related to the oil company.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/25c8b718-dee8-40f5-b35d-eff2eb8b3e96">

More review on confidential files. The file screenshotted below highlighted company goals and other proprietary information.

<img width="468" alt="image" src="https://github.com/user-attachments/assets/98cc8424-e704-4d7d-b933-11ec4f35ba44">

Folder containing exported files from my analysis.

<img width="317" alt="image" src="https://github.com/user-attachments/assets/eb656ca7-9803-44c7-8706-1bf62c548e9d">

---

### Findings Summary

Analysis of the image of John Smith’s workstation revealed multiple pieces of evidence that prove he was indeed in violation of the oil company’s policies. Twelve files were located with the keyword search “confidential” that John Smith did not have approval to access. These files referred to business strategy, data strategy, and drilling methodology. Smith’s computer also contained confidential images of the oil company’s drilling configurations. Access to these confidential documents alone provide enough proof that John Smith indeed violated the oil company’s NDA and AUP.

Furthermore, the discovery of files pertaining to cryptocurrency and how to anonymously make transactions with bitcoin suggest that John Smith may have intended on secretly selling the oil company’s confidential information to competitors. While there is no concrete evidence that he intended to do so, the files uncovered in today’s investigation will be presented to the oil company’s senior management.



