# CIFAR-10 Image Classification: CNNs vs Transfer Learning
**COMP3420 Assignment 1 - Student ID: 47990805**

## 🚀 Quick Start

### Option 1: Complete Assignment
```python
results = run_complete_assignment()
```

### Option 2: Debug Test First
```python
debug_success = debug_test()  # Quick test
results = run_experiment()     # Full experiment
```

## 📁 Project Structure

```
COMP3420-ASSIGNMENT-1/
├── MQ47990805.ipynb        # Main assignment notebook
├── README.md               # This file
├── .gitignore             # Excludes data files
└── data/                  # CIFAR-10 dataset (auto-downloaded)
```

## 🎯 Assignment Tasks Completed

- ✅ **Task 1**: Data subset preparation (1000 samples per class)
- ✅ **Task 2**: Custom CNN model (4+ conv layers, BatchNorm, Dropout)
- ✅ **Task 3**: MobileNetV2 transfer learning
- ✅ **Task 4**: Modular training function
- ✅ **Task 5**: Model evaluation
- ✅ **Task 6**: Confusion matrices
- ✅ **Task 7**: Training visualization
- ✅ **Task 8**: Performance analysis
- ✅ **Task 9**: Misclassification analysis
- ✅ **Task 10**: Efficiency analysis

## 🔧 Technical Features

### Models
- **Custom CNN**: 4-block architecture with BatchNorm and Dropout
- **MobileNetV2**: Pretrained ImageNet weights with custom classifier

### Data Processing
- Balanced subset: 1000 samples per class
- Data augmentation: Random horizontal flip, rotation
- Normalization using CIFAR-10 statistics

### Analysis
- Comprehensive performance comparison
- Visual misclassification analysis
- Efficiency metrics (parameters, inference time)
- Training curves and confusion matrices

## 💻 System Requirements

- Python 3.7+
- PyTorch 2.0+
- Dependencies: torchvision, matplotlib, seaborn, scikit-learn, tqdm
- ~2GB disk space for CIFAR-10 dataset
- 4GB+ RAM recommended

## 📊 Expected Results

- **Custom CNN**: ~70-80% test accuracy
- **MobileNetV2**: ~75-85% test accuracy
- Training time: 10-20 minutes per model (CPU)

## 🚨 Important Notes

### Data Handling
- CIFAR-10 dataset downloads automatically (~170MB)
- Data files excluded from Git due to GitHub's 100MB limit
- First run may take 5-10 minutes for dataset download

### Debugging
- Built-in debug test suite for troubleshooting
- Comprehensive error handling throughout
- Progress bars and status updates

## 🎓 Assignment Compliance

This implementation satisfies all COMP3420 assignment requirements:
- Proper dataset preparation and balancing
- Custom CNN with required architectural components
- Transfer learning implementation
- Comprehensive evaluation and analysis
- Professional code structure and documentation

---
*Ready to run - no additional setup required!*
