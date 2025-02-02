<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
<div class="container">
    <h1>🧠 Tumor Detection on CT & MRI using CNN</h1>
    <p><strong>🚀 A deep learning-based approach for detecting brain tumors in CT and MRI scans using a Convolutional Neural Network (CNN).</strong></p>
    <h2>📊 Dataset Information</h2>
    <p>
        The dataset used for this project is publicly available on <a href="https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri" target="_blank">Kaggle</a>.
        It contains high-quality CT and MRI scans labeled as <strong>Healthy</strong> or <strong>Tumor</strong>.
    </p>
    <ul>
        <li>📂 <strong>Source:</strong> <a href="https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri" target="_blank">Kaggle Brain Tumor Multimodal Dataset</a>.</li>
        <li>🖼️ <strong>Image Types:</strong> CT scans & MRI scans.</li>
        <li>🔖 <strong>Labels:</strong> Two categories - Healthy & Tumor.</li>
        <li>📏 <strong>Data Split:</strong> 80% Training, 10% Validation, 10% Test.</li>
    </ul>
    <h2>🧠 CNN Architecture</h2>
    <ul>
        <li>🔹 <strong>Conv Blocks:</strong> 4 convolutional layers with increasing filters (64 → 128 → 256 → 512).</li>
        <li>🌀 <strong>Batch Normalization:</strong> Applied after each convolution to improve training stability.</li>
        <li>🔹 <strong>Activation Function:</strong> ReLU6 for better precision.</li>
        <li>🛑 <strong>Dropout:</strong> Applied at each stage (20%-50%) to reduce overfitting.</li>
        <li>📏 <strong>Pooling:</strong> Max-pooling layers after each convolutional block.</li>
        <li>📊 <strong>Final Classifier:</strong> Fully connected layers with softmax for binary classification.</li>
    </ul>
    <h2>⚙️ Image Preprocessing</h2>
    <ul>
        <li>🎨 <strong>Grayscale Conversion:</strong> Ensuring uniformity across all images.</li>
        <li>🔍 <strong>Contrast & Brightness Adjustment:</strong> Enhancing image features.</li>
        <li>🌀 <strong>Gaussian Noise Injection:</strong> Simulating real-world noise.</li>
        <li>🔄 <strong>Random Affine Transformations:</strong> Adding slight distortions to improve generalization.</li>
    </ul>
    <h2>📊 Results</h2>
    <div class="result">
        <p>✅ <strong>Final Model Accuracy:</strong> <span class="code">97.30%</span></p>
        <p>🎯 <strong>Precision:</strong> <span class="code">98%</span></p>
        <p>🔬 <strong>Recall:</strong> <span class="code">98%</span></p>
        <p>📉 <strong>Validation Accuracy:</strong> <span class="code">97.66%</span></p>
        <p>🧪 <strong>Train Accuracy:</strong> <span class="code">96.63%</span></p>
    </div>
    <h2>📜 Confusion Matrix</h2>
    <p>Evaluating the classification performance:</p>
    <img src="Confusion Matrix.png" alt="Confusion Matrix" width="400">
    <p>
        Developed as part of a research-based deep learning project. Dataset credits to <a href="https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri" target="_blank">Kaggle dataset by Murtozali Khon</a>.</p>
    <p> Free to use and modify 🎉</p>
</div>
</body>
</html>
