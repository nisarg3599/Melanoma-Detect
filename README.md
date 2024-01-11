<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

  <h1>Melanoma Detection Project</h1>

  <p>This project focuses on building a custom Convolutional Neural Network (CNN) for the accurate detection of melanoma, a type of cancer that can be fatal if not diagnosed early. The dataset used in this project contains images of various oncological diseases, and the goal is to classify them into nine different classes, including melanoma.</p>

  <h2>Project Pipeline</h2>

  <ol>
    <li><strong>Data Reading/Data Understanding:</strong> Define the path for train and test images.</li>
    <li><strong>Dataset Creation:</strong> Create train & validation datasets with a batch size of 32, resizing images to 180x180 pixels.</li>
    <li><strong>Dataset Visualization:</strong> Code to visualize one instance of all nine classes in the dataset.</li>
    <li><strong>Model Building & Training:</strong>
      <ul>
        <li>Create a CNN model, rescale images to normalize pixel values between (0,1).</li>
        <li>Choose an appropriate optimizer and loss function for model training.</li>
        <li>Train the model for ~20 epochs and analyze for overfitting or underfitting.</li>
      </ul>
    </li>
    <li><strong>Data Augmentation:</strong> Implement a data augmentation strategy to resolve underfitting/overfitting issues.</li>
    <li><strong>Model Building & Training on Augmented Data:</strong>
      <ul>
        <li>Create a CNN model with rescaled images.</li>
        <li>Choose optimizer and loss function.</li>
        <li>Train the model for ~20 epochs and check for improvements.</li>
      </ul>
    </li>
    <li><strong>Class Distribution:</strong>
      <ul>
        <li>Examine the current class distribution in the training dataset.</li>
        <li>Identify the class with the least number of samples.</li>
        <li>Determine which classes dominate the data in terms of proportionate number of samples.</li>
      </ul>
    </li>
    <li><strong>Handling Class Imbalances:</strong> Rectify class imbalances using Augmentor library.</li>
    <li><strong>Model Building & Training on Rectified Data:</strong>
      <ul>
        <li>Create a CNN model with rescaled images.</li>
        <li>Choose optimizer and loss function.</li>
        <li>Train the model for ~30 epochs and assess improvements.</li>
      </ul>
    </li>
  </ol>

  <h2>Notebook Link:</h2>
  <p>Insert the link to your Google Colab notebook or provide the path to your Jupyter notebook on GitHub.</p>

  <h2>Instructions:</h2>
  <p>Follow the steps in the notebook to understand the project flow, model building, training, and evaluation. Make sure to execute each cell in order.</p>

  <h2>Contributing:</h2>
  <p>If you'd like to contribute or have suggestions, feel free to open an issue or submit a pull request.</p>

  <h2>License:</h2>
  <p>This project is licensed under the [Your License].</p>

</body>
</html>
