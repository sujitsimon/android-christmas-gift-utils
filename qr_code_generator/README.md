
# android-christmas-gift-utils

Utils for Server Updation and QR code Generation


## Installation of required libraries

Install the required libraries using `requirement.txt` file

```bash
  python -m pip install requirement.txt
    or
  pip install requirement.txt
```
    
## Usage

#### Prize Excel

Update the Excel File under `.\prize_list\PrizeList.xlsx` with the required data

#### Asset Data
Update any assets in the `assets\font` and `assets\images` folder

#### Python Generator
Update the assets data in the Python src file `src\qr_code_generator.py`

## Generating Image Tokens
Generate image tokens using the following command:

```bash
cd src
python qr_code_generator.py
```
QR Code tokens will be generated in `qr_codes` folder