Plagirm Checker

Basic Functionality: Plagirm detection is conducted by changing the information on the textdocuments into vectors, and then to arrays of numbers.

Supplementary Documents.
 https://www.digitalocean.com/community/tutorials/vectors-in-python




Step 1 

To get started with the code on this repo, you need to either *clone* or *download* this repo into your machine just as shown below;

```bash
git clone https://github.com/Kalebu/Plagiarism-checker-Python
```

## Dependencies 

Before you begin playing with the source code you might need to install deps just as shown below;

```bash
pip3 install -r requirements.txt
```

## Running the App

To run this code you need to have your textual document in your project directory with extension **.txt** and then when you run the script, it will automatically loads all the document with that extension and then compute the similarity between them just as shown below;

```bash
$-> cd Plagiarism-checker-Python
$ Plagiarism-checker-Python-> python3 app.py
('john.txt', 'juma.txt', 0.5465972177348937)
('fatma.txt', 'john.txt', 0.14806887549598566)
('fatma.txt', 'juma.txt', 0.18643448370323362)

```



