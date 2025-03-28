Description
We are pleased to cordially invite university students, who consider Data Science and related fields their careers, to attend the 4th International Competition in Data Science & Artificial Intelligence, organized by The International Society of Data Scientists (also called World Championship 2023).
Students graduated within 5 years are eligible to attend. Each team can optionally have an advisor, who may be a professor or a data science professional. 
The competition is to create a playground for young Data Scientists to grow skills, knowledge, experience, and collaboration for their career path. 
The competition committee includes professors and industry leaders around the world.

This year we introduce the Embryo classification challenge using on microscopic images by Hung Vuong Hospital. 
This is a remarkable opportunity to delve into the world of reproductive science and contribute to improving the accuracy of embryo quality assessment using cutting-edge deep learning techniques.

Registration: Before joining this Computer Vision track, please make sure your team is registered via the form below. 
This help us contact you with any updates or if your team is one of the winning teams.
https://docs.google.com/forms/d/1UXAJFtwArWofrwk3_1JlE-NsedAPJXPlZz-qLJay1PI

The Challenge: Embryo quality assessment is a critical aspect of assisted reproductive technology, aiding fertility specialists in selecting the most viable embryos for implantation. However, this process is both complex and subjective.
In this competition, you're challenged to create a robust deep learning model capable of classifying embryos as 'good' or 'not good' based on their images at day-3 and day-5 of development.

The Dataset: Provided by Hung Vuong Hospital in Ho Chi Minh City, this dataset offers a unique observation into the early stages of embryo development. 
It comprises images of embryos at two crucial time points, day-3 and day-5. Each image is labeled as either 'good' or 'not good,' reflecting the embryo's potential for successful implantation.

Competition's objective: The competition's objective is to harness the power of deep learning to develop an accurate classification model that can discern between 'good' and 'not good' embryos at both day-3 and day-5 stages. 
By achieving this, you'll help fertility specialists make more informed decisions, enhance the efficiency of assisted reproductive procedures, and ultimately contribute to the joy of prospective parents.

Acknowledgment
We are grateful for your interest in the "Embryo Quality Classification" dataset for your research endeavors. The creation of this dataset is a result of the collaborative efforts between Hung Vuong Hospital, Ho Chi Minh City, and the IC-IP lab Vietnam. 
As you utilize this dataset in your work, we kindly request that you acknowledge and recognize the collaborative contributions made by these institutions.


🏗️ Methodology
1️⃣ Data Preprocessing
Image Enhancement: Denoising, contrast normalization, and augmentation.

Segmentation: Removing background noise and isolating the embryo.

Data Augmentation: Rotation, zooming, flipping to improve model generalization.

2️⃣ Model Selection & Training
Baseline CNN Model: Simple convolutional neural network (CNN) for feature extraction.

Transfer Learning Approaches:

Fine-tuning models like ResNet, EfficientNet, VGG16, and InceptionV3.

Transformer-based Models:

Vision Transformers (ViTs) for improved feature recognition.

3️⃣ Model Evaluation
Performance Metrics Used:

Accuracy, Precision, Recall, F1-score.

Grad-CAM visualizations for model explainability.

📊 Key Findings & Insights
CNNs and Transfer Learning models outperform traditional feature-based approaches.

Grad-CAM visualization helps embryologists understand AI-based predictions.

Dataset augmentation significantly improves model generalization.

🔮 Future Improvements
🚀 To enhance this project, we plan to:

Develop a web-based embryo analysis tool (Flask / FastAPI).

Integrate time-series prediction models for embryo development tracking.

Collaborate with embryologists to fine-tune classification criteria.

🏆 Conclusion
This project demonstrates how deep learning and computer vision can enhance embryo selection in IVF procedures. By combining AI-driven insights with expert knowledge, we aim to improve success rates in fertility treatments.

💡 Want to contribute? Open issues, submit PRs, and help advance medical AI!

⭐️ If you found this project useful, star this repository and explore more!
