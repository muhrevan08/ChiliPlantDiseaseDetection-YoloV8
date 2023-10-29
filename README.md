<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>
  <h1>YOLOv8 - Chili Disease Detection App</h1>
  
  <div class="section">
    <h2 class="section-title">Description</h2>
    <p>
      This website can carry out disease detection on chili plants in the categories: Healthy, Curly Leaves, Leaf Spots, Yellow Leaves.
    </p>
  </div>
  
  <div class="section">
    <h2 class="section-title">Installation</h2>
    <div class="code-block">
      <code>$ git clone https://github.com/{your-repo.git}</code><br>
      <code>$ cd {your-repo}</code><br>
      <code>$ pip install -r requirements.txt</code>
    </div>
  </div>
  
  <div class="section">
    <h2 class="section-title">Usage</h2>
    <p>Follow the steps below to run the application:</p>
    <ol>
      <li>Make sure you have Python and pip installed.</li>
      <li>Install the required dependencies by running the following command in the project directory:</li>
      <div class="code-block">
        <code>$ pip install -r requirements.txt</code>
      </div>
      <li>Run the application using the following command:</li>
      <div class="code-block">
        <code>$ python main.py</code>
      </div>
      <li>Open your web browser and visit <code>http://localhost:5000</code>.</li>
      <li>Upload an image (.jpg) or video (.mp4) file to object detection.</li>
      <li>View the object detection results on the web page.</li>
    </ol>
  </div>

<li><strong>static/web_images:</strong> Contains static images used in the web application.</li>
<li><strong>yolo_assets:</strong> Contains the YOLOv8 model, class names file, and output directory for detections.</li>
<li><strong>README.md:</strong> The README file with instructions and information about the project.</li>
<li><strong>requirements.txt:</strong> Lists the required Python packages and their versions.</li>
</ul>
</div>

<div class="section">
<h2 class="section-title">Dependencies</h2>
<p>The project relies on the following dependencies:</p>
<div class="code-block">
<code>ultralytics==8.0.180</code><br>
<code>opencv-python==4.7.0.72</code><br>
<code>Flask==2.3.2</code><br>
<code>Flask-WTF==1.1.1</code><br>
</div>

</div>
</div>

</body>

</html>
