# 🧠 DeepLearning_MegaThread

Welcome to the official code and experiment hub for the **DeepLearning MegaThread** — a 5-part blog series by the **GDGC ML Team** that dives into the practical side of deep learning with a perfect blend of **theory, code, and good vibes**. 🚀

We’re talking **hands-on implementation**, **clear explanations**, and **models that actually work** — all wrapped into weekly drops designed to make deep learning more accessible, exciting, and deployable.

> 📅 New blog every Friday! (And yes, we’re having a blast writing them.)

## ✨ Blog Highlights

### 🔢 1. **Transfer Learning Fundamentals**  
**Author:** *Anaant Raj*  
Anaant kicked things off with a banger 💥 by walking us through how to **fine-tune MobileNetV2 on CIFAR-10**.  
From loading pre-trained weights to understanding which layers to freeze, this post is a must-read if you’re diving into **transfer learning**.

🔗 [Read the blog](https://medium.com/dsc-vit-bhopal/introducing-transfer-learning-fundamentals-cifar-10-mobilenetv2-fine-tuning-and-beyond-d747f73f216c)  

---

### 🧠 2. **Understanding GPT-2 & the Rise of Transformers**  
**Author:** *Nidhi*  
Nidhi broke down the **GPT-2 architecture** and the entire Transformer revolution with crystal-clear visuals and that golden example:  
> “In ‘The cat sat on the mat,’ the word ‘sat’ pays attention to both ‘cat’ and ‘mat.’” 🤯

She also included runnable code and a clean walkthrough of why decoder-only models like GPT-2 are so powerful.

🔗 [Read the blog](https://medium.com/dsc-vit-bhopal/understanding-gpt-2-the-evolution-of-transformers-in-ai-464d94164baa) 

---

### 🔍 3. **VisionGPT: Tiny Transformer, Mighty Vision!**  
**Author:** *Arihant Bhandari*  
CNNs are great at extracting local features. Transformers are amazing at global reasoning. So... why not both?  
**MobileViT** does just that — blending MobileNet’s efficiency with ViT’s attention mechanism for a hybrid model that punches way above its size.

We experiment with **MobileViT-XXS** under multiple settings using Tiny ImageNet to test how image resolution, pretraining, and architecture affect performance.

🔗 [Read the blog](https://medium.com/dsc-vit-bhopal/visiongpt-mobilevit-tiny-transformer-mighty-vision-b9a7f908d490)

## 📁 What's in This Repo?

All the code, experiments, and notebooks from the series, neatly organized for you to run, tweak, and learn from.

### 📌 VisionGPT Experiments

| Notebook | Description |
|----------|-------------|
| `mobilevit_xxs_scratch_64.ipynb` | Trains MobileViT-XXS from scratch on 64×64 Tiny ImageNet. |
| `mobilevit_xxs_pretrained_64.ipynb` | Fine-tunes pretrained MobileViT-XXS on 64×64 input. |
| `mobilevit_xxs_scratch_96.ipynb` | Trains from scratch on 96×96 resolution images. |
| `mobilevit_xxs_pretrained_96.ipynb` | Fine-tunes pretrained MobileViT-XXS on higher-res input. |

## 💬 Why This Series?

Because let’s face it — deep learning can feel like a black box sometimes.  
This series is our way of turning that box transparent.

- 🤖 From pre-trained models to attention mechanisms  
- 🧠 From “how it works” to “why it matters”  
- 💻 From paper to practice

Whether you're a beginner or a practitioner brushing up on fundamentals, we’ve got something here for you.

## 🙌 Meet the Team

🧠 **Arihant Bhandari**

🧠 **Sahil Garje**

🧠 **Anaant Raj**

🧠 **Nidhi Rohra**

🧠 **Samyak Waghdare**

We're the GDGC ML Team — on a mission to make deep learning more practical, fun, and open to all.

---

## 📬 Contribute / Connect

Spotted a bug, want to contribute, or just want to say hi?  
Open an issue, fork the repo, or comment on the blog posts — we love hearing from fellow learners and builders.

---

Thanks for stopping by. Now go train something cool. 🧠💻🔥