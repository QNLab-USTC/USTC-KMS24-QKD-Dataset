# USTC-QNLAB-KMS24 Dataset  

## Overview
This repository contains an open-source dataset derived from the QKD-PHA1250 device manufactured by QuantumCTek Co., Ltd. The dataset consists of quantum key distribution (QKD) data collected over a 2-hour period for various distances. Specifically, the data covers distances of 10 km, 20 km, 30 km, 40 km, and 50 km.

## Dataset Description
Each data packet in this dataset contains information exchanged during the key generation process between the communicating parties. The structure of each data packet is as follows:

1. **Timestamp (8 bytes)**:
   - Represents the time of interaction.
   - Unit: nanoseconds.

2. **Key Length (2 bytes)**:
   - Indicates the length of the generated key.
   - Unit: bytes.

3. **Binary Quantum Key**:
   - The actual quantum key generated during the communication process.

## Usage
This dataset can be used for research purposes such as analyzing QKD performance, evaluating communication protocols, or exploring post-processing techniques in quantum cryptography. Researchers may find the dataset useful for simulations, algorithm testing, and more.

## Additional Information
- The data is collected under controlled conditions to ensure reliability and reproducibility.
- Please ensure proper attribution when using this dataset in your work.

## Citation
If you use this dataset in your research, please cite it as follows:
```
[Provide citation format or DOI here if available]
```

## License
This dataset is released under the GPL-3.0 license.

## Contact
For further inquiries or technical support, please contact:
- Email: lijian9@ustc.edu.cn
- Website: [Research Group of Quantum Network, USTC](https://qnlab-ustc.com/)