# How to make realy fast your own form become public, with help of Google G Suite (persistence: GSheet, notification: Gmail)

## First phase: create backend

### first Step:
add the files Code.gs and email.html inside Google AppScript

### create a sheet:
Take the id of the sheet (check the URL)
Further:
change the ID in this line
  var sheet = SpreadsheetApp.openById('1QU9fe0_8cLGb6mFTIKU0lYl5Cer-RQZ8svQFln6pSWB').getActiveSheet();
 whith your newly created Sheet

 
change the email address where you want to receive notification with your own.

### third Step:
publish AppScript as webapp 
!!! Very important: You need to use your @gmail.com domain because you are able to publish this backend as a very permisive app
Execute the app as:
Me (youremail@address)

You need to authorize the script before distributing the URL.
Who has access to the app:
Anyone / even anonymous
[Deploy] (https://lh3.googleusercontent.com/N_CVHohMS77yCIZKq57eXlwFxVThO4XOhQLFqRrhmigCvRzy0TZBMY0VPoe3DKAe4hF9ZcdZbpN2Rz8WLpneH4JallHF0Sql2h0-GHOyPc7d-mKhr7uxtWnjMctKlQwA=s800)

### fourth step
copy the public link of your webapp


## Second phase: Frontend

### first Step:
Create a Google Site page

### second Step:
Change the HtmlFromForGSites.html by replacing the webapp link in the code with your own copied from "fourth step".
Now you can embed html code (HtmlFromForGSites.html) inside your Google Site page (This should be trivial)

### third Step:
publish the GSite page as publicly available. 
