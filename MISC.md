MISC WRITEUP

Download the text file entitled: WOMAN.docx
after downloading this file you will use either binwalk or just unzip to unzip the internal files of this text file
In my case I chose unzip , the syntax is as follows
unzip file.zip -d output file

![Capture d'écran 2022-12-08 16:40:31](https://user-images.githubusercontent.com/96654079/206462241-a639ca67-7fc8-4fae-b8c8-3b66d9ed3072.png)

after having unzipped the file there are several possibilities to open it either via the terminal or by opening it via the folder in the file explorer, in my case I open it via your terminal, the first folder I I chose open I found the flag in there, but the best thing is to open it via the folder, I found the flag in the word folder precisely in the document.xml file
to display what is inside the document.xml file I just did a cat document.xml but you have to make sure that you are in the word folder

![c](https://user-images.githubusercontent.com/96654079/206465689-f740f129-cfc4-42b8-8543-90e44eec4189.png)

And bingo here is the flaag, for this challenge there are several methodologies to get there
![fl](https://user-images.githubusercontent.com/96654079/206466295-b7e514f1-011d-4a46-b65a-80cc440beb1e.png)
