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
*   Outlook for iOS

It has not been tested for:

*   Outlook for MacOS (Legacy)
*   Outlook for Android


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

## Outlook for iOS

Warning:  
This option is only if you are truly sadomasochistic.  
Microsoft allows you to copy-paste fancy email signatures in to the signature editor. Even images will show up, but ONLY on your iphone. It will also allow you to add images from your Photos collection, but these don't allow transparency. However, there is a workaround! But be warned, it takes some time and frustration.  

1.  Download all the images from the main-folder of this git from your browser.  
DO NOT SAVE TO PHOTOS! This ensures you download the png files and they are not passed through the Photos aspp (which removes background).  
For each of the files, corner_adjusted.png, exosens_adjusted.png, phone_icon.png, mail_icon.png, location_icon.png, web_icon.png, do the following:
    *   Navigate to the image through Github, e.g. OutlookSignatureGenerator -> corner_adjusted.png
    *   Click [. . .] -> Download
    *   Click Download, not view; the image will now be saved to your Downloads folder
    *   Repeat for all 6 images
    *   Open the Files app, either by clicking the URL-bar with the download indicator or through the home-screen.
    *   In the finder app, navigate to the Download folder and verify that the files are there  
    ![Save images in iOS to Files](/docs/ios_save_to_downloads.webp)
2.  Send yourself an email with a signature  
Important! In order to correctly copy-paste, ensure there is an extra Return BEFORE AND AFTER your signature. So before htting send, go to the end of your signature (probably the right of the table) and hit Enter/ Return. Check that you indeed added a new line AFTER the table, not just inside the signature-table.
3.  Go back to your phone and open the email in Outlook.
4.  Select the entire signature, including the line before and after.  
Copy
5.  Go to settings (Click your photo/ Circle with initials) -> Cog wheel -> Signature
6.  Click the signature field, and delete any text currently present
7.  Paste the signature
8.  Probably you have 6 extra images at the bottom. Delete them using backspace.
9.  Click the checkmark, and close the settings; Then return.
![Copy paste the signature in iOS](/docs/ios_copy_paste.webp)
10. You now see that the images are now replaced with placeholders. 
11. Do for each image the following:
    *   Switch to the Files app, open the first image you want to replace. It should now open in Preview
    *   Copy the image by clicking the 'share' button, and selecting Copy.  
    *   Switch back to outlook.
    *   Delete the placeholder by placing the cursor directly after the image, and click delete.  
    Tip: swipe up from the space bar, while keeping your finger on the screen, allows you fine control of the cursor.
    *   Paste the image
    *   Repeat for all images
![Copy each image from Preview](/docs/ios_copy_from_preview.webp)
11. Test the sending of the signature

## Result

Your signature should now be in the Exosens style.

You can now delete the downloaded files.

As an added bonus, it also looks good in dark mode on Windows, MacOS and iOS. (And probably other systems)  

![Comparison](/docs/comparison.webp)

## Known issues
image size, especially the phone/mail/location/web icons vary in size depending on the platform. The problem is that Outlook signature editors strip out any size information. 
