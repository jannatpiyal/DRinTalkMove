# Incorporating Discourse Relations For Detecting Talkmoves in Classroom Transcripts

The original documentation and resources for the off-the-shelf parser can be found here: https://github.com/chijames/structured_dialogue_discourse_parsing

The modified code and resources for using this discourse parser on TalkMove Dataset can be found here:
https://drive.google.com/drive/folders/1F9g_RRQM4mcG4xyi-adhFN5WtpH2PI0f?usp=sharing

The data preparation for training and training with STAC data is the same as the original documentation.
The following commands are for preparing the TalkMove dataset and then parsing the discourse relations in the TalkMove dataset:
```
python convertTMjsontotxt.py talkmoves/train.json talkmoves/train.txt 37
python convertTMjsontotxt.py talkmoves/dev.json talkmoves/dev.txt 37
python convertTMjsontotxt.py talkmoves/test.json talkmoves/test.txt 37
```
```
bash test_talkmove.sh
```

