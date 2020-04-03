# Demo_Django
PYTHON 3.7 (NOT ANACONDA)
DJANGO 3.0
ORACLE DB 11g2

OKay People. Follow the lines above sequentially
1. Open CMD/POWERSHELL/BASH or your preferred shell in the directory. (Make sure it has mysite and requirements.txt)
2. Now run 
  pip install -r requirements.txt

  
  (It will install Django and cx_oracle. You need not install them if you have already installed. You may face some error 
  during installation due to version mismatch of your python package or permission error)
  Fix: Permission error : Open your Shell as Admin
  FIx: Version Mismatch: 
    Open a virtualenv(Recommended for your project), activate it and run pip install -r requirements.txt
    
3. row cd into mysite folder
4. run 
  python manage.py runserver
  
 You will see hr countries table printed. 
 for connection details see polls/views.py
