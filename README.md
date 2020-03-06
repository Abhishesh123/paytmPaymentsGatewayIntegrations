# paytmPaymentsGatewayIntegrations
    
    
    First open your terminal and clone the project
    1 git clone https://github.com/Abhishesh123/paytmPaymentsGatewayIntegrations.git
    
    Open Project directory
    Now install the requirements
    pip install -r requirements.txt
    
    backports.shutil-get-terminal-size==1.0.0
        decorator==4.0.10
        Django==1.8
        enum34==1.1.6
        ipython-genutils==0.1.0
        pathlib2==2.1.0
        pexpect==4.2.1
        pickleshare==0.7.4
        prompt-toolkit==1.0.9
        ptyprocess==0.5.1
        pycrypto==2.6.1
        Pygments==2.1.3
        simplegeneric==0.8.1
        six==1.10.0
        traitlets==4.3.1
        wcwidth==0.1.7
        
        
    Make Migrations

    python manage.py makemigrations

    Migrate paytm app for transactions details

    python manage.py migrate

    Create Super user

    python manage.py createsuperuser

    Card:
    Card Number : Any Visa or Master Card
    Expiration Month & Year : Any Future month and Year
    CVV : 123
    OTP : 123123

    Wallet:
    Mobile Number : 7777777777
    Password : Paytm12345
    OTP: 489871

    Net Banking:
    Bank : Andhra Bank
    User : test
    Password : test

