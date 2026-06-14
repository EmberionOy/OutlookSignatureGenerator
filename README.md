# Exosens signature generator

Fill in the fields, select your office location. 
Note: You can always modify texts (e.g. locations of phone numbers) later in your Outlook signature editor.

The signature generator is a simple HTML+javascript page that generates the signature.
You will still have to manually paste it into the Outlook signature editor.

This method works for:

*   Outlook for Windows (Classic)
*   Outlook for Windows (New)
*   Outlook for MacOS
*   Outlook 365 (Web)

It has not been tested for:

*   Outlook for MacOS (Legacy)
*   Outlook for Android

It does NOT work for: 

*   Outlook for iOS, this version does not allow for transparent images

## Download the files and generate the signature

Start by downloading the generator files:  
Code -> Download ZIP

![Download the assets](/docs/download_zip.webp)


Unpack the zip-file to a folder, and _open **signature-generator.html** in your browser_.
1.  Fill in the fields (name, function, phone number)
2.  Select your office location
3.  Click _Generate signature_
4.  Click _Copy Signature_
5.  Go to Outlook and edit the signature.  
See below for version-specific information.

## Outlook for Windows (Classic)

In Outlook, go to:  
1.  File (top left) -> Options (bottom left) -> Mail (left) -> Signature… (middle right).
2.  New -> Name = Exosens (or whatever you like).
3.  Click the edit-field, and paste (Ctrl + V)
4.  If all goes well, there should be 6 images (top-left corner, Exosens logo, phone, mail, location and web) as well as your text.  
If the images are not included, go back to the generator and manually select the signature-text _and_ the images, and copy it (Ctrl + C). Ensure all images are selected!  
![Select all manually](/docs/select_all.webp)
5.  Set as default email signature
6.  Save; Done!  
![Result on Outlook Classic](/docs/classic_done.webp)

## Outlook for Windows (New)

TODO


## Outlook for MacOS 

In Outlook, go to:  
1.  Outlook (Menu bar) -> Settings (⌘ + ,) -> Signatures
2.  New (+ symbol), or edit existing
3.  Change the name to Exosens (or whatever you like), by clicking the pencil symbol
4.  Click the edit-field, delete any placeholder text, and paste (⌘ + V)
5.  If all goes well, there should be 6 image-PLACEHOLDERS, as well as your text.  
If there are no image-placeholders, go back to the generator and manually select the signature-text _and_ the images, and copy it (⌘ + C). Ensure all images are selected!  
6.  For each of the images, do the following:  
    *   Select the image
    *   Delete the image (delete or ⌫)  
    if selecton is difficult, place the cursor right after and press backspace (⌫)
    *   Insert image: ... -> Image -> Image from file; 
    Select the correct image in the files you downloaded
    ![Inserting images 1 by 1 on MacOS](/docs/insert_image.webp)
    *   Repeat for all 6 images
7.  Set as default email signature.  
![Result on MacOS](/docs/macos_done.webp)
8.  Click a different setting to ensure that it is saved (There is no dedicated save button, and it does not always save for some reason)
9.  Test the signature by emailing

## Outlook for web

In Outlook (outlook.office.com) go to:
1.  Settings, cog-wheel (top-right) -> Account -> Signatures
2.  Add signature (+ Add Signature)
3.  Add the signature-name, e.g. Exosens (or whatever you like) in the field just above the edit field
4.  Click the edit-field, delete any placeholder text, and paste (Ctrl + V or ⌘ + V)
5.  If all goes well, there should be 6 image-PLACEHOLDERS, as well as your text.  
![Inserting images 1 by 1 on Web](/docs/web_edit.webp)  
If there are no image-placeholders, go back to the generator and manually select the signature-text _and_ the images, and copy it (Ctrl + C or ⌘ + C). Ensure all images are selected!  
6.  For each of the images, do the following:  
    *   Select the image
    *   Insert -> Pictures
    Select the correct image in the files you downloaded
    ![Inserting images 1 by 1 on web](/docs/edit_web.webp)
    *   Repeat for all 6 images
7.  Set as default email signature.  
8.  Save. Done.


## Result

Your signature should now be in the Exosens style.

You can now delete the downloaded files.

As an added bonus, it also looks good in dark mode on Windows, MacOS and iOS. (And probably other systems)  

![Comparison](/docs/comparison.webp)

## Known issues
image size, especially the phone/mail/location/web icons vary in size depending on the platform. The problem is that Outlook signature editors strip out any size information. 
