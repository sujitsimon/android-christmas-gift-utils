
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

### QR Code Generator

```bash
cd qr_code_generator
```

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

### Database Uploader

```bash
cd db_uploader
```

### Name Excel
Update the Name Excel in the required format and place it in the db_uploader/Name.xlsx

### Credential JSON
Update the credentials.json file in the db_uploader/credentials.json

``` json
{
    "username" : "xxx",
    "password" : "yyy"
}

```

```python 
python update_mongo_db.py
```

The Database will be updated with the Prize Data and Name File
