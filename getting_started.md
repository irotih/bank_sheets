# Getting Started

## Creating your Bank
1. Visit https://docs.google.com/spreadsheets/d/1Nf8pPSalVTI3WOhHuqSUUYmU_DtZWOIk3NRTRdexcxM/edit?usp=sharing
2. Click on File -> Make a copy
3. Give it a name i.e. "My Kid's Bank Account" and save it to your own Google Drive.
4. If it doesn't open in a new tab, launch it from your Google Drive.

## Granting Permissions
The code for the Bank application is separate from the Google Sheets itself. This means you need to grant permissions for the application libraries to make changes in your sheets. The permissions must be granted for each Google Sheet using the Bank application and Google may prompt you again to grant permissions after a few month.

1. In the Bank sheet, click on any of the blue rectangular buttons (e.g. `Archive History`).
2. At the top you should see that a script is running. Give it a few seconds.
3. You will get a popup saying "Authorization Required". Click `Continue`.

    ![bank_perm_01_auth_req.jpg](https://github.com/irotih/bank_assets/raw/main/bank_perm_01_auth_req.jpg)
4. You will get a popup saying "Choose an account". Choose the Google account that has the Bank Google Sheets.

    ![bank_perm_02_choose_acct.jpg](https://github.com/irotih/bank_assets/raw/main/bank_perm_02_choose_acct.jpg)

5. You will get a popup saying "Google hasn't verified this app".
    1. Click the `Show Advanced` link near the bottom.
    2. Click the `Go to bank (unsafe)` link further down.

    ![bank_perm_03_warning.jpg](https://github.com/irotih/bank_assets/raw/main/bank_perm_03_warning.jpg)

6. Finally, you will get a popup saying "bank wants to access your Google account". Click `Allow`.

    ![bank_perm_04_grant_privs.jpg](https://github.com/irotih/bank_assets/raw/main/bank_perm_04_grant_privs.jpg)