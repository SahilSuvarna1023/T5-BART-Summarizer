# T5-BART-Summarizer
T5-BART Summarizer is an AI-powered text summarization tool that leverages T5-Small and BART-Large models to generate concise summaries from large text inputs. It supports batch processing, evaluates summaries using ROUGE metrics, and is optimized for NLP applications like news summarization and research condensation. 🚀

🚀 Features

Uses T5-Small and BART-Large-CNN models for summarization

Supports abstractive summarization

Processes batch text summarization efficiently

Evaluates summaries using ROUGE metrics

📦 Dataset

The project uses the CNN/DailyMail dataset, which contains news articles and their corresponding summaries. It also supports custom datasets in CSV format.

🔥 Usage

Run Summarization

python summarize.py

This will summarize 50 random samples from the test dataset and save results in summarized_results.csv.

Customize Sample Size

To change the number of samples, edit the load_dataset function in summarize.py.

📊 Evaluation

The project uses ROUGE metrics for evaluation:

python evaluate.py

🧠 Models Used

T5-Small

BART-Large-CNN

🤝 Contributing

Fork the repo

Create a new branch (feature-branch)

Commit changes

Push to GitHub and create a PR!

📜 License

This project is licensed under the MIT License.

⭐ Acknowledgments

Hugging Face Transformers

CNN/DailyMail Dataset

OpenAI & NLP Community
