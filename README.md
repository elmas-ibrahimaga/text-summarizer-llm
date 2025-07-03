# text-summarizer-llm
# 🧠 Text Summarizer using Transformers

Topic: Text Summarization on CNN/DailyMail
Models Used: BART (facebook/bart-large-cnn), Pegasus (google/pegasus-cnn_dailymail)
Decoding Methods: Greedy, Beam Search, Top-k Sampling
Evaluation: ROUGE metrics
Tools: Hugging Face, Transformers, Datasets, Colab

📝 Comments on Approach, Results, and Findings
Approach: Used BART and Pegasus, two strong summarization models, with three decoding strategies.
Results: BART pipeline was straightforward and fast. Pegasus summaries were closer to reference.
Interesting Findings:
Greedy decoding is fast but less diverse.
Beam Search gave high-quality, balanced summaries.
Top-k added variety but was sometimes less accurate.
Evaluation: ROUGE scores support that Pegasus + Beam performs best for this task.
