# Project Title
Product Retrieval on E-commerce 2023.1 - Group 18

## Description
This project focuses on improving product retrieval on e-commerce platforms by experimenting with a wide range of different methods including TF-IDF, BM25, bi-encoder, cross-encoder, bi-cross and hybrid models. The dataset used in this project is curated and labeled in Vietnamese, involving both automated and manual annotation methods. The goal is to enhance retrieval accuracy and relevance by leveraging detailed product descriptions.

## Result
| Model | Precision@1 | Precision@5 | Precision@10 | MAP   |
|-------|-------------|-------------|--------------|-------|
| TF-IDF | 30.28       | 20.83       | 16.25        | 25.66 |
| BM25  | 25.56       | 21.39       | 15.83        | 21.50 |
| Hybrid | 32.50      | 22.38       | 15.69        | 38.41 |
| Bi-encoder only | 33.89 | 21.22       | 14.94        | 39.32 |
| Cross-encoder only | 28.61 | 19.61 | 13.03        | 35.08 |
| Bi-cross only | 32.27 | 21.89      | 14.94        | 40.34 |
| Bi-BM25 | 30.55     | 21.11      | 14.94        | 40.44 |

## Getting Started

### Dependencies
- Python 3.8
- PyTorch
- [Sklearn](https://scikit-learn.org/stable/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)

### Installing
Clone the repository: ``git clone https://github.com/viet-data/web_mining_e_commerce.git``

## Authors
- Dao Trong Viet
- Dao Van Tung
- Bui Thanh Tung
- Nguyen Anh Tuan
- Nguyen Phuong Uyen

## Version History
- **0.2**
  - Various bug fixes and optimizations
- **0.1**
  - Initial Release
