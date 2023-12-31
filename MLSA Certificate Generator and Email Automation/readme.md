# Microsoft Learn Student Ambassador Certificate Automation and Email Sender | Yatharth Chauhan - CLUMOSS

This repo simply use a template certificate docx file and generates certificates
both docx and pdf. It also sends personalised emails with certificates / LinkedIn Premium Voucher Links attached to it.

###  Working on Windows only.

## Run these commands in your terminal

```
git clone https://github.com/YatharthChauhan2362/MLSA-Certificate-Generator_Email-Sender.git
cd Certificate-Generator-MLSA
```
Now Copy your Participant List to the Data Folder and rename it as `Participant List.csv`. <br>
<e><i>The list must have the following fields: ```Name, Email```</i></e>.
```
pip install -r requirements.txt
python main_certificate.py
```

## Customization
- You can change the certificate template file in the `Data` folder.
- You can change the email template in the `Jupyter Notebooks`.

## How to send emails?
- You can use the `Send_certificates_via_email.ipynb` file to send emails to the participants.
- You can use the `Send_linkedinPremiumVouchers_via_email.ipynb` file to send LinkedIn Premium Vouchers to the Winners.
- You don't need to change anything in the file itself.
- All you need to do is feed Participant Data under ```Participant List.csv``` and then click on ```Run``` in the respective Jupyter Notebook.
- Now open outlook and login.
- Click on outbox and see the mails being sent one by one.

### There are 2 email templates:
- MLSA Email Template  
![image](https://github.com/YatharthChauhan2362/MLSA-Certificate-Generator_Email-Sender/assets/69571769/3478c021-c31d-4f67-a031-f2e5d40ddb00)

- Custom Email Template (by Sabyasachi)  
![image](https://github.com/YatharthChauhan2362/MLSA-Certificate-Generator_Email-Sender/assets/69571769/fb7f3429-0250-469e-accb-7387aba04d7d)


Souce Repo(I made some changes) : <a href="https://github.com/Sabyasachi-Seal/Certificate-Generator-MLSA">Click Here</a>
