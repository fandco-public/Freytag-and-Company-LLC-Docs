# How to Change the Name of a Microsoft Store App

# 1 Getting Started

- Open the app for which you are changing the name....

- To avoid manually having to change the app name in the app (as opposed to the Store where you will have to retype the name) use the C# code in your app that automatically pulls in and uses the app name you have retyped and changed on your package manifest.


# 2 Renaming

- If you are changing the name of an app already in the store you will need to change the 'primary' name for the app in the partner store ingestion interface.  First reserve the new app name for your old app and then select/make it the 'primary' name. 

- Create the web pages (description, privacy policy, and support email address) so they use the new app name.

- Change the app name and any other use of the old app name to the new app name in all of the language files (pay particular attention to the 'Description' field).


# 3 Repackaging

- Add a Packaging Template project using "&lt;app name&gt;Package".

- At this point you must tell the "&lt;app name&gt;Package" what it is packaging.  Do this by adding a reference to the application.  Right-click on "&lt;app name&gt;Package/Applications" and then select 'Add Reference'.  

- Then from the list of already built and compiled applications listed (you should see a list in a dialog) select the app being built to produce the "*.msixupload" file (compiled).  If you don't see the app with the name you expected that means the Solution does not have that app compiled and available.

- Right-click on the new Package and associate the app with the store.   When you right-click the pop-up list should have the option "Publish"->"Associate app with the Store". 

- Since you are changing the name of an application already in the Store, under "Publish"->"Associate app with the Store" you will probably have to select the checkbox (upper-right) ding "Include app names that already have packages" (Publish->Include app names that already have packages).

- Now look for the entry for the old app you are updating to the new name. At this point your "&lt;app name&gt;Package" project will take the version of the app you have in the store. 
                            
- Change the package name and version number in the package manifest.  In your VS 'Solution Explorer' this is usually found under "&lt;app name&gt;Package/Package.appxmanifest".


# 4 Icons and Images</h1>

- Add images to the 'images' folder in the "&lt;app name&gt;Package" folder.

- Do this by opening your "&lt;app name&gt;Package/Package.appxmanifest" and selecting the 'Visual Assets' tab.  You will be 'generating' your "&lt;app name&gt;Package/Images" contents using the largest app icon (PNG usually, maybe with 120x120 pixel dimensions) you have.  All other app icon sizes will be generated automatically into the "&lt;app name&gt;Package/Images" folder by this step.

- Select your largest by on the 'Visual Assets' tab selecting the '...' button to the right of  the 'Source' textbox and navigating the file picker to the largest app icon image.  Open that and you will see that icon displayed under 'Asset Generator' to left of the 'Source' prompt.  

- Now *uncheck* 'Apply recommended padding' checkbox.  
                            
- Now you are ready to 'Generate' all the app icon sizes.  Click the 'Generate' button.  You will be prompted to acknowledge that all the default app icon PNGs will be overwritten; do this.  You will now see "&lt;app name&gt;Package/Images" full of all the necessary sizes of app name icons.


# 4 Build

- On the project you want to package (probably called "&lt;app name&gt;Package), right-click the package name, and select "Publish"->"Create App Packages".  (You will probably want to select the 'Microsoft Store as &lt;app name&gt;Package by &lt;company name&gt;' radio button on the pop-up dialog).
                            
- Build to test and then build again by opening the packaged app by right-click on "&lt;app name&gt;Package" -> Publish -> 'Create app packages...'</p>


# 6 Certificates

- To test: find the *.cer (certificate) and *.msixbundle files just built (they are in the "&lt;app name&gt;Package/AppPackages/&lt;app name&gt;Package_&lt;version number&gt;_AnyCPU_Test/" subdirectory).

- Install the *.cer (certificate) file in your machine (or you won't be able to side-load the app.  Do this 'Local to your machine' and then install the certificate in your 'Root certificate store'.


# 7 Test and Upload

- Double-click the *.msixbundle file to install your app.  

- TEST.

- Now upload the "&lt;app name&gt;Package/AppPackages/"&lt;app name&gt;Package_&lt;version number&gt;_AnyCPU_bundle.msixupload" file to the Store to publish (use App Publisher for Microsoft Store <i>for extra points!</i>).

- Wait for certification.

[Back to App Publisher For Microsoft Store Page](https://www.freytag.us/app-publisher-for-microsoft-store.aspx)
