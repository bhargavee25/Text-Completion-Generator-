# Text-Completion-Generator
A lightweight NLP application that predicts the next sentence based on user input, leveraging pre-trained transformer models like GPT-2. Built using Python, HuggingFace Transformers, and Streamlit, this tool demonstrates the power of Generative AI in real-world language tasks such as sentence prediction, writing assistance, and chatbot development.

Features
Generate context-aware next sentence(s) from user input.

Ranks top 3 predictions for relevance and coherence.

Simple and interactive web interface.

Optional evaluation module for grammaticality and contextual fit.

Technologies Used
Python 3.8+

HuggingFace Transformers

Streamlit

PyTorch or TensorFlow (backend for Transformers)

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/text-completion-generator.git
cd text-completion-generator
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install the dependencies:

bash
Copy
Edit
pip install -r requirements.txt
How It Works
User enters a sentence or paragraph into the input field.

The GPT-2 model processes the input and generates multiple next sentence predictions.

The system displays the top 3 most contextually relevant continuations.

(Optional) Evaluations are shown for grammaticality and coherence.

Running the App
bash
Copy
Edit
streamlit run app.py
Then, open the URL provided by Streamlit (typically http://localhost:8501/) in your browser.

Testing
The system has been tested across:

Various input types (short, long, and incomplete).

Edge cases (nonsensical or abrupt inputs).

Performance with different input lengths.

Project Structure
bash
Copy
Edit
text-completion-generator/
│
├── app.py                # Streamlit app
├── generator.py          # Core logic for sentence prediction
├── evaluator.py          # Optional relevance/grammar checks
├── requirements.txt      # Project dependencies
└── README.md             # Project documentation
Future Enhancements
Support for other models (e.g., T5, GPT-Neo).

User customization for number of predictions.

Integration with story generation or chatbot systems.

Improved evaluation and feedback mechanism.

License
This project is licensed under the MIT License.

Acknowledgements
HuggingFace Transformers

Streamlit
