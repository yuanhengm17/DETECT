# Transformer Models for DETECT: Data-driven Evaluation of Treatments Enabled by Classification Transformers

This repository contains the code and transformer models used in our research paper: "**DETECT: Data-driven Evaluation of Treatments Enabled by Classification Transformers**". These models cover different datasets, including public benchmark datasets and internally simulated data.

## Table of Contents

- [Models](#models)
- [Graphs](#graphs)
- [Datasets](#datasets)
- [Citation](#citation)
- [License](#license)

## Models

This repository contains three transformer-based models:

| Model                | Dataset                                       | Description                                                                                 |
|----------------------|-----------------------------------------------|---------------------------------------------------------------------------------------------|
| `PublicDataIMU`      | IMU-based Human Activity Recognition Dataset | Transformer model trained on a publicly available dataset to evaluate accuracy and robustness. |
| `PublicDataKUHAR`    | KU-HAR: An Open Dataset for Human Activity Recognition | Transformer model trained on a second public dataset to assess model performance and generalizability. |
| `TransformerSIMDATA` | Simulated Dataset                             | Transformer model trained on internally generated data to simulate real patient activities of daily life (ADL) patterns. |

All models are stored in the `models/` folder.

---

## Graphs

This repository also contains the simulated patients' motion data graphs that we displayed in the paper. The graphs and code are available at the `graphs.ipynb` file.

---

## Datasets

### Public Datasets

1. **IMU-based Human Activity Recognition Dataset**  
   - Used for training the `PublicDataIMU` model  
   - Access: [IMU-based Human Activity Recognition Dataset](https://data.mendeley.com/datasets/fcnmmsn857/3)  
   - Citation: Tahir, Yara; Hamarash, Ibrahim Ismael (2025), “IMU-based Human Activity Recognition Dataset”, Mendeley Data, V3, doi: 10.17632/fcnmmsn857.3  

2. **KU-HAR: An Open Dataset for Human Activity Recognition**  
   - Used for training the `PublicDataKUHAR` model  
   - Access: [KU-HAR: An Open Dataset for Human Activity Recognition](https://data.mendeley.com/datasets/45f952y38r/4)  
   - Citation: Nahid, Abdullah-Al; Sikder, Niloy; Rafi, Ibrahim (2021), “KU-HAR: An Open Dataset for  Human Activity Recognition”, Mendeley Data, V5, doi: 10.17632/45f952y38r.5

### Simulated Data

- Collected internally and stored securely in Firebase  
- Used for training the `TransformerSIMDATA` model  
- Neither this dataset nor the real patient dataset that has been delayed due to IRB is publicly available due to privacy restrictions

---

## Citation

If you use this code or datasets in your research, please cite our paper: Coming Soon

And the datasets: 

Tahir, Yara; Hamarash, Ibrahim Ismael (2025), “IMU-based Human Activity Recognition Dataset”, Mendeley Data, V3, doi: 10.17632/fcnmmsn857.3

Nahid, Abdullah-Al; Sikder, Niloy; Rafi, Ibrahim (2021), “KU-HAR: An Open Dataset for  Human Activity Recognition”, Mendeley Data, V5, doi: 10.17632/45f952y38r.5

---

## License

This repository is licensed under the MIT License. See the `LICENSE` file for details.
