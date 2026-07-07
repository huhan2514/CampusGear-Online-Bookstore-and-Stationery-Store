# CampusGear Customer Service Chatbot

## Project Description

This project develops a customer service chatbot for **CampusGear Online Bookstore and Stationery Store**. The chatbot combines **LLM, RAG, and fine-tuned intent classification** to answer customer questions related to products, shipping, payment, order tracking, and refund processing.

## Google Colab Link

The full project code can be accessed through Google Colab:

https://colab.research.google.com/drive/1_2LDpTKeIz_MNNrPHcH1Udykfke7bAQ3?usp=sharing

## Main Features

- Product recommendation for students
- Shipping policy question answering
- Payment method question answering
- Order tracking by order ID
- Refund request processing
- RAG-based FAQ response generation
- Fine-tuned intent classification model
- Gradio interface for interactive chatbot testing

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- PyTorch
- Transformers
- Sentence Transformers
- FAISS
- Scikit-learn
- Gradio

## Dataset

The project uses the public **Olist e-commerce dataset** and converts it into a simulated CampusGear database, including:

- Product database
- Order database
- Refund database
- Customer service knowledge base

## Model Design

The chatbot uses:

- **SentenceTransformer** for text embedding
- **FAISS** for vector similarity search
- **DistilBERT** for fine-tuned intent classification
- **FLAN-T5** as the LLM backend for response generation

## How to Run

1. Open the Google Colab link above.
2. Run all cells from top to bottom.
3. Install the required libraries when prompted.
4. The chatbot will load data, build the knowledge base, train the intent model, and generate responses.
5. Run the final Gradio cell to test the chatbot interactively.

## Output Files

The notebook can generate the following output files:

```text
campusgear_chatbot_simulated_outputs.csv
campusgear_chatbot_evaluation_results.csv
campusgear_chatbot_evaluation_summary.csv
campusgear_product_database_from_olist.csv
campusgear_order_database_from_olist.csv
campusgear_refund_database_from_olist.csv
campusgear_finetuned_intent_model
```

## Author

HU HAN
