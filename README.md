# End-to-end-Medical-Chatbot-using-Llama2

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/8210182092/End-to-end-Medical-Chatbot-using-Llama2.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mchatbot python=3.8 -y
```

```bash
conda activate mchatbot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

<img width="1035" alt="download (1)" src="https://github.com/suvraadeep/Course-ChatBot-using-Llama-2-7B-model-and-Gemini-Pro/assets/154406386/45d4efa0-dbb5-484e-8a94-5891e762c83c">



### Create a `.env` file in the root directory and add your Pinecone credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

<img width="1035" alt="download (1)" src="assets/Screenshot 2024-01-19 012003.png">

### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama 2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```

```bash
# run the following command
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- Meta Llama2
- Pinecone