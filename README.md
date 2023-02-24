# Xraydetect_GR11

# Overview

Security inspection is a process of checking assets against set criteria and the evaluation of security systems and access controls to ensure safety, which is important to uncover any potential risks in various scenarios, such as public transportation and sensitive departments. In practice, the inspectors are required to monitor the scanned X-ray images acquired by the security inspection machine to uncover prohibited items, such as guns, ammunition, explosives, corrosive substances, toxic and radioactive substances. However, the inspectors struggle to localize prohibited items hidden in messy objects accurately and efficiently, which poses a great threat to safety.

Towards the prohibited item detection in real-world scenarios, we present a large-scale benchmark, i.e., PIDray, which is formed by 47, 677 images in total. To the best of our knowledge, it is the largest X-ray prohibited item detection dataset to date.

# Xray dataset

We compare the existing X-ray benchmarks as follows. “Total” and “Prohibited” indicate the number of total images and the images containing prohibited items in the dataset, respectively. C, O, and I represent Classification, Object Detection, and Instance Segmentation respectively. S, A, and R represent Subway, Airport, and Railway Station respectively.
![''](images/dataset_comparision.png)
There are a total of 12 categories of prohibited items defined in the dataset, namely gun, knife, wrench, pliers, scissors, hammer, handcuffs, baton, sprayer, powerbank, lighter and bullet. Each image is provided with image-level and instance-level annotation. For clarity, we show one category per image.
![''](images/image_samples.png)

