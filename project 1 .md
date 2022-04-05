# Install Apache using Ubuntu’s package manager
<img width="1440" alt="Screenshot 2022-04-05 at 10 13 02" src="https://user-images.githubusercontent.com/36015933/161739741-4f8f6fdd-8e64-4e69-9feb-67dc8dd2dde4.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 16 25" src="https://user-images.githubusercontent.com/36015933/161739764-b0895272-c497-42c7-8b9f-910b1e1e2306.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 28 10" src="https://user-images.githubusercontent.com/36015933/161739795-7ff7e27d-edc5-49bc-9f52-39b9b057f4fc.png">




# To verify that apache2 is running as a Service in our OS, use following command
<img width="1440" alt="Screenshot 2022-04-05 at 10 19 03" src="https://user-images.githubusercontent.com/36015933/161739779-87aa21bb-6725-446d-9901-d2697ebdb6fd.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 35 55" src="https://user-images.githubusercontent.com/36015933/161739825-c325e927-66fe-49b5-a970-2aaedfa44738.png">


# First, let us try to check how we can access it locally in our Ubuntu shell, run
<img width="1440" alt="Screenshot 2022-04-05 at 10 23 57" src="https://user-images.githubusercontent.com/36015933/161739784-c1ebfa29-1100-4177-978c-76ab7447f82c.png">


# Now it is time for us to test how our Apache HTTP server can respond to requests from the Internet.
# Open a web browser of your choice and try to access following url
<img width="1440" alt="Screenshot 2022-04-05 at 10 26 51" src="https://user-images.githubusercontent.com/36015933/161739790-f4325819-55cd-49cb-90ad-44813a5000eb.png">

# Installing Mysql
<img width="1440" alt="Screenshot 2022-04-05 at 10 28 26" src="https://user-images.githubusercontent.com/36015933/161739805-0e158b7c-b078-4bf0-b215-5487c18beddd.png">

# Secure Mysql installation
<img width="1440" alt="Screenshot 2022-04-05 at 10 30 38" src="https://user-images.githubusercontent.com/36015933/161739816-f4b7d7b5-0e5a-4034-a71b-8b0b652bd360.png">

# Validate Password plugin
<img width="1440" alt="Screenshot 2022-04-05 at 10 34 57" src="https://user-images.githubusercontent.com/36015933/161739817-46099416-705c-4881-94c0-a737eb98e3ba.png">

# sudo mysql
<img width="1440" alt="Screenshot 2022-04-05 at 10 35 35" src="https://user-images.githubusercontent.com/36015933/161739822-bfa65937-926c-4ad6-b3f5-f2eaa3467806.png">

# Install 3 packages
# sudo apt install php libapache2-mod-php php-mysql
<img width="1440" alt="Screenshot 2022-04-05 at 10 39 13" src="https://user-images.githubusercontent.com/36015933/161739827-a869ca69-0ef9-4214-9add-4015b198c321.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 41 03" src="https://user-images.githubusercontent.com/36015933/161739839-9e950fae-1b77-40ff-a742-adeeb943692f.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 41 13" src="https://user-images.githubusercontent.com/36015933/161739848-82451340-5498-4006-a1ef-8dcd2f80db15.png">

# Php -v
<img width="1440" alt="Screenshot 2022-04-05 at 10 42 23" src="https://user-images.githubusercontent.com/36015933/161739857-4d3b548e-5893-4ccd-9018-11cc3673af6b.png">

# Create the directory for projectlamp using ‘mkdir’ command as follows:

<img width="1440" alt="Screenshot 2022-04-05 at 10 46 43" src="https://user-images.githubusercontent.com/36015933/161739863-e36ab244-fb29-42c3-97c1-4cb931124f21.png">
<img width="1440" alt="Screenshot 2022-04-05 at 10 49 27" src="https://user-images.githubusercontent.com/36015933/161739876-02884406-30bb-4c80-b1f1-b34fa46f24bb.png">

###  Use the ls command to show the new file in the sites-available directory
###  Use a2ensite command to enable the new virtual host:
### To make sure your configuration file doesn’t contain syntax errors

<img width="1440" alt="Screenshot 2022-04-05 at 11 28 42" src="https://user-images.githubusercontent.com/36015933/161739879-b269aadc-553a-45a6-96a1-fb326b0fd4d8.png">
<img width="1440" alt="Screenshot 2022-04-05 at 11 30 52" src="https://user-images.githubusercontent.com/36015933/161739885-8521550c-b0ab-4b29-9a68-515a344aeef2.png">

# Now go to your browser and try to open your website URL using IP address:
<img width="1440" alt="Screenshot 2022-04-05 at 11 38 23" src="https://user-images.githubusercontent.com/36015933/161739888-d31b4f94-aa15-4c82-a43c-8633a70d0f38.png">

# sudo vim /etc/apache2/mods-enabled/dir.conf
<img width="1440" alt="Screenshot 2022-04-05 at 11 39 29" src="https://user-images.githubusercontent.com/36015933/161739892-392d3645-3704-4625-b8b4-ca8e56490488.png">
<img width="1440" alt="Screenshot 2022-04-05 at 11 47 45" src="https://user-images.githubusercontent.com/36015933/161739893-7e297382-a514-4de5-bfb5-32abc31cdbc3.png">
