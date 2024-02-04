# AI-Chat-Bot
This is an AI bot that using Langchain to QA on a database and provide customers with product recommendations.
This is a Demo project on seeing how a power of LLM's colud be utilized to add AI to a SalesBot

https://vimeo.com/909626173?share=copy

#Installation Instruction (For Windows)

#### Steps for setting up the project in Windows
##### 1. Make sure you have the Python version above 3.9
##### 2. install virtualenv environment package
```
pip install virtualenv
```
##### 3. Create virtual environment under your project folder
```
C://<python path>/python.exe -m venv venv
```
##### 4. Active virtual environment from created venv
```
./venv/Scripts/activate.bat
```
##### 5. Install required python packages
```
pip install -r requirements.txt
```

## How to start the bot
##### 1. Set up openapi key as environment
```
set OPENAI_API_KEY=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
```
##### 2. Set the python packages as environment, which are installed in step 5 above
```
set PYTHONPATH=C:\<prject folder path>\venv\Lib\site-packages
```
##### 7. Start the bot
```
C://<python path>/python.exe main.py
```



