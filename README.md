# Deep Learning for Vision Systems

This repository contains projects and exercises from the book "Deep Learning for Vision Systems" by Mohamed Elgendy. The book provides a comprehensive guide to understanding and implementing deep learning algorithms for computer vision applications.

## About the Book

This book aims to bridge the gap in deep learning for computer vision education by providing:

- A comprehensive resource taking readers from basic machine learning to advanced deep learning algorithms
- Both breadth (horizontal coverage) of computer vision topics and depth (vertical understanding) of the underlying mathematics
- Practical projects implementing the concepts discussed
- Intuitive explanations of complex mathematical concepts
- Focus on production-ready neural networks for real computer vision applications

### Target Audience

This book is ideal for:
- Engineers with intermediate Python experience
- Developers with basic machine learning knowledge
- Anyone looking to build production-ready computer vision applications
- Those interested in understanding the mathematics behind deep learning algorithms

### Book Structure

The book is organized into three main parts:

1. **Deep Learning Foundations**
   - Detailed explanation of neural network components
   - Core concepts and definitions
   - Understanding neural networks internals

2. **Object Classification and Detection**
   - Deep learning techniques for classification
   - Object detection implementations
   - Practical projects and applications

3. **Image Generation and Visual Embeddings**
   - Advanced techniques for image generation
   - Visual embedding methods
   - Complex implementation projects

### Technical Requirements

The book's examples use:
- Python
- TensorFlow
- Keras
- OpenCV

GPU access is recommended for chapters 6-10 due to complex network training requirements. Alternatively, cloud environments like Google Colab can be used.

### Resources

- Book Website: [Manning Publications](https://www.manning.com/books/deep-learning-for-vision-systems)
- Source Code: [GitHub Repository](https://github.com/moelgendy/deep_learning_for_vision_systems)
- Discussion Forum: [Manning liveBook](https://livebook.manning.com/#!/book/deep-learning-for-vision-systems/discussion)



## Package's installation
The required packages are listed in the *requirements.txt* file.
- Create the virtual environment: `python3.10 -m venv venv`
- Activate the virtual environment: `source venv/bin/activate`
- Upgrade pip: `python3.10 -m pip install --upgrade pip`
- Install packages from *requirements.txt*: `pip install -r requirements.txt`
- Uninstall all packages: `pip freeze | xargs pip uninstall -y`
- Deactivate the virtual environment: `deactivate`
- Delete the virtual environment (optional): `rm -rf venv`
