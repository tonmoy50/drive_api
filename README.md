# Drive API Backend (Django REST Framework)
This is a api endpoint service to mainly execute three process,
- Get list of permitted users
- Add New User
- Remove Existing Use

## Setup
You will need docker desktop to run this project. If you don't have docker installed then go [here](https://www.docker.com/products/docker-desktop) and download docker desktop in your system. Now, after that we will need two file that will handle google drive api key that is `mycreds.txt` and `client_secrets.json`. For, obvious reasons I have not included my key's in the repo. However, I will assist you on how to create those files for your usage. First head towards [here](https://github.com/tonmoy50/setup-pydrive-cred/)

## API Endponts

- List Users - http://127.0.0.1:8080/folder/all_users
- Add User - http://127.0.0.1:8080/folder/all_users
- Remove User - http://127.0.0.1:8080/folder/remove_user
