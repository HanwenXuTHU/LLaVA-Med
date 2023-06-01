# LLaVA-Med: Large Language and Vision Assistant for BioMedicine

*Visual instruction tuning towards buiding large language and vision models with GPT-4 level capabilities in the biomedicine space.*

[[Paper](https://arxiv.org)] 

<!-- [[Data](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K)] [[Model](https://huggingface.co/liuhaotian/LLaVA-13b-delta-v0)] -->

**LLaVA-Med: Training a Large Language-and-Vision Assistant for Biomedicine in One Day** <br>

[Chunyuan Li*](https://chunyuan.li/), [Cliff Wong*](https://scholar.google.com/citations?user=Sl05ifcAAAAJ&hl=en), [Sheng Zhang*](https://scholar.google.com/citations?user=-LVEXQ8AAAAJ&hl=en), [Naoto Usuyama](https://www.microsoft.com/en-us/research/people/naotous/), [Haotian Liu](https://hliu.cc), [Jianwei Yang](https://jwyang.github.io/), [Tristan Naumann](https://scholar.google.com/citations?user=cjlSeqwAAAAJ&hl=en), [Hoifung Poon](https://scholar.google.com/citations?user=yqqmVbkAAAAJ&hl=en), [Jianfeng Gao](https://scholar.google.com/citations?user=CQ1cqKkAAAAJ&hl=en) (*Equal Contribution)

<p align="center">
    <img src="images/llava_med_logo.png" width="50%"> <br>
 
  *Generated by  <a href="https://gligen.github.io/">GLIGEN</a>  using the grounded inpainting mode, with three boxes: ``white doctor coat``, ``stethoscope``, ``white doctor hat with a red cross sign``.*
 
</p>

## Release

- [June 1] 🔥 We released **LLaVA-Med: Large Language and Vision Assistant for Biomedicine**, a step towards building biomedical domain large language and vision models with GPT-4 level capabilities.  Checkout the [paper](https://arxiv.org/abs/2304.08485)

<p align="center">
    <img src="images/llava_med_pipeline.png" width="90%"> <br>
 
  *LLaVA-Med was initialized with the general-domain LLaVA and then continuously trained in a curriculum learning fashion (first biomedical concept alignment then full-blown instruction-tuning). We evaluated LLaVA-Med on standard visual conversation and question answering tasks.*
</p>


## Related Projects

- [LLaVA](https://llava-vl.github.io/)
- [BioMed CLIP](https://huggingface.co/microsoft/BiomedCLIP-PubMedBERT_256-vit_base_patch16_224)
- [Instruction Tuning with GPT-4](https://github.com/Instruction-Tuning-with-GPT-4/GPT-4-LLM)


[![Code License](https://img.shields.io/badge/Code%20License-Apache_2.0-green.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/LICENSE)
[![Data License](https://img.shields.io/badge/Data%20License-CC%20By%20NC%204.0-red.svg)](https://github.com/tatsu-lab/stanford_alpaca/blob/main/DATA_LICENSE)
**Usage and License Notices**: The data, code and checkpoint is intended and licensed for research use only. They are also restricted to uses that follow the license agreement of LLaMA, Vicuna and GPT-4. The dataset is CC BY NC 4.0 (allowing only non-commercial use) and models trained using the dataset should not be used outside of research purposes.


