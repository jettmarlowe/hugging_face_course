# hugging_face_course
My notes from the Hugging Face course at https://huggingface.co/course/

# Set up environment
```bash
conda create --name transformers_course  python=3.9
conda activate transformers_course
conda install -c conda-forge pandas pip
conda install jupyter notebook
conda install pytorch torchvision torchaudio -c pytorch
pip install transformers sentencepiece datasets evaluate scipy sklearn

jupyter notebook
```

# Chapters
* [Transformer Models](1_transformer_models.ipynb)
* [Using HuggingFace Transformers](2_using_transformers.ipynb)
* [Fine-Tuning a Pretrained Model](3_fine-tuning_a_pretrained_model.ipynb)
* [Sharing Models and Tokenizers](4_sharing_models_and_tokenizers.ipynb)
* [The Datasets Library](5_datasets_library.ipynb)