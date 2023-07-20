# 🧪 Projects

## [open-domain-question-answering](https://github.com/chicuongdx/question_answering-ir) 🔗
- Approximately 1 million wiki entities are indexed and stored. The system is able to answer open-domain questions by retrieving the most relevant entities from the index.
- Build BM25 index and use it to retrieve the most relevant entities.
- Fined turned BERT QA and BERT Sentence Pair are used to retrieve the most relevant entities.

## [face-recognition](https://github.com/chicuongdx/cs331_faceid) 🔗
- Face recognition system using haarcascade and arcface.
- Use haarcascade to detect faces in images.
- Use arcface to extract features from faces.
- Use cosine similarity to compare features.

## [captcha-recognition](https://github.com/chicuongdx/crnn_ctc) 🔗
- Captcha recognition system using CRNN and CTC loss.
- CRNN is used to extract features from images.
- CTC loss is used to decode the features.
- Custom CRNN architecture:
  - Change CNN layers:
    - Use 1 CNN layer.
    - Use 3 CCN layers.
    - Use AlexNet architecture.
  - Custom RNN layers:
    - LSTM unit
    - GRU unit
    - RNN unit