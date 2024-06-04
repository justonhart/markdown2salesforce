# Markdown to Salesforce Converter
I forked this project because I needed to use this for work documentation and Knowledge articles. However, I wasn't able to successfully get it working on my Windows machine with the state it existed in. I made some changes and got it working from a virtual environment.

## Usage 
1. Install the package dependencies
2. Call the script with the .md file as the single parameter. The .html output will be placed in the same directory as the source .md file.
```
cd ./markdown2salesforce
pip install -r requirements.txt
python ./md2sf.py ./sample.md
```
