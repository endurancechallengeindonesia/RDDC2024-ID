# RDDC2024-ID-Endurance Challenge Indonesia
# Crowdsourced Road Damage Detection Dataset for Convolutional Neural Network Object Detection - Indonesia

Welcome to our repository housing a comprehensive dataset tailored for convolutional neural network (CNN) object detection tasks, focusing on road damage detection. Our dataset comprises over 9,000 labeled images sourced from various locations throughout Indonesia, making it a valuable resource for researchers and practitioners in the field of computer vision and infrastructure management.

# Key Features

1. **Crowdsourced Labeling**: Each image in our dataset has been labeled by a diverse team of 44 dedicated contributors. Their collaborative efforts ensured accurate annotations for training reliable CNN models.
2. **Diverse Road Damage Types**: Our dataset encompasses five distinct types of road damage: longitudinal crack, lateral crack, alligator crack, pothole, and other road damage. This diversity enables the development of models capable of detecting and classifying various forms of road deterioration.
3. **Indonesian Context**: The images in our dataset originate from real-world roads across Indonesia, providing a contextualized dataset reflective of the unique challenges faced in the region's infrastructure management.
4. **Usable for Object Detection**: Designed specifically for CNN-based object detection tasks, our dataset facilitates the training and evaluation of models to identify and localize road damage instances accurately
5. **YOLO Label Format**: Due to the popularity of the YOLO algorithm for its state-of-the-art performance in several object detection cases in CNN, our dataset label format is available in YOLO format.

