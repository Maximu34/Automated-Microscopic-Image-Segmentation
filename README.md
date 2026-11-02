# Automated Microscopic Image Segmentation

**Automated Microscopic Image Segmentation using U-Net and Watershed**

A deep learning and image processing project for automatic segmentation of cell nuclei from microscopic images, biological feature extraction, and visual comparison of segmentation methods.

## 👨‍💻 Project Team

| Student Name | Register Number |
|---|---|
| Jayanithish B | 23MIA1057 |
| Jainth Vaishnav B L | 23MIA1022 |

**Academic Year:** 2026–2027

## 📌 About the Project

Microscopic image segmentation is an important task in biological image analysis. Manually identifying and separating cell nuclei can take considerable time and effort.

This project develops an automated system that processes microscopic images and identifies cell nuclei using two approaches:

1. **Classical Image Processing:** Adaptive Thresholding and Marker-Based Watershed.
2. **Deep Learning:** U-Net segmentation model.

The system also extracts biological features and provides a web-based dashboard to visualize and compare the results.

## 🎯 Project Objectives

- Automatically segment cell nuclei from microscopic images.
- Apply image preprocessing to improve image quality.
- Implement classical and deep learning segmentation methods.
- Compare U-Net and Watershed segmentation results.
- Extract biological measurements from segmented objects.
- Evaluate segmentation performance using standard metrics.
- Provide an easy-to-use web dashboard for visualization and analysis.

## 🧬 Dataset

**2018 Data Science Bowl (DSB2018) – BBBC038 Stage 1**

The dataset contains microscopic images of cell nuclei and corresponding ground-truth segmentation masks.

- [Kaggle Dataset](https://www.kaggle.com/c/data-science-bowl-2018/data)
- [Broad Bioimage Benchmark Collection – BBBC038](https://bbbc.broadinstitute.org/BBBC038)

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| OpenCV | Image processing |
| NumPy | Numerical operations |
| Pandas | Data handling |
| Matplotlib | Graphs and visualization |
| PyTorch | Deep learning |
| U-Net | Cell nuclei segmentation |
| Java | Biological feature calculations |
| HTML, CSS, JavaScript | Dashboard interface |

## ⚙️ Algorithms Used

### 1. Image Preprocessing
- Image resizing
- Normalization
- CLAHE (Contrast Limited Adaptive Histogram Equalization)

### 2. Classical Segmentation
- Adaptive Thresholding
- Distance Transform
- Marker-Based Watershed

### 3. Deep Learning Segmentation
- U-Net architecture
- Convolutional Neural Network
- Binary Cross-Entropy Loss
- Dice Loss

### 4. Postprocessing
- Morphological operations
- Connected Component Analysis
- Watershed-based separation

## 📊 Biological Feature Extraction

The system extracts measurements from segmented cell nuclei:

- Area
- Perimeter
- Centroid
- Eccentricity
- Solidity

## 🚀 Main Features

- Upload microscopic images through a web dashboard.
- Generate segmentation masks.
- View original images, masks and overlays.
- Compare classical and U-Net segmentation.
- Visualize confidence maps where supported.
- View biological feature measurements in tables.
- Analyze segmentation errors.
- Perform ablation comparisons where implemented.
- Support tiling and Test-Time Augmentation (TTA).
- Explore video-based cell tracking and counting where implemented.
- Export analysis results.

## 🔄 System Workflow

```text
Microscopic Image Input
          |
          v
   Image Preprocessing
          |
          v
   Segmentation Methods
      /          \
     v            v
 Classical       U-Net
 Watershed       Model
      \          /
       v        v
      Postprocessing
            |
            v
   Biological Feature
       Extraction
            |
            v
    Performance Evaluation
            |
            v
       Web Dashboard
            |
            v
     Visual Results
```

## 📁 Project Structure

```text
Automated-Microscopic-Image-Segmentation/
│
├── dashboard/
│   ├── server.py
│   └── static/
│       └── index.html
│
├── python/
│   ├── requirements.txt
│   └── seg/
│       └── Segmentation modules
│
├── java/
│   ├── pom.xml
│   └── Java source files
│
├── outputs/
│   └── Model and result files (if included)
│
├── run_all.py
├── README.md
└── START_HERE.md
```

*The exact files and folders may vary depending on the version uploaded to GitHub.*

## 💻 Installation and Execution

### Requirements

- Python 3.10–3.12
- JDK 17 or above
- pip
- Modern web browser

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Automated-Microscopic-Image-Segmentation.git
```

### Step 2: Open the Project

```bash
cd Automated-Microscopic-Image-Segmentation
```

### Step 3: Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```bash
.venv\Scripts\activate
```

### Step 4: Install Dependencies

```bash
pip install -r python/requirements.txt
```

### Step 5: Start the Dashboard

```bash
python dashboard/server.py
```

Open the following address in your browser:

```text
http://localhost:8000
```

**Note:** The trained U-Net model and dataset must be available in the expected project folders. Follow `START_HERE.md` for any additional setup instructions.

## 📈 Evaluation Metrics

The project supports standard segmentation evaluation metrics:

- Dice Coefficient
- Intersection over Union (IoU)
- Precision
- Recall
- F1-Score

Actual performance values should be taken from the generated project results.

## 🌟 Applications

- Biological image analysis
- Cell nuclei detection
- Microscopic image processing
- Biomedical research
- Automated biological feature extraction

## 🔮 Future Enhancements

- Improve segmentation accuracy with additional training data.
- Support more microscopic image types.
- Improve cell tracking across video frames.
- Optimize processing speed for large images.
- Extend biological feature analysis.

## 👥 Project Contributors

**Jayanithish B**  
**Jainth Vaishnav B L**

Developed as a Fourth Year Academic Project, 2026–2027.

## 📄 License

This project is developed for academic and educational purposes. Add a suitable open-source license if you intend to permit reuse and redistribution.

