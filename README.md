- 👋 Hi, I’m @MaureenNyarko
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
MaureenNyarko/MaureenNyarko is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html>

<head>
  <title>PollutAI: Air Quality Image Classification+X</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="shared/tfjs-examples.css" />
</head>

<body style="background-color: #f0f5ff; font-family: Arial, sans-serif;">
  <div class="tfjs-example-container" style="max-width: 800px; margin: 0 auto; padding: 20px; background-color: #ffffff;">
    <section class='title-area'>
      <h1 style="text-align: center; color: #0099cc;">Fruits and Veggies Classification</h1>
    </section>

    <section>
      <img src="dataset.jpg" style="width: 50%; display: block; margin: 0 auto;">
      <p class='section-head' style="font-weight: bold; margin-top: 20px; color: #0099cc;">Description</p>
      <p>
        We classify 9 categories of fruits and veggies.
      </p>
    </section>

    <section>
      <p class='section-head' style="font-weight: bold; color: #0099cc;">Status</p>
      <div id="status" style="font-size: 16px;"></div>
    </section>

    <section>
      <p class='section-head' style="font-weight: bold; color: #0099cc;">Model Output</p>

      <div id="file-container" style="margin-bottom: 20px;">
        Upload an image: <input type="file" id="files" name="files[]" multiple />
      </div>

      <div id="predictions" style="font-size: 18px;"></div>

      <img style="display: none;" id="cat" src="ai4all.jpg" width="224" height="224" />
    </section>

    <script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@1.5.2"></script>
    <script src="index.js"></script>
  </div>
</body>

</html>
