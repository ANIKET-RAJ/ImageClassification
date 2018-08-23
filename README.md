# ImageClassification
VGG16-Python-scikit-learn-SVM-opencv   
This project is an attempt to classify the hematoxylin and eosin stained breast images into different classes. The dataset is composed of Hematoxylin and eosin stained breast histology microscopy images. The annotation was performed by two medical experts and images where there was disagreement were discarded. The dataset contains a total of 400 microscopy images, distributed as follows:   
• Normal: 100  
• Benign: 100  
• In situ carcinoma: 100  
• Invasive carcinoma: 100  
Earlier features were hand engineered which was done by experts having field knowledge which was later replaced by convolutional neural networks. We have tried to combine both of them so, a method of feature extraction using pretrained model augmented with some hand-picked features is used to classify the images into four classes. Further, an attempt to classify images into three classes has been made where the noncancerous classes are merged together as the cancerous images are of more significance to the pathologists. Machine-aided classification would reduce the cost significantly as manual inspection requires well-trained personnel. The number of features is kept small to reduce the computation time. The features extracted are used to train an SVM classifier with the linear kernel. Accuracies of 65% for four class and 74% for three class are achieved.
