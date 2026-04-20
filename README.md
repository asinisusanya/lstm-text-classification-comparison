# LSTM Text Classification – Model Comparison

This project presents a comparative analysis of multiple LSTM-based architectures for text classification on an imbalanced dataset.

## 🚀 Models Implemented

- Single-Layer LSTM
- Two-Layer LSTM
- Single-Layer LSTM with Attention
- Two-Layer LSTM with Attention
- Bi-LSTM
- Bi-LSTM with Attention

## 📊 Key Results

| Model | Accuracy |
|------|---------|
| Single LSTM | 70.97% |
| Two-Layer LSTM | 70.97% |
| LSTM + Attention | 85.89% |
| Two-Layer + Attention | **86.1%** |
| Bi-LSTM | 85.44% |
| Bi-LSTM + Attention | 85.74% |

## 🔍 Key Findings

- Standard LSTM fails on imbalanced data (predicts majority class)
- Attention significantly improves performance
- Best model: Two-Layer LSTM with Attention

## 🧠 Insights

This project demonstrates how attention mechanisms improve feature learning and minority class detection in sequence models.

## 📌 Technologies Used

- Python
- PyTorch
- Scikit-learn
- Pandas

