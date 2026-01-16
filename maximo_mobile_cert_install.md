# Maximo Faststart 2026: Maximo Mobile Certificate Installation Guide

## Download the certificate file
1. Access the Maximo Application Suite server `home` page in your browser on a desktop computer. A message indicates that the connection is not private.
    1. On Safari, click the ```view the certificate``` link to open the certificate in a pop-up window
       <img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/f0b8d0c2-79ae-4848-bc6c-37d3178309ec" />

    2. On Firefox, click the ```Advanced``` -> ```view certificate``` link to open the certificate in a new tab
       <img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/553b9b5b-079e-49e8-8afa-440f360986fe" />


2. Find and save the certificate of the root certificate authority.
    1. On Safari, click the ```public.mas.mas.ibm.com``` tab to select the root certificate, and drag this file to a folder.
       <img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/ac8880db-954c-4806-8fac-ae8b615437b2" />
    2. On Firefox, click the ```public.mas.mas.ibm.com``` tab then scroll to ```Miscellaneous``` -> and click  ```PEM (cert)``` to download the Root CA certificate for the server
        1. <img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/e227a10f-3446-48cf-9d30-7600f004ed40" />
        2. <img width="3456" height="2234" alt="image" src="https://github.com/user-attachments/assets/4949d8b8-bc2c-4a3e-b84c-45cab234283e" />


## Install the certificate profile
1. Use Airdrop to send the saved root certificate file to your iOS device.
    1. <img width="450" alt="image" src="https://github.com/user-attachments/assets/4149ef51-10d4-4531-bca2-2445ca2f30cc" />

    2. <img width="300" alt="image" src="https://github.com/user-attachments/assets/82e3f157-5a39-40f8-b100-83b3970e7eaa" />

2. Open the Device Settings page.
3. In the User details section of the device settings, click Profile Downloaded.
   1. <img width="300" alt="image" src="https://github.com/user-attachments/assets/85d67a9b-1277-44ad-83dd-2904fbe1b577" />

4. In the Install Profile page, click Install.
    1. <img width="300" alt="image" src="https://github.com/user-attachments/assets/4ddbc62a-2888-4a81-8276-76ec39088d9a" />

5. If you are prompted, enter the iOS device passcode. A certificate warning is displayed.
6. Click Install and click Install again if you are prompted.
7. On the Profile Installed page, click Done.

## Trust the certificate
1. On the device, go to Settings > General > About > Certificate Trust Settings. The installed root certificate is displayed in the Enable Full Trust for Root Certificates.
2. Turn on trust for the certificate that you installed and click Continue. The certificate is trusted and enabled and you can proceed to use the Maximo Mobile application.
    1. <img width="300" alt="image" src="https://github.com/user-attachments/assets/a22bbadf-a591-4e9d-a19f-20a5a79c4c3f" />


## Congrats! 
1. Before opening the app, visit the following url to prep the mobile app's connection.
    1. API Url
        1. <img width="250" alt="image" src="https://github.com/user-attachments/assets/f6bd966b-f3dd-4390-8427-4686ac45f2e1" />


2. Now you can open up the Maximo Mobile App and scan the following url:
    1. Server URL (Scan from the IBM Maximo Mobile App)
        1. <img width="250" alt="image" src="https://github.com/user-attachments/assets/34b47ad9-1ce9-4938-bf3d-f43b27bc68ec" />


 
