# MHow to Run?

### Step 01: Create a conda environment after opening the repo

```bash
conda create -n medibot python=3.10 -y
```
```bash
conda activate medibot
```

### Step 02: Install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone and openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```bash
# run the following command to store embeddings to pinecone
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
- GPT
- Pinecone