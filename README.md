# NFT generator

   NFT generator is a web service for collecting an
information about NFTs in Solana.

## Installation

1. You need to pip install next libraries: Flask, request, session, redirect, url_for, render_template, flash, psycopg2, psycopg2.extras, re, generate_password_hash, check_password_hash
```bash
from flask import Flask, request, session, redirect, url_for, render_template, flash
import psycopg2 #pip install psycopg2 
import psycopg2.extras
import re 
from werkzeug.security import generate_password_hash, check_password_hash
```
2. After step 1, you need to download PostgreSQL
3. Install all files from nftaggregator folder and connect it with your database

## Usage
![image](https://user-images.githubusercontent.com/99247587/199253109-fba789d4-64c1-421f-a8f2-b369f07b7e2d.png)
![image](https://user-images.githubusercontent.com/99247587/199253152-b38faff4-cda8-42c0-8656-43ba835c6d0b.png)
![image](https://user-images.githubusercontent.com/99247587/199253185-e799378b-3b0f-493c-bdb0-ff449cd49319.png)
![image](https://user-images.githubusercontent.com/99247587/199253215-7b392b59-56f4-4ebc-8b7e-4b324851a8d9.png)
![image](https://user-images.githubusercontent.com/99247587/199253240-0645a9b2-6422-463f-93b0-178bbd6829df.png)
![image](https://user-images.githubusercontent.com/99247587/199253275-068d498e-7b23-4c18-9e1e-b43a65d31229.png)
![image](https://user-images.githubusercontent.com/99247587/199253304-412f6aeb-5635-4b5b-b46c-dc1003b0e28d.png)
![image](https://user-images.githubusercontent.com/99247587/199253346-df348562-2c06-4743-8ac0-9cc81eb4da7a.png)


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
