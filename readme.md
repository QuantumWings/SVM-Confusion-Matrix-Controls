<h1>3D SVM confusion matrix visualization</h1>
<h2>Introduction</h2>
<p>This project is an interactive 3D Support Vector Machine (SVM) confusion matrix visualization tool. It is designed to help users understand the performance of SVM classifiers and visually demonstrate how the various components of the confusion matrix affect different performance metrics. This tool combines machine learning, data visualization and web interaction technology to provide learners, educators and researchers with a powerful platform to explore how SVM works. </p>

Check out the demo [here](https://quantumwings.github.io/SVM-Confusion-Matrix-Controls/).

<h2>Main functions</h2>
<ol>
<li>3D scatter plot showing SVM classification results</li>
<li>Interactive confusion matrix adjustment (true positive, true negative, false positive, false negative)</li>
<li>Real-time calculation and display of various performance indicators (accuracy, precision, recall, etc.)</li>
<li>Visualizing and hiding decision boundaries</li>
<li>Supports vector highlighting</li>
<li>Custom category colors</li>
<li>3D graphics rotation animation</li>
<li>Dynamic data point generation</li>
<li>Supports vector resizing and breathing animation effects</li>
</ol>
<h2>Installation and Setup Guide</h2>
<h3>Environmental requirements</h3>
<ul>
<li>Modern web browsers (such as Chrome, Firefox, Safari, etc.)</li>
<li>Network connection (used to load external JavaScript libraries)</li>
</ul>
<h3>How to use</h3>
<ol>
<li>Clone the project file locally:
 <code>git clone https://github.com/your-username/3d-svm-confusion-matrix.git</code></li>
<li>Open the <code>index.html</code> file in your browser. </li>
</ol>
<h2>Instructions for use</h2>
<h3>Operation steps</h3>
<ol>
<li>Adjust confusion matrix parameters:</li>
<li>Use the sliders to change the values ​​for True Positives (TP), True Negatives (TN), False Positives (FP), and False Negatives (FN). </li>
<li>Select performance metrics:</li>
<li>Select the performance metrics to display from the drop-down menu. </li>
<li>Switch decision boundary:</li>
<li>Use the switch to show or hide the decision boundary plane. </li>
<li>Custom color:</li>
<li>Use the color picker to change the colors of both categories. </li>
<li>Control animation:</li>
<li>Click "Animate Rotation" to start the rotation animation of 3D graphics. </li>
<li>Click "Stop Animation" to stop the rotation. </li>
<li>Regenerate data:</li>
<li>Enter the desired number of data points and click "Regenerate Data". </li>
<li>Adjust support vector display:</li>
<li>Check "Highlight Support Vectors" to highlight support vectors. </li>
<li>Use the slider to adjust the size of the supported vectors. </li>
</ol>
<h3>Example</h3>
<ol>
<li>Set TP=700, TN=600, FP=150, FN=50</li>
<li>Select "F1 Score" as the performance metric to display</li>
<li>Turn on decision boundary display</li>
<li>Set the color of Class 1 to blue and the color of Class -1 to red</li>
<li>Start rotation animation</li>
<li>Set the number of data points to 2000 and regenerate the data</li>
<li>Turn on support for vector highlighting and adjust its size to 12</li>
</ol>
<p>Observe the changes in 3D graphics, especially the position of the decision boundary and the distribution of support vectors. Note the change in F1 score. </p>
<h2>Project structure</h2>
<ul>
<li>index.html: Contains all necessary HTML, CSS, and JavaScript code for an interactive interface to build and display SVM confusion matrices. </li>
</ul>
<p>Main components:
1. ConfusionMatrixModel: handles data generation and indicator calculations
2. ConfusionMatrixView: Responsible for UI elements and graphics drawing
3. ConfusionMatrixController: Coordinates models and views and processes user input</p>
<h2>Contribution Guidelines</h2>
<p>If you would like to contribute to this project, please follow these steps:
1. Fork this repository and clone it to the local environment.
2. Create a new branch for development (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push the changes to your branch (git push origin feature-branch).
5. Submit a Pull Request. </p>
<h2>Authorization information</h2>
<p>This project is licensed under the terms of the <a href="https://opensource.org/licenses/MIT">MIT</a> license. </p>
<h2>Contact information</h2>
<p>If you have any questions or suggestions, please contact the project maintainer: `quantumwingslab@gmail.com`</p>
<h2>Additional information</h2>
<ul>
<li>This project uses Plotly.js for 3D data visualization</li>
<li>Math.js for complex mathematical calculations</li>
</ul>
