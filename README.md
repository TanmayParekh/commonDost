# commonDost
Bilingual Human-Computer Dialogue Framework

## Data

The `data/` folder consists of three metafiles and a folder corresponding for each batch of data collection.

The metafiles contain information about the chat and corresponding survey files. They have the following format
```
chat_json   survey_json
<chat_json_filename>   <survey_json_filename>
```

The data was collected via two sources: mechanical turk (mturk) and local community (community). They have been labelled with a prefix accordingly. Each folder contains the following files:
* `chat.html`: Visualization of all the chats and surveys
* `clean_transcript.json`: The raw data in a json format. This is only for filtered chats.
* `clean_survey.json`: The surveys for the filtered chats in a json format.

## Citations and Contributions

If you use the data or code, please use the following citation:

Parekh, T., Ahn, E., Tsvetkov, Y. and Black, A., 2020. "Understanding Linguistic Accommodation in Code-Switched Human-Machine Dialogues". In Proceedings of the 24th Conference on Computational Natural Language Learning.

    @inproceedings{parekh-etal-2020-understanding,
        title = "Understanding Linguistic Accommodation in Code-Switched Human-Machine Dialogues",
        author = "Parekh, Tanmay and Ahn, Emily and Tsvetkov, Yulia and Black, Alan W",
        booktitle = "Proceedings of the 24th Conference on Computational Natural Language Learning",
        year = "2020",
        publisher = "Association for Computational Linguistics",
        url = "https://www.aclweb.org/anthology/2020.conll-1.46",
    }

For any queries, please contact/email: tparekh[at]andrew.cmu.edu