# Datasets
You can download the datasets [here](https://drive.google.com/file/d/1AbNe-dhK2ikaK05ATsPUcJXWW_bsz-pp/view?usp=sharing). The zipfile contains 2 folder : Images and Labels. For the labels:

- 0 : Longitudinal Crack
- 1 : Lateral Crack
- 2 : Alligator Crack
- 3 : Pothole
- 4 : Other

# Class Descriptions
**1a. Longitudinal Crack**\
Longitudinal cracks run parallel to the centerline (may be either in the wheel paths or outside). These types of cracks are caused by poor construction of the paving lane joint, shrinkage of the pavement surface as a result of low temperatures, or asphalt hardening and/or daily temperature cycling. 

![Longitudinal Crack](https://raw.githubusercontent.com/endurancechallengeindonesia/RDDC2024-ID/main/images/P2%20-%20Long%20Crack%20Description.png?token=GHSAT0AAAAAACR3DZW634BGYGC5KHKERW74ZRWHBHA)

Severity Levels :
- Low	: Crack widths averaging less than 10 mm or filled cracks of any width in good condition.
- Moderate: Cracks averaging between 10 mm and 75 mm or any crack width up to 75 mm plus adjacent low severity random cracking. 
- High	: Cracks averaging over 75 mm or any crack with average width or less than 75 mm plus adjacent moderate to high severity random cracking.

![Longitudinal / Lateral Crack Severity](https://github.com/endurancechallengeindonesia/RDDC2024-ID/blob/main/images/P1%20-%20Long%20-%20Lat%20Crack%20Severity.png?raw=true)

**1b. Lateral Crack**\
Lateral Cracks are cracks which are predominately perpendicular to the pavement centerline.

![Lateral Crack](https://raw.githubusercontent.com/endurancechallengeindonesia/RDDC2024-ID/main/images/P3%20-%20Lat%20Crack%20Description.png?token=GHSAT0AAAAAACR3DZW622WKKOQ7J7WDPKCKZRWHCWA)

Severity Levels :
- Low	: Any unsealed crack with a mean width up to 10 mm or a crack with good condition sealant plus an undetermined width.
- Moderate: Any crack width averaging between 10 mm and 75 mm or any crack up to 75 mm and adjacent low severity random cracking.
- High	: Any crack width greater than 75 mm or any crack averaging less than 75 mm plus adjacent moderate to high severity random cracking.

![Longitudinal / Lateral Crack Severity](https://github.com/endurancechallengeindonesia/RDDC2024-ID/blob/main/images/P1%20-%20Long%20-%20Lat%20Crack%20Severity.png?raw=true)

**2. Alligator / Fatigue Crack**\
Alligator/fatigue cracking are road damages that occurs in areas subjected to repeated traffic loadings. In the early stages, this distress can be a series of interconnected cracks, later developing into many-sided, and sharp-angled pieces, with the characteristic alligator pattern or chicken wire appearance. This alligator cracking is a major structural distress and normally occurs with rutting.

Severity Levels :
- Low	: An area with fine, longitudinal, parallel, hairline cracking with few connecting cracks. The cracks are not spalled or sealed and pumping is not evident.
- Moderate: An area of interconnected cracks forming a complete pattern or network. The cracks may be lightly spalled or sealed and pumping is not evident.
- High	: An area of moderately or severely spalled interconnected cracks forming a complete pattern. The pieces may move under traffic, the cracks may be sealed, and pumping may be evident. 

![Alligator Crack Severity](https://raw.githubusercontent.com/endurancechallengeindonesia/RDDC2024-ID/main/images/P4%20-%20Alligator%20Crack%20Severity.png?token=GHSAT0AAAAAACR3DZW6ZECJWYV6ZYAQRAO4ZRWG27Q)

**3. Pothole**\
Potholes are depressions on the surface of the pavement that have a small diameter, usually less than 750 mm. Potholes generally have sharp corners and vertical upper wall. If the pothole is formed from a high-severity alligator crack, then the damage is recorded as a pothole, not as a alligator crack or weathering

Severity Levels :
- Low	: Any unsealed crack with a mean width up to 10 mm or a crack with good condition sealant plus an undetermined width.
- Moderate: Any crack width averaging between 10 mm and 75 mm or any crack up to 75 mm and adjacent low severity random cracking.
- High	: Any crack width greater than 75 mm or any crack averaging less than 75 mm plus adjacent moderate to high severity random cracking.

![Pothole Severity](https://raw.githubusercontent.com/endurancechallengeindonesia/RDDC2024-ID/main/images/P5%20-%20Pothole%20Severity.png?token=GHSAT0AAAAAACR3DZW6NNQXQY6DAXDXIY22ZRWG4HA)
![Pothole Severity Classification](https://raw.githubusercontent.com/endurancechallengeindonesia/RDDC2024-ID/main/images/P6%20-%20Pothole%20Severity%20Table.png?token=GHSAT0AAAAAACR3DZW7X6WR6JZOKHXWO6BGZRWHAQA)

# Contributors:
We extend our heartfelt gratitude to the 44 contributors who sourced images from videos captured on Indonesian roads, labeled the data, and cross-validated the annotations. Their collective dedication have been instrumental in creating this dataset.

- Adi Angga
- Ahmad Jundi Hibatullah 
- Aliyyah Nazmi
- Alya Cindy Rahmawati
- Atisya Badhiatunrahma Yusuf 
- Audi Raihana Safira Darwis 
- Aziiz Rahmat Habibie
- Fadhillah Hisyam Al Rasyid
- Farhana Dwi F
- Ghiffary Muhammad Ramadan
- I Made Bagus Ananta Putra
- Indra Wahyu Kurniawan 
- Iqbal Bayu Kurniawan
- Irani Salsabila
- Irfan Qobus Salim
- Isma Dewanti Aprilya
- Iva Nur Fatmawati
- Jeanette Cesilia Toar 
- Jepriadi 
- Joanna Netania
- Kadek Adi Hendrawan
- Kent Gunadharma 
- Lidya Miken Charmelita Siahaan
- Mario Valerian Rante Ta'dung
- Miftahul Chosyi
- Mohammad Dimas Noufal
- Muhamad Ridho Al Isya
- Muhammad Dafa Qaulalhaq Mulyadi
- Muhammad Daffa Farras
- Muhammad Fariq Athar
- Naufal Aditya Hadzi
- Nicolas Akbar
- Owen Rantelino
- Radinal Setya Darmansyah
- Rafly Bani Fadlih 
- Rafly Muzakki Rahman 
- Rio Nugroho
- Robertus Rangga Saputra
- Satrio Agung Wicaksono
- Sepki Bakti Pamungkas
- Shafira Rizhani Laila
- Wahyudin A Paca
- Yoga Firman Syahputra
- Yohanes Bagas Eko Prasetyo

# Usage:
Researchers, developers, and practitioners can leverage our dataset to advance the state-of-the-art in road damage detection algorithms. Whether you're exploring new methodologies or benchmarking existing approaches, our dataset serves as a robust foundation for enhancing road infrastructure management and safety.

# License:
Please refer to the provided license file for details on the permitted usage and redistribution of the dataset.

Start exploring our dataset today and join us in paving the way for safer and more resilient road networks in Indonesia and beyond!
