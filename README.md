# Modification of Apple's question answering demo to use DBPedia

Original Apple article: https://developer.apple.com/documentation/coreml/finding_answers_to_questions_in_a_text_document

## Setup notes

The 200 MB model file is in the .gitignore file and not part of the repository. You need to download the BERT-Squad model file  `BERTQAFP16.mlmodel` from [https://developer.apple.com/machine-learning/models/](https://developer.apple.com/machine-learning/models/) and copy it to:

    ./FindingAnswers/Model/BERTQAFP16.mlmodel

