# StringResGenerator
This project automatically creates string resources for Android and ios by reading excel files in Google Drive.



## Installation requirements

### Install pip
- https://pypi.org/project/pip/

### Install Google Library
```pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib```

### Install openpyxl
- https://openpyxl.readthedocs.io/en/stable/

``` pip install openpyxl ```

### Install yattag (only used android)
- https://www.yattag.org/

``` pip install yattag ```

-----

## Steps to install and run this project

- Step1. Install pip
  - https://pypi.org/project/pip/
- Step2. Install Google Library
  - ```pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib```
- Step3. Create access credentials
  - https://developers.google.com/workspace/guides/create-credentials
- Step4. Download Json Key file and call api service aceept 
- Step5. Install openpyxl
  - ``` pip install openpyxl ```
- Step6. Install yattag (only used android)
  - ``` pip install yattag ``` 
- Step7. Make file `string_generate_templat.xlsx` at your google drive 
- Step8. Input google drive xlsx key in `download_google_drive.py` file_id variable
- Step9. Run `android.sh` or `ios.sh`

-----

### Google Drive API Setting menual
- https://developers.google.com/drive/api/v3/quickstart/python
- https://developers.google.com/workspace/guides/create-project


### Create access credentials 
- https://developers.google.com/workspace/guides/create-credentials


-----
MIT License

Copyright (c) 2021 Hyun Dong Han

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
