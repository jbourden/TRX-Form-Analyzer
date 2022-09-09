<h1>TRX Form Analyzer</h1>
<hr>
<h3>About this Project</h3>
<p>This our main course project for Computer Vision.</p>
<p>Using existing CV libraries, we built an app which analyzes the exercise form of someone using TRX Suspension Training cables. The four exercises include bicep curls, chest press, y-row, and w-row.</p>
<p>The TRX Form Analyzer uses the MediaPipe library and OpenCV to place a wireframe on the body. The Pose model from MediaPipe maps landmarks to points of interest on the human body. From these landmarks, we can gather positional information through XYZ coordinates which can then be used to calculate angles of the body. From these angles, we can determine whether an exercise was executed with proper form.</p>

<img width="1280" alt="trx-analyzer-screenshot" src="https://user-images.githubusercontent.com/77255535/189387324-589334aa-1cb9-4ccb-8f20-7e433ddf3e6f.png">





<p>This project was a collaboration between myself and <a href="https://github.com/iqtier">Iqtier U. Ahammad.</a></p>
