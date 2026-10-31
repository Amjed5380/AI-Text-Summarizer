AI Text Summarizer
An NLP-based text summarization project that uses a pre-trained
Transformer model from Hugging Face to convert long text into concise,
meaningful summaries. The notebook demonstrates how to load the
sshleifer/distilbart-cnn-12-6 model, generate summaries, and calculate
summary statistics.
Features
- Summarizes user-provided text automatically.
- Uses the Hugging Face sshleifer/distilbart-cnn-12-6 summarization
  model.
- Supports short, medium, and long summary-length settings in the
  interactive notebook interface.
- Displays the original and summarized word counts.
- Calculates the percentage reduction in text length.
- Includes Generate Summary and Clear All controls.
Technologies Used
- Python
- Hugging Face Transformers
- DistilBART (sshleifer/distilbart-cnn-12-6)
- PyTorch
- SentencePiece
- Jupyter Notebook
- ipywidgets
How It Works
1. Install the required Python packages.
2. Import the Hugging Face pipeline.
3. Load the pre-trained DistilBART summarization model.
4. Provide text to summarize.
5. Generate a summary with configurable minimum and maximum token
   lengths.
6. Compare the original and summary word counts and calculate text
   reduction.
Getting Started
1. Clone the repository
git clone https://github.com/<your-username>/<your-repository-name>.git
cd <your-repository-name>
2. Install dependencies
pip install transformers==4.57.3 torch sentencepiece ipywidgets
3. Run the notebook
Open AI_Text_Summarizer.ipynb in Jupyter Notebook or JupyterLab and
run the cells in order.
Model
This notebook uses the pre-trained Hugging Face model
sshleifer/distilbart-cnn-12-6,
accessed through the Transformers summarization pipeline.
Example
The notebook includes sample text about Artificial Intelligence, Machine
Learning, and Deep Learning. It generates a shorter version of the input
and reports:
- Original word count
- Summary word count
- Text reduction percentage
Project Structure
.
└── AI_Text_Summarizer.ipynb
Notes
- The notebook checks that the input contains at least 20 words before
  generating a summary.
- Summary length is selected using Short, Medium, or Long settings.
- The model may truncate very long inputs depending on the model's
  input limits.
- Generated summaries should be reviewed for accuracy and
  completeness.
