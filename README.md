<h1>Mining Site Detection</h1>

<p>This project aims to develop a technology for detecting mining sites using images from the optical satellite Sentinel-2. Specifically, it involves classifying images that contain mining sites and those that do not.</p>

<h2>Modules</h2>

<ol>
    <li>
        <strong>Preprocessing:</strong>
        <p>A module that reads the provided data, preprocesses it, and outputs the file in a state ready for input to the model.</p>
    </li>
    <li>
        <strong>Training:</strong>
        <p>A module that reads the files created in the preprocessing stage and trains the model. It saves the trained model, features, and weights.</p>
    </li>
    <li>
        <strong>Prediction:</strong>
        <p>Module that reads the test data created in the preprocessing stage and the models created in the learning stage, and outputs the prediction results as a file. It outputs a file to be submitted.</p>
    </li>
</ol>

<h2>Dataset</h2>

<p>The Sentinel-2 image contains information on 12 bands and includes the following bands: 'B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7', 'B8', 'B8A', 'B9', 'B11', 'B12'. The images have been processed to mask clouds for Sentinel-2 images from January 1, 2022, to December 31, 2023, and the median of all images is used as the image for that location.</p>
