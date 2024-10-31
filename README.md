# Diverse Sign Language Translation

About The official implementation of the paper "[Diverse Sign Language Translation](link)".

Like spoken languages, a single sign language expression could correspond to multiple valid textual interpretations. Hence, learning a rigid one-to-one mapping for sign language translation (SLT) models might be inadequate, particularly in the case of limited data. In this work, we introduce a Diverse Sign Language Translation (DivSLT) task, aiming to generate diverse yet accurate translations for sign language videos. Firstly, we employ large language models (LLM) to generate multiple references for the widely-used CSL-Daily and PHOENIX14T SLT datasets. Here, native speakers are only invited to touch up inaccurate references, thus significantly improving the annotation efficiency. Secondly, we provide a benchmark model to spur research in this task. Specifically, we investigate multi-reference training strategies to enable our DivSLT model to achieve diverse translations. Then, to enhance translation accuracy, we employ the max-reward-driven reinforcement learning objective that maximizes the reward of the translated result. Additionally, we utilize multiple metrics to assess the accuracy, diversity, and semantic precision of the DivSLT task. Experimental results on the enriched datasets demonstrate that our DivSLT method achieves not only better translation performance but also diverse translation results.

<img src="./Images/Intro_De.jpg" width="900" />

TODO:

- &#9989;Release the extended sign language translation datasets, CSL-Daily-Div and PHOENIX14T-Div.
- (comming soon) Release the two-stage DivSLT training paradigm code.
- (comming soon) Release checkpoints for reproducibility.

# Licenses

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

# Citation

Please consider citing our work if you find this repo is useful for your projects.

```bibtex
@article{shen2024diverse,
  title={Diverse Sign Language Translation},
  author={Shen, Xin and Shen, Lei and Yuan, Shaozu and Du, Heming and Sun, Haiyang and Yu, Xin},
  journal={arXiv preprint arXiv:2410.19586},
  year={2024}
}
```
