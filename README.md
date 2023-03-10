# ZJUT-EIFD: A Synchronously Collected External and Internal Fingerprint Database

External fingerprints (EFs) based only on epidermal information are vulnerable to spoofing attacks and non-ideal skin conditions. To solve such shortcomings, internal fingerprints (IFs) collected using optical coherence tomography (OCT) have been proposed and widely researched. However, the development of IF is limited by the lack of in-depth research on the IF and the EF-IF interoperability, which is partially caused by the lack of public OCT data. The obvious gap at the application of EF-IF identification motivated us to design and publish a comprehensive fingerprint database containing both traditional EFs and OCT IFs, denoted as ZJUT-EIFD [1]. 

## Goal of Database

The purpose of the database is mainly to provide data support for the correlation and potential interoperability of internal and external fingerprints. The use of this database to develop new technologies, methods, algorithms or systems for use in the field of biological modalities can be readily acceptable. 

## Acquisition technology

Synchronously acquired Total internal reflection (TIR) and optical coherence tomography (OCT) [2].

![fig2-a](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/Fig2(a).png)

![fig2-b](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/Fig2(b).png)

## Source data

The source data collected by our synchronization device in each measurement includes a grayscale image of TIR and a series of grayscale B-scan images of OCT.

![fig3](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/fig3.bmp)

## OCT fingerprint reconstruction method

The quality and pattern clarity of an OCT fingerprint is directly related to the OCT fingerprint reconstruction method used. To ensure that the reconstruction method has minimal impact on EF-IF correlation studies, the current state of the art contour extraction method BCL-U Net [3] is used in fingerprint construction.

![fig4](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/fig4.png)

## The collection and storage detail of database

![table1](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/table1.png)

![table2](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/table2.png)

![fig22](https://github.com/ZJUT-ERCISS-home/ZJUT-EIFD/blob/main/fig/fig22.png)

## The protocol

A portion of the data is shown in the ZJUT-EIFD folder. Call for protocol and get the complete database via email hxwang@zjut.edu.cn

## reference

[1] This work was submitted to *IEEE Trans. Pattern. Anal. Mach. Intell.*.

[2] H. Sun et al., ???Synchronous fingerprint acquisition system based on total internal reflection and optical coherence tomography,??? *IEEE Trans. Instrum. Meas.*, vol. 69, no. 10, pp. 8452-8465, Apr. 2020.

[3] B. Ding et al., ???Surface and internal fingerprint reconstruction from optical coherence tomography through convolutional neural network,??? *IEEE Trans Inf. Foren. Sec.*, vol. 16, pp. 685-700, Aug. 2021.

