### Project Description

This project aims to estimate periodontal bone loss using panoramic dental images, utilizing Region-based Convolutional Neural Networks (RCNN).

**Image Preprocessing**: The initial step involves enhancing and normalizing panoramic images to improve quality. Techniques such as histogram equalization are applied to ensure consistent input for the RCNN model.

**Feature Extraction and Model Training**: The RCNN model is trained on annotated panoramic images. During training, the RCNN learns to detect and localize regions indicative of bone loss automatically, eliminating the need for manual feature extraction. The model uses a pre-trained backbone for initial feature extraction and is fine-tuned on the dental dataset.

**Model Evaluation**: The performance of the RCNN model is evaluated using metrics such as accuracy, precision, recall, and the area under the ROC curve (AUC-ROC). The evaluation process involves validating the model's ability to correctly identify and localize bone loss regions in new, unseen images.

By leveraging RCNN, this project aims to improve the accuracy and efficiency of periodontal bone loss estimation. The automatic detection and localization capabilities of the RCNN model can significantly aid in the early detection and management of periodontal disease, providing valuable support to dental professionals. This approach enhances diagnostic accuracy and offers a robust solution for analyzing panoramic dental images.
