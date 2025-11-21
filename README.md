# fraud-detection-using-AutoEncoder
Experiment using deep learning techniques to build and train a Fraud Detection model using AutoEncoder provided by PyOD and an anonymized credit card transactions dataset available at Kaggle. AutoEncoder helps detect abnormalities in the data by calculating the reconstruction errors. 

## Dependencies
Dependencies can be found in `requirements.txt`

## Installation
1. Clone the repo
```
git clone https://github.com/ptienthong/fraud-detection-using-AutoEncoder.git
```

2. Create a virtual environment
```
python -m venv venv
source venv/bin/activate
```

3. Install libraries
```
cd ~/fraud-detection-using-AutoEncoder
pip install --upgrade pip
pip install -r requirements.txt
```

## Run the code
If you have not activate your virtual environment, do
```
cd ~/fraud-detection-using-AutoEncoder
source venv/bin/activate
```

Open Jupyter notebook server to run the notebooks
```
jupyter notebook
```

Download dataset [creditcard.csv](https://www.kaggle.com/datasets/whenamancodes/fraud-detection?phase=FinishSSORegistration&returnUrl=/datasets/whenamancodes/fraud-detection/versions/1?resource=download&SSORegistrationToken=CfDJ8Ksq__M8KNdOsrtGDpOZ52UJbj2lKpub_CsPqFOr0MS38qILVqG8vhjS0qp2sMoVkYhoZzFtAQpaXAXhc71FrE1YCazBEGf-1puAS0lJvjJTHM_zKHyg7HYK1ycfNpJmgF5ds3fMpWd6GLaJ9dnjIodJlOwsWL9LmXfSqFwoZRQS58ndfkutZnz-c0KlrpneNKgiLznTwA4cl6SZTvxzWlh_wc1GmL8hehlJgzjmB7CXiSFw6FzRO4IlX04A02SfmU04xcFhcud-Yp-ua1UbV8aNOGDOvJGNura2vjxTCv1jgcRoiTbBo-4Ni9TdrL8nADNf8a6zrnTXQM25I6atzAz8Th2s7LfL&DisplayName=peera%20tienthong) and extract csv file in this directory
