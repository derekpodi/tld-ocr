# tl;d(oc)r
Screenshot long text ---> output a short summary.

Utilize OCR on a screenshot to feed the captured text into a summarization CNN model.

![tld-ocr](tld-ocr.gif)

## Requirements

Will need to Install [macOCR](https://github.com/schappim/macOCR).

Install via Homebrew

```
brew install schappim/ocr/ocr
```

Install via Curl

``` 
curl -O https://files.littlebird.com.au/ocr-EPiReQzFJ5Xw9wElWMqbiBayYLVp.zip; 
unzip ocr-EPiReQzFJ5Xw9wElWMqbiBayYLVp.zip;
sudo cp ocr /usr/local/bin; 
```

## Setup

Install and run within virtual environment:

```
python3 -m venv env
source env/bin/activate
python3 pip install -r requirements.txt
```

Note: First run of the model will take time to download CNN model.
Can take few minutes to download and few GB for space needed.

## USE

Make sure you are in the project directory, then from command line run:

```
./ocr-shell.sh
```


