<div align= "center">
    <h1> Official repo for ShapeGPT <img src="./assets/images/logo_shapegpt.png" width="35px"></h1>

</div>

<div align="center">
    <h2> <a href="https://shapegpt.github.io/">ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model</a></h2>

<p align="center">
  <a href="https://shapegpt.github.io/">Project Page</a> •
  <a href="https://arxiv.org/abs/2311.17618">Arxiv Paper</a> •
  Demo •
  <a href="#️-faq">FAQ</a> •
  <a href="#-citation">Citation</a>
</p>

</div>

<div align="center">
</div>
<!-- <img src="https://cdn.discordapp.com/attachments/941582479117127680/1111543600879259749/20230526075532.png" width="350px"> -->

## 🏃 Intro ShapeGPT

ShapeGPT is a **unified** and **user-friendly** motion-language model to learn the semantic coupling of two modalities and generate high-quality motions and text descriptions on **multiple motion tasks**.

<details>
    <summary><b>Technical details</b></summary>

Though the advancement of pre-trained large language models unfolds, the exploration of building a unified model for language and other multi-modal data, such as motion, remains challenging and untouched so far. Fortunately, human motion displays a semantic coupling akin to human language, often perceived as a form of body language. By fusing language data with large-scale motion models, motion-language pre-training that can enhance the performance of motion-related tasks becomes feasible. Driven by this insight, we propose MotionGPT, a unified, versatile, and user-friendly motion-language model to handle multiple motion-relevant tasks. Specifically, we employ the discrete vector quantization for human motion and transfer 3D motion into motion tokens, similar to the generation process of word tokens. Building upon this “motion vocabulary”, we perform language modeling on both motion and text in a unified manner, treating human motion as a specific language. Moreover, inspired by prompt learning, we pre-train MotionGPT with a mixture of motion-language data and fine-tune it on prompt-based question-and-answer tasks. Extensive experiments demonstrate that MotionGPT achieves state-of-the-art performances on multiple motion tasks including text-driven motion generation, motion captioning, motion prediction, and motion in-between.

<img width="1194" alt="pipeline" src="./assets/images/pipeline.png">
</details>

## 🚩 News

- [2023/12/01] Upload paper and init project 🔥🔥🔥

## ⚡ Quick Start

<!-- <details>
  <summary><b>Setup and download</b></summary>

</details> -->

## ▶️ Demo

<!-- <details>
  <summary><b>Webui</b></summary>


</details> -->

## 👀 Visualization

## ⚠️ FAQ

<details> <summary><b>Question-and-Answer</b></summary>
    

</details>
</details>

## 📖 Citation

If you find our code or paper helps, please consider citing:

```bibtex
@misc{yin2023shapegpt,
      title={ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model}, 
      author={Fukun Yin and Xin Chen and Chi Zhang and Biao Jiang and Zibo Zhao and Jiayuan Fan and Gang Yu and Taihao Li and Tao Chen},
      year={2023},
      eprint={2311.17618},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}

```

## Acknowledgments

Thanks to [Motion-GPT](https://github.com/OpenMotionLab/MotionGPT), our code is partially borrowing from them.

## License

This code is distributed under an [MIT LICENSE](LICENSE).

Note that our code depends on other libraries, including SMPL, SMPL-X, PyTorch3D, and uses datasets which each have their own respective licenses that must also be followed.
