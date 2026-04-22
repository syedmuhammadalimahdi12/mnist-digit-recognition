# MNIST Handwritten Digit Recognition 🚀

[![Accuracy](https://img.shields.io/badge/Accuracy-99%25-brightgreen.svg)](https://en.wikipedia.org/wiki/MNIST_database)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13%2B-orange.svg)](https://www.tensorflow.org/)

Complete **Google Colab-ready** Convolutional Neural Network (CNN) for recognizing handwritten digits (0-9) using the famous MNIST dataset. Achieves **99%+ accuracy** with custom image testing interface.

## ✨ Features

- **Production-ready CNN** (3 Conv layers + Dropout)
- **99%+ test accuracy** after 50 epochs training
- **Live image upload** testing with confidence scores
- **Professional visualizations** (training curves, predictions, bar charts)
- **Model export** (.h5 format for deployment)
- **Colab-optimized** 12-cell notebook workflow

## 📊 Dataset
- **60,000 training images** (28×28 grayscale)
- **10,000 test images**
- **Labels**: Digits 0-9

## 🏗️ Model Architecture 





## 🔮 Custom Image Testing

1. **Draw digit** in Paint (black on white)
2. **Save as PNG/JPG** (any size)
3. **Upload via Cell 11/12**
4. **Get instant prediction** with confidence bars

**Pro Tip**: Resize to 28×28px, grayscale for best results.

## 📦 Deployment Options

- **Flask/FastAPI API** (add 10 lines)
- **Streamlit web app** (15 lines)
- **TensorFlow Lite** (mobile)
- **ONNX export** (other frameworks)

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| `ModuleNotFoundError` | `pip install -r requirements.txt` |
| Low accuracy | Train 50 epochs (Cell 5) |
| Image fails | Grayscale, 28×28px, white bg |
| Colab timeout | Use GPU runtime |

## 📚 References

- [MNIST Database](https://en.wikipedia.org/wiki/MNIST_database)
- [TensorFlow MNIST Tutorial](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data#define_the_model_and_metrics)
- [CNN for Digit Recognition](https://machinelearningmastery.com/handwritten-digit-recognition-using-convolutional-neural-networks-python-keras/)

## 🤝 Contributing

1. Fork repository
2. Create feature branch
3. Submit PR with tests

## 📄 License

MIT License - Use freely for any purpose.

---

**Built with ❤️ for machine learning enthusiasts**  
*Achieved 99%+ accuracy on the classic MNIST benchmark*