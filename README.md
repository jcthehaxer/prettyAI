# What is PrettyAI?

PrettyAI is a fine-tuned version of Haotian Liu's [LLaVa](https://github.com/haotian-liu/LLaVA) model whose goal is to identify "pretty" and attractive young men in images. The main goal of this user case is to give modeling agencies the ability to implement AI in their recruiting process. While the standard image requirements and model poses can be strict depending on the agency, PrettyAI takes any image of a man and automatically classifies them as pretty or not. With this information, modeling agencies can then decide if they wish to continue with this candidate and take their standard requirements into account in the next round. PrettyAI can also help modeling agencies with this step as it may also return the race of the candidate. In doing so, we hope to diversify the current male modeling market.

# Dataset

We used a custom dataset to fine-tune our model. The dataset can be found on our Hugging Face page - [jcthehaxer/check](https://huggingface.co/datasets/jcthehaxer/check). The dataset contains over 1,000 image files depicting different types of young pretty men, also called pretty boys. In addition to the image files, a metadeta.csv file is included which links each of the images to its appropriate caption. To use the dataset, download it onto your local machine and then upload the files onto your workspace as instructed in **llava-finetune.ipynb**.

#Training

