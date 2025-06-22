StyleGAN2-FashionGen is a deep learning project that focuses on generating and classifying realistic fashion apparel images using a modified StyleGAN2-ADA framework. The goal is to create high-quality, diverse clothing images—specifically topwear and bottomwear—for both men and women, and evaluate them using state-of-the-art CNN architectures.

🔍 Key Features
✅ Image Filtering & Categorization:
Filtered the original fashion dataset to separate images into meaningful categories—topwear and bottomwear—for both men and women.

📁 CSV File Generation with styles.csv:
Created two custom CSV files (men_topwear.csv and women_topwear.csv) using the original styles.csv for efficient dataset handling. Each CSV contains paired data of clothing categories and image paths.

🧠 Image Generation with StyleGAN2-ADA:
Trained StyleGAN2-ADA models to generate new, realistic apparel images based on the curated dataset.

📊 Image Classification with CNNs:
Evaluated generated images using CNN models like VGG16, ResNet50, and MobileNetV2 to assess visual quality and category accuracy.

🗂 Dataset
Kaggle Fashion Product Images (Small):
https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset
