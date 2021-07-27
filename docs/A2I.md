## Improving Speech-to-text Machine Learning using A2I (Augmented Intelligence)

For This workshop, We are going to use the resource from [this blog](https://aws.amazon.com/blogs/machine-learning/improving-speech-to-text-transcripts-from-amazon-transcribe-using-custom-vocabularies-and-amazon-augmented-ai/)

Prerequisites:
1. SageMaker Studio, or SageMaker Notebook.
2. SageMaker Ground Truth private team.

Steps:
1. please clone this git: `https://github.com/aws-samples/amazon-a2i-sample-jupyter-notebooks` on your SageMaker Notebook.
2. open `A2I-Video-Transcription-with-Amazon-Transcribe.ipynb` notebook.
3. choose `Python 3 (Data Science) kernel with t3.medium notebook size`

Notes:
1. Please replace this code
```
!pip install jiwer
```


to this code

```
!apt-get update && apt-get install -y build-essential
!python -m pip install jiwer
```


[BACK TO WORKSHOP GUIDE :house:](../README.md)

[BACK TO PREVIOUS GUIDE :arrow_left:](SpeakerIdentify.md)