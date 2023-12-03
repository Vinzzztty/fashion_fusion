# Fashion Fusion

Unbeknownst to us, human perception heavily relies on appearance. Research published in the British Journal of Psychology found a bias influencing our judgments of someone's personality based on overall impressions. It can be concluded that appearance is crucial to us, making fashion a basic necessity and propelling the fashion industry's rapid growth.

The fashion industry has become a significantly growing sector, contributing a substantial $3 trillion and accounting for 2% of the world's GDP. However, the economic growth is deemed to overlook the adverse environmental impacts, according to the United Nations. The fashion industry is responsible for 8-10% of carbon dioxide emissions and contributes to 35% of microplastic waste. The United Nations emphasizes the importance of achieving Sustainable Development Goals (SDGs) in the fashion industry. To meet these goals, innovation is needed, and machine learning holds the potential to address these issues. Machine learning can optimize the excessive use of clothing, tackling overconsumption, excessive production, and minimizing textile waste.

## Project Overview

Fashion Fusion introduces our latest innovation by harnessing machine learning technology. This web platform empowers individuals to optimize their daily appearance. Through the analysis of users' clothing collections, Fashion Fusion recommends outfits based on clothing types and colors, adapting to changing fashion trends over time.

Beyond enhancing appearance, Fashion Fusion is committed to reducing clothing waste. The platform encourages users to make smarter clothing choices by optimizing existing wardrobe options to minimize overconsumption. With Fashion Fusion, users can express their unique style while maintaining a focus on environmental sustainability."

Over 8,003 images of 28 different classes.

## Link Dataset

-   This dataset available on Kaggle: https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset

**_Please refer to 'dataset' on this link for full data_**  
&nbsp;&nbsp;&nbsp;&nbsp; We've already converted the images into ndarray and save them to **.npz** for ease of use and fast processing. You can refer to the file **'Convert_img_to_ndarray.ipynb"** how we did this conversion. Furthermore, for **shoes category**, before we train/val, we need to do **data augmentation** too because shoes have a direction that they are pointing to, if we didn't do any augmentation when it see the real world images in the different direction, it will have trouble classifying them. We provide some examples of our images data in **'Sample images (Full size)'** folder.  
Here are some examples: <br>
<img src = "./samples_images/1163.jpg" width="150" height="150">
<img src = "./samples_images/1662.jpg" width="150" height="150">
<img src = "./samples_images/1671.jpg" width="150" height="150">
<img src = "./samples_images/1758.jpg" width="150" height="150">
<img src = "./samples_images/1765.jpg" width="150" height="150">
<img src = "./samples_images/2185.jpg" width="150" height="150">
<img src = "./samples_images/3601.jpg" width="150" height="150">
<img src = "./samples_images/5809.jpg" width="150" height="150">
<img src = "./samples_images/6962.jpg" width="150" height="150">
