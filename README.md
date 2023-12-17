# A Task is Worth One Word: Learning with Task Prompts for High-Quality Versatile Image Inpainting

### [Project Page](https://powerpaint.github.io/) | [Paper](https://arxiv.org/abs/2312.03594) | [Online Demo(OpenXlab)](https://openxlab.org.cn/apps/detail/rangoliu/PowerPaint#basic-information)

This README provides a step-by-step guide to download the repository, set up the required virtual environment named "PowerPaint" using conda, and run PowerPaint with or without ControlNet.

## News

**December 17, 2023**

*Enhanced PowerPaint Model*

- We are delighted to announce the release of enhanced and more stable model weights. These refined weights can now be accessed on [Hugging Face](https://huggingface.co/JunhaoZhuang/PowerPaint-v1/tree/main). The `gradio_PowerPaint.py` file has also been updated as part of this release.


**Stronger Model Weights Coming Soon！**

<img src='https://github.com/open-mmlab/mmagic/assets/12782558/acd01391-c73f-4997-aafd-0869aebcc915'/>

## Getting Started

```bash
# Clone the Repository
git clone https://github.com/open-mmlab/mmagic.git

# Navigate to the Repository
cd projects/powerpaint

# Create Virtual Environment with Conda
conda create --name PowerPaint python=3.9
conda activate PowerPaint

# Install Dependencies
pip install -r requirements.txt

# Create Models Folder
mkdir models

# Set up Git LFS
git lfs install

# Clone PowerPaint Model
git lfs clone https://huggingface.co/JunhaoZhuang/PowerPaint-v1/ ./models
```

## Run PowerPaint

To run PowerPaint, execute the following command:

```bash
python gradio_PowerPaint.py
```

This command will launch the Gradio interface for PowerPaint.

Feel free to explore and create stunning images with PowerPaint!

## BibTeX

```
@misc{zhuang2023task,
      title={A Task is Worth One Word: Learning with Task Prompts for High-Quality Versatile Image Inpainting},
      author={Junhao Zhuang and Yanhong Zeng and Wenran Liu and Chun Yuan and Kai Chen},
      year={2023},
      eprint={2312.03594},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
