<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

</head>
<body>

  <h1>🎨 Stable Diffusion - Text to Image Generator</h1>

  <p>
    This project demonstrates how to generate realistic images from text prompts using the <strong>Stable Diffusion</strong> model.
    It leverages pre-trained models from <a href="https://huggingface.co/CompVis/stable-diffusion" target="_blank">Hugging Face 🤗 Diffusers</a> library to perform state-of-the-art text-to-image synthesis.
  </p>

  <hr>

  <h2>🚀 Features</h2>
  <ul>
    <li>Generate high-quality images from natural language descriptions</li>
    <li>Uses pre-trained Stable Diffusion model from Hugging Face</li>
    <li>No need to train your own model</li>
    <li>Quick setup and easy inference</li>
  </ul>

  <hr>

  <h2>🛠️ Installation</h2>
  <p>Install the required dependencies using pip:</p>
  <pre><code>pip install diffusers transformers scipy safetensors</code></pre>

  <hr>

  <h2>📌 How to Use</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/kunalmahadule/Stable-Diffusion-Model.git</code></pre>
    </li>
    <li>Navigate into the project directory:
      <pre><code>cd Stable-Diffusion-Model</code></pre>
    </li>
    <li>Run the inference script:
      <pre><code>python generate_image.py --prompt "A fantasy landscape with dragons"</code></pre>
    </li>
    <li>The generated image will be saved to the <code>outputs/</code> folder.</li>
  </ol>

  <hr>

  <h2>🖼️ Sample Results</h2>
  <p>Here are a few sample prompts and generated images:</p>
  <ul>
    <li><strong>Prompt:</strong> "The picture of earth at 2035"</li>
    <li><strong>Output:</strong> <img src="Generated_img/The picture of earth at 2035.png" width="300" alt="robot"></li>

  </ul>

  <hr>

  <h2>📚 Resources</h2>
  <ul>
    <li><a href="https://huggingface.co/docs/diffusers/index" target="_blank">🤗 Diffusers Documentation</a></li>
    <li><a href="https://github.com/huggingface/diffusers" target="_blank">Diffusers GitHub Repository</a></li>
    <li><a href="https://stability.ai/" target="_blank">Stability AI</a></li>
  </ul>

  <hr>

  <h2>👨‍💻 Author</h2>
  <p>Made with ❤️ by <strong>Kunal Mahadule</strong></p>
  <p>
    🌐 <a href="https://github.com/kunalmahadule" target="_blank">GitHub Profile</a>
  </p>

  <hr>

  <p>🌟 If you liked this project, consider giving it a star on GitHub!</p>

</body>
</html>
