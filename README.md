# FFF Infill Pattern Classifier

Infill pattern classification of fused filament fabricated (FFF) components from multimodal data using machine learning techniques.

## Overview

This project develops a machine learning-based system to classify and identify infill patterns in 3D-printed parts manufactured through Fused Filament Fabrication (FFF). By leveraging multimodal data (images, sensor readings, G-code analysis), the classifier can accurately determine infill patterns without destructive testing.

## Team

- **Group Members:** Minan Li, Will Kalahar, Andy Jennings, Dongmin (Ethan) Kang
- **Advisor:** Wenmeng Tian, Ph.D.
- **Course:** Spring 2025 IE-6990: Sensing and Analytics in Smart Manufacturing

## Key Features

- **Multimodal Analysis:** Combines multiple data sources for robust classification
- **Machine Learning Classification:** Implements state-of-the-art ML algorithms for pattern recognition
- **G-code Processing:** Analyzes printer instructions to understand print structure
- **Non-destructive Testing:** Classify patterns without damaging components

## Project Structure

```
FFFInfillPatternClassifier/
├── data/                 # Training and test datasets
├── models/               # Trained machine learning models
├── scripts/              # Python utility scripts and preprocessing
├── notebooks/            # Jupyter notebooks for analysis and visualization
├── gcode/                # G-code files and processing tools
└── README.md             # This file
```

## Technologies & Languages

- **Python** (2.6%): Machine learning pipeline, data processing
- **G-code** (97.1%): 3D printer instruction sets and pattern analysis
- **C++** (0.3%): Performance-critical computations

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ezy-8/FFFInfillPatternClassifier.git
   cd FFFInfillPatternClassifier
   ```

2. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download and extract datasets (if available)

## Usage

### Training a Model
```bash
python scripts/train_model.py --data data/training/ --output models/
```

### Classifying Infill Patterns
```bash
python scripts/classify_pattern.py --image path/to/image.jpg --gcode path/to/file.gcode
```

### Processing G-code Files
```bash
python scripts/process_gcode.py --input file.gcode --analyze
```

## Methodology

### Data Sources
- **Visual Data:** High-resolution images of printed parts
- **Sensor Data:** Temperature, pressure, and motion characteristics during printing
- **G-code Analysis:** Parsing and feature extraction from printer instructions

### Machine Learning Approach

## Results & Performance

## Infill Patterns Supported

## Future Work

- [ ] Expand to additional infill pattern types
- [ ] Real-time classification during printing
- [ ] Integration with IoT sensors
- [ ] Cross-material validation

## References & Relevant Work

For questions or collaboration inquiries, please open an issue or contact the team.

---

**Last Updated:** September 2026
