# ckb-Central-Kurdish-files-for-Tesseract-engine 
Hello everyone, today I will introduce the first Kurdish OCR trained data used by Tesseract engline (the most powerful engine for Optical character recognition supported by google since 2006) for extracting test from everything!  (:.
Let me tell you about Language prefix used by tesseract repo. They used kur_ara for Central Kurdish and kmr for Kurmanji but I told them use ckb as it's in the ISO-639, and leave kur for macro model language contains all dialects trained texts so see what will happen and what they say.
This repo contains a small test ckb.traineddata for Tesseract trained from Arabic script and also a unicharset.
This trained model has been created better to say finetuned from Arabic script model. It's only for testing and we we're now training it for LSTM best model.
Training text was about 200000 sorted lines with all misspelling in it but don't worry won't lead to any problem, Tesseract takes care of anything!. The training test cloned from Asosoft repo https://github.com/AsoSoft/AsoSoft-Text-Corpus and they have a large project for Kurdish Speech and Language Processing for first time, we're all waiting for and We appreciate their work but I reversed this mentioned line in their repo "Everywhere "ر" or "وو" is used as the first letter of words, it is replaced with "ڕ" or "وو" correspondingly." I thank them for their effort, But we all have to respect latest changes in Kurdish grammar.  
And about unicharset, I want to say I place all characters either panctution used for writting.
Arabic num and Persian num placed in unicharset
"ک" and "ك" included
"ھ" and "ه" included but as I said these doesn't make any problem, these has been seen a lot in Kurdish texts so after image or pdf OCRed we can make a wordlist according to Kurdish grammar and a spell checker to replce all "ك" with "ک" and others so.FOR more information and latest news and updates about Kurdish Grammar please visit "http://diyako.yageyziman.com/". 
other chars doesn'y exist in Kurdish moved to forbidden_characters file. 

for testing Kurdish OCR have a look to my Fb posts.


this is my email and Fb account, Please feel free to contact me if you have any questions or comments
ayub.rauf92@gmail.com 
Fb https://www.facebook.com/ayub.rauf.aziz
