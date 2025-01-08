# Experiments in Audio Sentiment

## Some models to test
- ~~https://huggingface.co/distilbert/distilbert-base-uncased-finetuned-sst-2-english~~ ❌ (two labels)
- ~~https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest~~ ❌ (two labels)
- ~~https://huggingface.co/MoritzLaurer/ModernBERT-large-zeroshot-v2.0~~ ❌ (no pipeline)
- ~~https://huggingface.co/sbcBI/sentiment_analysis_model~~ ❌ (bad labels: LABEL_0, LABEL_1, etc)
- https://huggingface.co/SamLowe/roberta-base-go_emotions (28 emotions) ⚠️ (a lot of _neutrals_)
- https://huggingface.co/cardiffnlp/twitter-roberta-large-emotion-latest (11 emotions) ⚠️ (large model takes a long time to download and run)
- https://huggingface.co/joeddav/distilbert-base-uncased-go-emotions-student (28 emotions) ✅
- https://huggingface.co/cardiffnlp/twitter-roberta-base-emotion-multilabel-latest (11 emotions) ✅
- https://huggingface.co/bhadresh-savani/distilbert-base-uncased-emotion (6 emotions) ✅
