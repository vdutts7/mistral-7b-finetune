<div align="center">

<img src="https://res.cloudinary.com/dnz16usmk/image/upload/v1725843708/mistral-ai.png" alt="logo" width="100" height="40" />

  <h1 align="center">
        Mistral 7B Finetune
    </h1>
    <p align="center"> 
        <i><b>Fine-tuning Mistral 7B model using the UltraChat dataset</b></i>
        <br /> 
    </p>

[![Github][github]][github-url]


 </div>

<br/>

## Table of Contents

  <ol>
    <a href="#about">📝 About</a><br/>
    <a href="#dataset">📊 Dataset</a><br/>
    <a href="#how-to-run">💻 How to Run</a><br/>
    <a href="#tools-used">🔧 Tools Used</a>
        <ul>
        </ul>
    <a href="#contact">👤 Contact</a>
  </ol>

<br/>

## 📝About

This project demonstrates the process of fine-tuning the Mistral 7B language model using the UltraChat dataset. It covers the entire pipeline from downloading the model to inference with the fine-tuned model.

## 📊Dataset

The project uses the UltraChat dataset from Hugging Face:
- Dataset: [HuggingFaceH4/ultrachat_200k](https://huggingface.co/datasets/HuggingFaceH4/ultrachat_200k)
- Specific file used: `test_gen-00000-of-00001-3d4cd8309148a71f.parquet`

## 💻 How to Run

1. **Download the Model**
   - Clone the Mistral finetune repository
   - Install requirements
   - Download the Mistral 7B model

2. **Prepare the Dataset**
   - Download and split the UltraChat dataset
   - Reformat the data for training

3. **Configure Training**
   - Set up the training configuration in a YAML file

4. **Start Training**
   - Run the training script

5. **Inference**
   - Load the fine-tuned model and run inference

For detailed steps and code, please refer to the Jupyter notebook in this repository.

## 🔧Tools Used

<img
  src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"
  alt="Python"
/>
<img
  src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"
  alt="PyTorch"
/>
<img
  src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"
  alt="Jupyter"
/>
<img
  src="https://img.shields.io/badge/Hugging Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black"
  alt="Hugging Face"
/>

## 👤Contact

[![Email][email]][email-url]
[![Twitter][twitter]][twitter-url]

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[email]: https://img.shields.io/badge/Email-FFCA28?style=for-the-badge&logo=Gmail&logoColor=00bbff&color=black
[email-url]: mailto:me@vd7.io
[github]: https://img.shields.io/badge/Github-2496ED?style=for-the-badge&logo=github&logoColor=white&color=black
[github-url]: https://github.com/vdutts7/mistral-7b-finetune
[twitter]: https://img.shields.io/badge/Twitter-FFCA28?style=for-the-badge&logo=Twitter&logoColor=00bbff&color=black
[twitter-url]: https://twitter.com/vdutts7
