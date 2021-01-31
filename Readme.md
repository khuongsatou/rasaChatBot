Readme.md

Rasa:----------

# Lấy từ Facebook develop
Token:
EAAGDmgheCOoBAIKNeKndnWAIXZBhZANf3qUZAuoYqdENsJJ2j7bZC6851yyYHBmKri7XVyCQfVmfZA6f6Xf6a0ccwpit3PlxNiO9ZBV4DmgArlj2QbqW4ACDpz1rwmxgQnym31ad9qpHxH3CCbND5vVG0GkledR3jbOUcGOXHEyrKE6JOR47PjS4uqb7m9NugZD



kbm.md


# Chay terminal để 
rasa run --endpoints endpoints.yml --credentials credentials.yml



# Tải source ngrok về
ngrok.com

# Giải nén và đưa vào project
./ngrok http 5005

# Tạo app facebook messeger và add địa chỉ này vào.
https://0a0690195b38.ngrok.io/webhooks/facebook/webhook

# add vào o mã xác thực face được lấy từ file credentials
 verify: "hoilamgi"



# Project python --version
python 3.7.7

# Active Env
python3 -m venv --system-site-packages ./venv
source ./venv/bin/activate 

# Kiểm tra tất cả packages project
pip3 freeze

# Tạo file requirements
pip3 freeze -l > requirements.txt

# Install all packages
pip install -r requirements.txt


# Tutorials
pip install rasa_core sklearn_crfsuite spacy rasa_nlu
python -m spacy download en
https://www.miai.vn/2020/03/19/rasa-series-4-cai-dat-rasa-theo-cach-moi-sieu-nhanh-sieu-gon-nhe/


# Có vấn đề với version rasa
pip install -r requirments.txt  --use-feature=2020-resolver
