# Dental-Diseases-Classification-using-PanoromicImages

### Project Description

This project aims to estimate periodontal bone loss using panoramic dental images, leveraging advanced machine learning techniques. The primary methodologies employed are Support Vector Machines (SVM) and Region-based Convolutional Neural Networks (RCNN).

**Image Preprocessing**: The initial step involves enhancing and normalizing panoramic images to improve quality. Techniques like histogram equalization are applied to ensure consistent input for the models.

**Feature Extraction**: For the SVM approach, relevant features are manually extracted from the images. These features typically include measurements such as the distance between the cemento-enamel junction (CEJ) and the alveolar bone crest (ABC). On the other hand, RCNN automates feature extraction, learning directly from the image data.

**Model Training**: The SVM model is trained on the extracted feature vectors, with hyperparameter tuning performed via cross-validation to optimize performance. The RCNN model is trained on annotated images, where it learns to detect and localize regions indicative of bone loss.

**Evaluation**: Both models are evaluated using metrics such as accuracy, precision, recall, and the area under the ROC curve (AUC-ROC). Cross-validation is employed to ensure the models generalize well to unseen data.

This dual approach allows for robust estimation of periodontal bone loss, providing both classification and localization capabilities. By combining traditional feature-based methods with deep learning techniques, the project aims to improve diagnostic accuracy and aid in the early detection and management of periodontal disease.


