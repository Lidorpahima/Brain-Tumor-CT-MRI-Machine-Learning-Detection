<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
    <div class="container">
        <h1>🧠 Brain Tumor Detection using ResNet 🩺</h1>
        <p>
            This project utilizes cutting-edge AI to analyze MRI and CT scan images, distinguishing between 
            <b>Healthy</b> and <b>Tumor</b> categories. With an incredible <b>98.5% accuracy</b> on test data, 
            this model sets a new benchmark for brain tumor detection. 🚀
        </p>
        <h2>🌟 Features</h2>
        <ul>
            <li>🔍 <b>Multi-modal support</b> for MRI and CT scans.</li>
            <li>🧪 <b>98.5% Test Accuracy</b>, ensuring robustness and reliability.</li>
            <li>🛠️ <b>Preprocessing pipeline:</b> resizing, grayscale conversion, and contrast adjustments.</li>
            <li>🧠 Built on <b>ResNet18</b>, fine-tuned for binary classification.</li>
        </ul>
        <h2>📂 Dataset</h2>
        <p>The dataset includes categorized MRI and CT scans:</p>
        <ul>
            <li><b>Tumor:</b> 🟠 Scans with brain tumors.</li>
            <li><b>Healthy:</b> 🟢 Scans without any abnormalities.</li>
        </ul>
        <p>📥 Download the dataset from <a href="https://www.kaggle.com/datasets/murtozalikhon/brain-tumor-multimodal-image-ct-and-mri">Kaggle</a>.</p>
        <h2>🚀 Quick Start Guide</h2>
        <h3>Clone the Repository</h3>
        <pre>
git clone https://github.com/your_username/brain-tumor-detection.git
cd brain-tumor-detection
        </pre>
        <h3>Download and Place the Dataset</h3>
        <p>Extract the dataset into a folder named <code>Dataset</code>.</p>
        <h3>Install Dependencies</h3>
        <pre>
pip install -r requirements.txt
        </pre>
        <h3>Run the Notebook</h3>
        <pre>
jupyter notebook Brain_Tumor_Detection.ipynb
        </pre>
        <p>Follow the steps in the notebook to train and evaluate the model.</p>
        <h2>🏗️ Model Architecture</h2>
        <p>Built on <b>ResNet18</b>, the model:</p>
        <ul>
            <li>Adapts for grayscale image input.</li>
            <li>Outputs probabilities for two classes: <b>Tumor</b> 🟠 and <b>Healthy</b> 🟢.</li>
        </ul>
        <h2>📊 Results</h2>
        <ul>
            <li><b>Validation Accuracy:</b> 99% ✅</li>
            <li><b>Test Accuracy:</b> 98.5% ✅</li>
        </ul>
        <p>These metrics showcase the model's exceptional generalization and performance on unseen data.</p>
        <h2>📈 Visualizations</h2>
        <p>The notebook provides:</p>
        <ul>
            <li>📉 <b>Training/Validation Loss and Accuracy Graphs</b></li>
            <li>🔢 <b>Confusion Matrix</b> for test results.</li>
            <li>🎯 <b>Sample Predictions</b> (both correct and incorrect classifications).</li>
        </ul>
        <h2>🤝 Contributing</h2>
        <p>We welcome contributions! To get started:</p>
        <ol>
            <li>Fork this repository 🍴</li>
            <li>Create a new branch for your feature/bug fix 🌿</li>
            <li>Submit a pull request 📥</li>
        </ol>
        <p><b>Together, we can make a difference in brain health! 💪</b></p>
    </div>
</body>
</html>
