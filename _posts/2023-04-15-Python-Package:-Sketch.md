## Python-Package: Sketch

### 1. Introduction

A framework to Empower your pandas data analysis with a `ChatGPT like assistant` that not only comprehends your data context but also delivers highly relevant coding suggestions.

---
### 2. Key features
Load the data in your dataframe and use prompts to get answers & code suggestions. -- saves a lot of time for the exact commands & logic search

---
### 3. Getting started


i. Installation:\
&nbsp;
``pip install sketch``

ii. Import both Libraries:\
&nbsp;
``import sketch``\
&nbsp;
``import pandas as pd``

iii. Import your dataset:\
&nbsp;
``df = pd.read_csv('')``

iv.  Use direct:\
&nbsp;
``df.sketch.ask ('Your Question')``\
&nbsp;
``df.sketch.howto ('code help')``

---
### 4. Core components
Two main components
1. ``.ask`` - direct questions about the dataframe that yo have loaded in the memory &nbsp;
2. ``.howto`` - Direct code suggestion according to your requirement
---
### 5. Best practices
Basic Question answering like \
``df.sketch.ask("What are the column names?")``

Basic Code Suggestion like \
``df.sketch.howto("Get the top 5 grossing states")``

---
### 6. Use cases
Some real world data analysis prompts \
![Screenshot 2023-04-12 at 5 58 15 PM](https://user-images.githubusercontent.com/130972855/232471943-eddb6726-f0db-4df6-95be-fdbabe99d1a7.png)\
![Screenshot 2023-04-12 at 5 58 54 PM](https://user-images.githubusercontent.com/130972855/232471975-19ad27c2-a247-4413-8f9e-1bdf17f31567.png)\
![Screenshot 2023-04-12 at 6 02 14 PM](https://user-images.githubusercontent.com/130972855/232471999-e6d4a938-7153-440a-bccb-8e7f61aa37f4.png)\
![Screenshot 2023-04-12 at 6 03 36 PM](https://user-images.githubusercontent.com/130972855/232472013-5530e1c8-f75a-4eb5-b9b3-2edba39fedc6.png)\
![Screenshot 2023-04-12 at 6 05 35 PM](https://user-images.githubusercontent.com/130972855/232481960-5ccf1a43-22dd-4145-bd31-61061ecf155a.png)\
![Screenshot 2023-04-12 at 6 05 19 PM](https://user-images.githubusercontent.com/130972855/232472046-1322b0e8-8904-4576-9738-e4b878f9fd6e.png)\
![Screenshot 2023-04-12 at 6 05 27 PM](https://user-images.githubusercontent.com/130972855/232481961-37fac157-9521-4ee2-8ff9-0b8b601d7ed4.png)

---
### 7. Community and resources

If you like the project then appreciate with a Star ⭐ on their Github \
https://github.com/approximatelabs/sketch

Pypi Url \
https://pypi.org/project/sketch/

