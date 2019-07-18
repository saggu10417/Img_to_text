This is a script to extract data from a image and convert it to text.
Just follow some steps and enjoy it.

Create a virtualenv (virtualenv VENV_NAME)

Install the requirements (pip install -r requirements.txt)

sudo apt update
sudo apt install tesseract-ocr
sudo apt install libtesseract-dev

Run the command "tesseract filename.png stdout"
command =python ocr.py -i images/img2.png > output.txt

And now you can enjoy it.