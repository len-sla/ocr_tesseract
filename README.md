## Project Name Tesseract 4.0x+ with LSTM


> <p>Tesseract 4.0x+ added a new OCR engine based on LSTM neural networks.<br> That feature and a lot impleented in previous releases made my attention. Number of languages which are recognised( ~60) is also impresive.<br>

For Latin-based languages, the existing model data provided has been trained on about 400000 textlines spanning about 4500 fonts.<br> For other scripts, not so many fonts are available, but they have still been trained on a similar number of textlines. eg. Latin ~4500 fonts, Devanagari ~50 fonts, Kannada 15.<br>


Library is installed from : [Tesseract ](https://github.com/tesseract-ocr/tessdata_fast) .<br>
<br>


### Results: on the left side there is a picture on the right opned output text file after ocr processing

![### source-result ](ocr-result-eng.PNG)
---

### Additional funcions:

To retrieve text from video files ffmpeg was used to split file to frames 
with given diffrence factor when text presentation was changed.
Once having set of pictures in directory they were OCRed in a batch to text file.

---

![### processing files from folder](frames.PNG)
---

![### processing files from folder](folder.PNG)


### Technologies
* Python, 
* LSTM
* OCR



### Setup
Easiest way is to install/update libraries accordnig to install secion in notebook




### Contact
Created by: _len.sla_

