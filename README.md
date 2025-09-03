 Pest_Classification_byUsing_CNN

A deep learning-based pest classification system using Convolutional Neural Networks (CNN) to identify harmful and beneficial pests in crops. This project aims to enhance sustainable agriculture by improving pest management and reducing crop damage.

1. Features
- CNN-based classifier for crop pests
- Works with common agricultural pest images
- Aims to reduce crop loss and improve decisions

2. Project Structure
Pest_Classification_byUsing_CNN/
├── src/
│ ├── train.py # Training script
│ ├── predict.py # Inference script
│ └── utils.py # Helper functions
├── models/ # Saved models (gitignored)
├── data/ # Dataset folder (gitignored)
├── requirements.txt # Python dependencies
└── README.md
3. Dataset
This project uses the IP102 pest dataset  
Download it here: [[IP102 Dataset on Kaggle](https://www.kaggle.com/datasets/parserpixy/ip102-dataset)

4. After downloading, place it inside `data/` folder like this:
data/
  train/
    class_1/
    class_2/
  val/
    class_1/
    class_2/
5.  Installation
Clone the repository:
```bash
git clone https://github.com/swethabogolu/Pest_Classification_byUsing_CNN.git
cd Pest_Classification_byUsing_CNN
6. pip install -r requirements.txt

7. Results
```markdown
 Results
- Accuracy: 90%
- Loss: 0.35
8. Future Work

Improve accuracy with transfer learning (VGG16, Inception-ResNet)

Deploy model as a web app using Flask/Streamlit



