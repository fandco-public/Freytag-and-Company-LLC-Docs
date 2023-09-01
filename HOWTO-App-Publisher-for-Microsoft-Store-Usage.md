If you discover a needed correction to this document please make changes and issue a pull request - thank you.

# 1 Welcome

Thank you for using App Publisher for Microsoft Store (APfMS).  We at Freytag & Company, LLC (F&CO) hope APfMS helps you have many easy and fast application updates

# 2 Support

We want your experience to be a good one.  Please post your questions to https://StackOverflow.com with the abbreviation “APfMS” in the title if you have problems following this guide or using APfMS.  Or just email us your question to: team@freytag.us.

# 2.1 Microsoft Store Support

For help the first time getting your app into the Microsoft Store, “Windows Developer Support” (https://aka.ms/storesupport, look for the “Contact Us” tab) is your friend.  Do be patient.  They are good people; but may be a little busy.  

We are experienced publishing to the Microsoft Store.  If you are stuck, then post you publishing question to the Microsoft Store with the text “PubToMSFTStore” in the title to https://StackOverflow.com.  Note, that is a public forum so please do not post proprietary information in your question.  

# 3 What App Publisher for Microsoft Store (APfMS) Does

Save you time by:

- *Publish your apps faster.*  The first time the Microsoft App Store Certification Team reviews your product it can take days.  Updates to your app take minutes or hours.  Read “Fast Publish” below.

- *Less form filling for similar apps.*  APfMS lets you save, edit, and reuse your app’s publishing configuration for reuse in your other apps.  This reduces errors and saves time.  Read “Archive and Reuse Workflows” below.

- *Up-to-date international prices.*  The Microsoft Store updates international prices every few months or slower.  APfMS’s prices are updated to a weekly average.  Read “Current Rates” below.

- *Accurate local prices for each local economy.*  Bread in an expensive country (looking at you Switzerland) costs more dollars than bread elsewhere; same for apps.  APfMS lets you avoid overpricing your app in most countries; read “Purchasing Parity Prices” below.

- *Publish in all languages.*  Automated translations let you support nearly 100 languages but it takes days to put that in the App Store using their ingestion portal.  APfMS makes publishing every language as fast as publishing in only one language.  Read “Easy Multilingual Publishing” below.

APfMS organizes your workflow of getting your app into the Microsoft App Store through its tabs.  As you work from left-to-right through your tabs (Connect, Pricing, Languages – Fields Mapping, Languages – Images and Application, and Update to Store), you also progress to the final step where you actually do “Update (your app) to (the) Store”.  

To assist in your introduction to APfMS we have open-sourced a UWP app called [Open Password Generator](https://github.com/fandco-public/OpenPasswordGenerator); available on GitHub.  The Microsoft Store requires each app use a unique name so you will need to [rename your version of Open Password Generator](https://www.freytag.us/how-to-change-the-name-of-a-microsoft-store-app).  Of course, the F&CO version is named [Open Password Generator](https://www.microsoft.com/en-us/p/open-password-generator/9nblggh0gr80?activetab=pivot:overviewtab).

APfMS only *updates* your app because the Microsoft Store requires initial publication of an app be *manual*.

*APfMS does not change anything about your app or its Microsoft Store listing until you actually get to the last tab and “Upload” your package.*

## 3.1 Fast Publish

Updating apps with APfMS takes a few tens of minutes from start to published-in-the-store.  This constrasts to what can be hours for updates through the Microsoft Store App Ingestion web portal.  We would like to know about your experience; email us at team@freytag.us.  

## 3.2 Archive and Reuse Workflows

APfMS's many fields and choices can be saved and reloaded later.  Even partial work can be saved, reloaded, changed and re-saved.  This means even if not everything is ready for publication at the same time, the workflow can still begin to preserve parts as they become ready.  

When part of your workflow is shared between apps it is possible to reuse the saved publication work from a previous app.  Perhaps some of the pricing should be reused, easily done by reloading an old workflow, even a partially-completed one, and filling in and changing entries as necessary.  

For much more detail see "Using APfMS - Load & Save Work" below.

## 3.3 Current Rates

Every update of APfMS brings the latest "Market" exchange rates.  Not only does APfMS allow more accurate prices in many more local currencies but the prices update more frequently than the "Microsoft" exchange rates ("Microsoft" rates are of course available in APfMS).  

## 3.4 Purchasing Parity Prices

We at F&CO use the “PPP Rates” option when pricing our apps and we highly recommend you do the same.  PPP Rates adjust for the local cost of living.  Only with PPP Rates will you be able to price relative to the local price for gum, bread, an appliance, or a motorcycle.  Neither Microsoft or Public Market rates consider what a price “feels” like for a local person.  

If you are currently pricing in a developed nation’s currency (e.g. the US Dollar), and use either Microsoft or Public Market exchange rates, then in most of the rest of the world your prices will “feel” too high in the lesser-developed nation’s local currency.  This is because Microsoft and Public Market rates reflect large international money movements and not the local cost-of-living.  You will lose sales as a result.  This is why F&CO uses “PPP Rates” to translate our carefully chosen prices into prices that reflect local conditions..  

The limitations of PPP Rates are that they are often years old.  However, local inflation/deflation rates historically do not change very quickly for many countries and that limitation is offset by the sales by not overpricing in weaker currencies with a high local purchasing power.

Another limitation of “PPP Rates” is they are not available for the most tiny countries.  For now, selecting "PPP rates" will produce more accurate prices but in only 173 markets while "Market" rates are available in 237 and "Microsoft" rates in 242 markets.  The timeliness and coverage of “PPP Rates” will improve as this feature gains popularity.  

## 3.5 Easy Multilingual Publishing

Loading a multilingual app into the MSFT App Store is incredibly tedious.  Not only must you translate your app but then the app ingestion web portal needs Product Description, Release Notes, Keywords etc., be manually entered for each and every language.  You might do this for two, or maybe three but 100 languages is out of the question.  

The “Languages - …” tabs handle all of this.  For your first manual upload you only define the fields for one of your app’s languages.  For subsequent updates, even the day your app is approved, use APfMS to load all your languages with just a few clicks.  

# 4 Usage

Using APfMS starts with an app already manually uploaded to the Microsoft Store through its App Ingestion Web Portal.  If the app needs sophisticated pricing and/or is multilingual we recommend the first upload use: simple pricing, be published in one language, and only to one market.  This will save an enormous amount of time not typing, and possibly making mistakes, in the Web Portal.  

To undergo the usual multi-day Store validation, apps must be public as private apps are not reviewed.  Subsequent app reviews by the Store frequently only take hours to complete.  APfMS uploads frequently are reviewed in less than an hour.  The second and subsequent app updates can be done quickly with APfMS so feel free to make it available in all markets while using its pricing and multi-lingual support features.  

Updating the app should be carried out by filling out the forms on APfMS's tabs from from left-to-right.  Each tab is explained in depth below in sections matching each tab's names:

*	Connect,
*	Prices,
*	Languages - Fields Mapping, and 
*	Languages - Images and Application.  
	
Only the "Connect" and "Update to Store" are required.  Select "no change" on tabs for which the app requires no update.  Follow the detailed instructions below.

## 4.1 Let’s Begin – Requirements

Putting apps in the Microsoft Store is by far the easiest way to publish an app.  Microsoft has realized this and is expanding the type of digital products sold in the Store.  Beyond WPF and UWP apps, the Store is going to be used to sell movies, music, games, and also Android apps previously only available in the Amazon android app store.

Before you can publish to the Microsoft Store there are four requirements:

1. [Get a free Azure Account](https://azure.microsoft.com/en-us/free/),
	* *This account includes Azure Active Directory (AAD) at no charge,*

2. [Become a Microsoft Partner](https://developer.microsoft.com/en-us/microsoft-store/register/),
	* *The Partner Account allows manual app publication through the Microsoft Store Ingestion Web portal.  Businesses should not sign up as individuals or they lose the ability to brand as a business in the store*,

3. [Connect the Partner Account to the Azure Active Directory (AAD)](https://docs.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services#associate-an-azure-ad-application-with-your-windows-partner-center-account),
	* *AAD handles access control (passwords, etc.), for a Microsoft Account, it is essential, and free.  Connecting AAD and a Partner Account allows AAD to manange access to the Partner Account's Store API,* and 

4. [Get Partner ID, Client ID, and Client Secret so APfMS can access the correct Partner Account](https://docs.microsoft.com/en-us/windows/uwp/monetize/create-and-manage-submissions-using-windows-store-services#associate-an-azure-ad-application-with-your-windows-partner-center-account), 
	* This is a complicated step - you can't break anything.  Just follow the linked steps carefully.
	* *The Client Secret is given once when the AAD and Partner Account are connected; save it somewhere safe.  The Client ID identifies the connection.  The Partner ID is found in the URL of every Partner Account page and under the account properties.*

The above linked instructions must be followed to use the Microsoft Store App Ingestion API.  If you already have a Microsoft Account or a Partner Account skip those steps.  

If you have questions please see the section *2 Support*; we and Microsoft are ready to help.  

APfMS needs the Partner ID, Client ID, and Client Secret to authenticate and use the Store API.  Save these credentials in a secure cut-and-paste-able location.  *Keep these credentials private.  Anyone having these credentials can publish to your store.*  

The first time an app is published it must be published thorugh the web portal.  For this reason, keep an app's first version simple; use simple pricing, and only publish in one language.  Here are [instructions on publishing your UWP apps to the Store](https://social.technet.microsoft.com/wiki/contents/articles/34483.publish-your-app-to-windows-store.aspx).  

APfMS helps make app updates to version 2.0 easy and fast avoiding many of the UWP publishing steps outlined above.  The API and APfMS can only be used for updates.  As soon as an app is first approved and published in the store, go ahead and get fancy using all the languages and prices for every market.  

(APfMS will support Azure Key Vault in a later version).

*You are now done with the slightly tricky part.  From here on APfMS just needs to know about your app.*

## 4.2 Using APfMS - Load & Save Work

Because APfMS is designed around an app publication workflow it is possible to save your work at any point.  Clicking the "Save Work" button (see #1 below) opens a file save dialog.  Save the configuration under any name at any point in the publication workflow.  

The result is kept in a ZIP file with a \*.fsap extension.  Whatever partial work is defined so far, field mappings, app selection, images are all copied and saved into APfMS's FSAP file.  

After an app is reloaded from a \*.fsap file all selections can be changed and the file can be overwritten or a new FSAP file created.  

Clicking the "Load Work" button (see #2 below) will present a file selection dialog.  Selecting any file with a \*.fsap extension will overwrite all APfMS's workflow tabs with the saved state of the reloaded publication workflow.  

![APfMS_LoadAndSaveTab_4.2.1.png](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LoadAndSaveTab_4.2.1.png)

APfMS's many fields and choices can be saved and reloaded later.  Even partial work can be saved, reloaded, changed and re-saved.  This means even if not everything is ready for publication at the same time, the workflow can still begin to preserve parts as they become ready.  

The saved file ZIPs up all the components and configurations to publish an app making every published version an *exact* archival copy of every published version of an app.  
If several apps are similar then the configuration for one app can be loaded, altered and saved under another name.  This can save considerable time in updating several apps.  

## 4.3 Using APfMS – Credentials

Once you start APfMS, Enter all three (3) credentials (Tenant ID, Client ID, and Client Secret) and click the “Submit” button.  

![APfMS_ConnectTab_4.3.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_ConnectTab_4.3.1.png)

APfMS will attempt to connect to your Microsoft Store Account (see red oval below); this may take a few seconds.  

![APfMS_ConnectTab_4.3.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_ConnectTab_4.3.2.png)

A successful connection will cause APfMS to display a list of all your current Store apps (you should have at least one, the one you are updating with APfMS).  To see the list of current apps, click on the drop-down listbox labeled with the red arrow in the image below.

![APfMS_ConnectTab_4.3.3](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_ConnectTab_4.3.3.png)

Select the app you are updating to load its information and click on the “Pricing” tab (see red circle below).  

![APfMS_ConnectTab_4.3.4](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_ConnectTab_4.3.4.png)

## 4.4 Using APfMS – Pricing

If the “Pricing” tab’s elements (checkbox, radio-buttons, etc.) are grayed out as follows …

![APfMS_PricingTab_4.4](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.png)

...then go back to the “Connect” tab, make sure you are connected to your Microsoft Store account, and  select one of your currently-available Microsoft Store apps.

The Pricing tab has 5 ways to set your app’s price:

1. Leaving the existing pricing already defined for your app unchanged.
2. Setting one app price in your chosen currency.
3. Showing app price in each country’s currency using the slow-to-update Microsoft rates.
4. Showing app price in each country’s currency using the weekly updated market rates.
5. Showing app price in each country’s currency using the local “purchasing power parity” rates.

You select each of these 5 pricing options by choosing the element denoted by the red arrow with the number corresponding to the numbered descriptions in screenshot APfMS_PricingTab_1.1 above.

### 4.4.1 No Changes

Selecting the “No Changes,…” checkbox will cause APfMS to hide the other pricing options.  This choice will leave unchanged whatever pricing is already defined for your app.  This original pricing will be used for this new APfMS-mediated submission.  

![APfMS_PricingTab_4.4.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.1.png)

### 4.4.2 Base Price only

Selecting the “No – Just set Base Price only” radio button (see #1 the diagram below) lets you set one price for your app and has Microsoft assign the prices worldwide for each local currency where your app is sold.  This option hides the per-country/per-currency prices.  

Then choose your local country/currency (see #2 below), and a base price (see #3 below).  “Free” will make your app free everywhere.  Clicking on “Free” (#3 below) will give you a wide-ranging set of prices in your chosen currency.  Choose your price and that price will will be applied to every other country/currency supported by the Microsoft Store.  

If you want to actually see each Microsoft-assigned price for each country/currency select the “Apply Microsoft Rates” radio button (see the red circle in the diagram below).  

![APfMS_PricingTab_4.4.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.2.png)

*NOTE: Microsoft prices are assigned in “tiers” about US$0.10 apart.  This 10 cent USD inter-price gap will be reflected in the gaps between your chosen currency if it is different.* 
   
### 4.4.3 Microsoft Rates

Select “Apply Microsoft Rates” (see #1 below) to display the Microsoft exchange rate prices for each currency in which your app is sold.  

Next choose the currency (#2 below) and price for your app in that currency (#3 below).  If you press the “Refresh/Generate Pricing” button (#4 below) a list of per-currency prices will appear.  

*NOTE: Microsoft rates are presented only by currency, not country, to match the behavior of the Microsoft Store App Ingestion Web Portal.*

![APfMS_PricingTab_4.4.3.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.3.1.png)

*NOTE: These prices will be “0” or free unless your “Base Price” is greater than “0” (free).  If you initially generated “Free” prices the per-currency prices will be “0” (free) until you re-select the “Refresh/Generate Pricing” button (see red circle in the image below showing this erroneous intermediate state).  Remember to press the “Refresh/Generate Pricing” button (#1 below).*

![APfMS_PricingTab_4.4.3.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.3.2.png)

### 4.4.4 Exchange Rates

Selecting “Apply Exchange Rates” (see #1 below) to access APfMS’s public currency market exchange rates.  *These rates are updated weekly with each APfMS update.*  

*Many currencies are available under this option (see #2 below) that are not supported by the Microsoft Store.*  We have noticed less well traded or highly volatile currencies, like the Russian ruble and many smaller currencies, are only available through the public currency markets.

*NOTE: Microsoft rates are presented only by currency, not country, to match the behavior of the Microsoft Store App Ingestion Web Portal.* 

Please remember to “Refresh/Generate Pricing” after choosing your country/currency and price (see #3 below).

![APfMS_PricingTab_4.4.4](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.4.png)

### 4.4.5 Purchasing Power Parity Rates (PPP Rates)

“PPP Rates” are applied just as with “Microsoft Rates” and “Exchange Rates”.  First select the country (#1 below), and the price (#2 below).  Then press the “Refresh/Generate Prices” button (#3 below).

![APfMS_PricingTab_4.4.5.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_4.4.5.1.png)

The "Row State" (see 'red circle' below) values can be: 

    * A - Added new country price,
    * M - Modified a country's price, and 
    * D - Deleted a country's price.

![APfMS_PricingTab_4.4.5.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_PricingTab_2.8.png)

*NOTE: Microsoft rates are presented only by currency, not country, to match the behavior of the Microsoft Store App Ingestion Web Portal.  Also, both the Microsoft and Public market exchange rates must only be given by currency as some, like the Euro, are shared among several countries.  The PPP rates are only given by country and APfMS converts that selection for you to the correct currency behind-the-scenes.*

## 4.5 Using APfMS – Languages – Field Mapping

Multilingual apps are recommended first to users whose computers are configured for a language an app supports.  To translate apps we at F&CO use the automatic translation feature on Microsoft's [Multilingual Application Toolkit](https://docs.microsoft.com/en-us/windows/apps/design/globalizing/use-mat) (see option #3 in that documentation).  We highly recommend you translate your apps.  

Getting each language into the Microsoft Store web ingestion portal is *extremely* laborious.  APfMS makes the publication of multilingual apps as fast as one language.  Just upload one language during your required first *manual* publication of your app.  Then on all subsequent updates use APfMS to include all your remaining languages.  

Microsoft apps specify the text contents of their XAML display elements in XML-formatted \*.RESX or \*.RESW files.  For example, hi-IN (i.e. hindi lanuage with Indian culture) content files will appear in a directory 'hi-in\Resources.resw' file in your UWP project.  The Multilingual Application Toolkit will translate an app's default RESX/W file through a translation "helper" format called [XLF/XLIFF](https://en.wikipedia.org/wiki/XLIFF), into new RESX/RESW files for each desired language translation.

NOTE: **The text of your app's Store Posting should be multilingual to engage users not using your default langauge.  Adding the five (5) fields in section 4.5.2 below to an app's default RESX/RESW file, and creating translated RESX/RESW files will allow APfMS to upload a mutltilingual Store Posting for your app.  See section 4.5.2 below.**

Building your app in Visual Studio converts your app's XLF file(s) into the the RESX/RESW file(s) that your app uses for each display element's content.  Whether your project depends on RESX or RESW doesn't affect APfMS which automatically uses the file type used by your project.  If your app has translations in multiple XLF files then building with Visual Studio will produce a matching RESX/RESW file for each language's XLF file.  

### 4.5.1 Required and Optional RESX/RESW File Fields

APfMS searches each per-language RESX/RESW file for a few required and many optional fields for these Microsoft Store entries.  **These entries needed to publish in the Microsoft Store must appear in your original XLF file with the prefix "Publish_".**  For example, the required Microsoft Store "Description" text must appear in your XLF file as "Publish_Description".  See the Required and Optional tables below for the full list of Microsoft Store entries that APfMS will read and display for you in this "Languages - Fields Mapping" tab.  

Elements lacking a matching RESX/RESW entry will appear blank.

### 4.5.2 Required APfMS Entries and associated RESX/RESW Fields

APfMS Entry Text                     | RESX/RESW Field Name
:---------------------------------- | :--------------------
1 Description                       | Publish_Description
2 Release Notes                     | Publish_ReleaseNotes
5 SupportContactInfo                | Publish_SupportContactInfo
6 PrivacyPolicyUrl                  | Publish_PrivacyPolicyUrl
9 Website                           | Publish_Website

### 4.5.3 Optional APfMS Entries and associated RESX/RESW Fields

APfMS Entry Text                     | RESX/RESW Field Name
:---------------------------------- | :--------------------
3 ShortDescription                  | Publish_ShortDescription
8 AdditionalLicenseTerms            | Publish_AdditionalLicenseTerms
7 CopyrightTrademarkInformation     | Publish_CopyrightTrademarkInformation
4 DevStudio                         | Publish_DevStudio
10 ShortTitle                       | Publish_ShortTitle
11 SortTitle                        | Publish_SortTitle
12 VoiceTitle						| Publish_VoiceTitle
1 Keywords #1                       | Publish_SearchTerm1
2 Keywords #2                       | Publish_SearchTerm2
3 Keywords #3                       | Publish_SearchTerm3
4 Keywords #4                       | Publish_SearchTerm4
5 Keywords #5                       | Publish_SearchTerm5
6 Keywords #6                       | Publish_SearchTerm6
7 Keywords #7                       | Publish_SearchTerm7
1 Product Features #1               | Publish_Feature1
2 Product Features #2               | Publish_Feature2
3 Product Features #3               | Publish_Feature3
4 Product Features #4               | Publish_Feature4
5 Product Features #5               | Publish_Feature5
6 Product Features #6               | Publish_Feature6
7 Product Features #7               | Publish_Feature7
8 Product Features #8               | Publish_Feature8
9 Product Features #9               | Publish_Feature9
10 Product Features #10             | Publish_Feature10
11 Product Features #11             | Publish_Feature11
12 Product Features #12             | Publish_Feature12
13 Product Features #13             | Publish_Feature13
14 Product Features #14             | Publish_Feature14
15 Product Features #15             | Publish_Feature15
16 Product Features #16             | Publish_Feature16
17 Product Features #17             | Publish_Feature17
18 Product Features #18             | Publish_Feature18
19 Product Features #19             | Publish_Feature19
20 Product Features #20             | Publish_Feature20
1 Minimum Hardware #1               | Publish_MinimumHardwareReq1
2 Minimum Hardware #2               | Publish_MinimumHardwareReq2
3 Minimum Hardware #3               | Publish_MinimumHardwareReq3
4 Minimum Hardware #4               | Publish_MinimumHardwareReq4
5 Minimum Hardware #5               | Publish_MinimumHardwareReq5
6 Minimum Hardware #6               | Publish_MinimumHardwareReq6
7 Minimum Hardware #7               | Publish_MinimumHardwareReq7
8 Minimum Hardware #8               | Publish_MinimumHardwareReq8
9 Minimum Hardware #9               | Publish_MinimumHardwareReq9
10 Minimum Hardware #10             | Publish_MinimumHardwareReq10
11 Minimum Hardware #11             | Publish_MinimumHardwareReq11
1 Recommended Hardware #1           | Publish_RecommendedHardwareReq1
2 Recommended Hardware #2           | Publish_RecommendedHardwareReq2
3 Recommended Hardware #3           | Publish_RecommendedHardwareReq3
4 Recommended Hardware #4           | Publish_RecommendedHardwareReq4
5 Recommended Hardware #5           | Publish_RecommendedHardwareReq5
6 Recommended Hardware #6           | Publish_RecommendedHardwareReq6
7 Recommended Hardware #7           | Publish_RecommendedHardwareReq7
8 Recommended Hardware #8           | Publish_RecommendedHardwareReq8
9 Recommended Hardware #9           | Publish_RecommendedHardwareReq9
10 Recommended Hardware #10         | Publish_RecommendedHardwareReq10
11 Recommended Hardware #11         | Publish_RecommendedHardwareReq11

### 4.5.3 Step-by-step through "Languages - Fields Mapping"

The “Languages – Field Mapping” tab offers two options.  One option is to check “No Changes” (see #1 below) and the other is pressing the button “Select folder containing .resx file(s)…” (see #2 below).  

![APfMS_LanguagesFieldsMappingTab_4.5.3.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesFieldsMappingTab_4.5.3.1.png)

Checking “No Changes” (#1 below) hides the button associated with the second option.  When “No Changes” is checked, the web portal fields (e.g. app names, website URLs, keywords, etc.) are reused.  

![APfMS_LanguagesFieldsMappingTab_4.5.3.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesFieldsMappingTab_4.5.3.2.png)

Pressing the button “Select folder containing .resx file(s)…” causes a folder-selection dialog box to appear.  Navigate in your app's source tree to the parent folder having all the language folders (e.g. en-US), holding the per-language RESX/RESW files used in your app.  

The diagram below shows a case where the per-language folders have be pulled together in their own special folder; you may not need to do this.  Now select the folder holding the per-language folders (#1 below).  

*NOTE: part of the file path for our example application is obscured to avoid confusion.* 

![APfMS_LanguagesFieldsMappingTab_4.5.3.3](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesFieldsMappingTab_4.5.3.3.png)

Upon selecting the folder containing the per-language RESX files (See #1 below), APfMS reads the contents of these per-language RESX/RESW files.  The screenshot below shows the Arabic RESX/RESW entries (#2 below) that have been defined displayed in light blue under their matching entries.  APfMS will choose as an example for display the alphabetically first language defined; here that is Arabic in an *.ar-SA.resx file.  

The drop-down listboxes (See #3 below) on this tab display the RESX/RESW field mappings that can be assigned automatically.  For example, APfMS will attempt to map "2 ReleaseNotes" to "Publish_ReleaseNotes".  If the mapping does not exist, as in "1 Keywords #1", then the drop-down listbox to right shows the expected term; in this case "Publish_SearchTerm1".  See the Required and Optional tables above for the RESX/RESW field mappings APfMS expects. 

*NOTE: It may be that your app cannot use the default "Publish_" RESX/RESW field name prefix.  If this is the case you can type your desired field name prefix in the "Filter drowdown starting with text" textbox (see #4 below).*

![APfMS_LanguagesFieldsMappingTab_4.5.3.4](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesFieldsMappingTab_4.5.3.4.png)

The content of these mapped RESX/RESW fields are collected, formatted into a JSON file which defines your app, and the read RESX/RESW entries are displayed in the matching fields in this tab (again refer to the Required and Optional mapping tables above).  When you get to the “Update to Store” tab, this JSON will be uploaded along with your application binary.  

You will see portions of the JSON content exchanged with the Store API on the "Update to Store" tab during upload.  Some of the field names may be similiar but changed from the "Languages - Fields Mapping" tab for clarity when creating distinct fields in the RESX/RESW files.  

## 4.6 Using APfMS – Languages – Images and Application

The Microsoft Store requires only two more items for a minimal upload:

*	at least one screenshot (maximum of ten (10)) and
*	one of a MSIX, MSIXBUNDLE, MSIXUPLOAD, APPX, APPXBUNDLE, APPXUPLOAD or XAP binary.
	
APfMS will auto-search files with the names given below and will ignore the rest.  To be uploaded by APfMS the image files *must* have the names, dimensions, type and size limits noted here:

    • Eg. DesktopScreenShot-1, DesktopScreenShot-2 Upto 10 maximum. 
        ◦ 1366 x 768 pixels or larger recommended.
        ◦ Accepted file types: .png.
        ◦ Less than 50 MB
    • Eg. MobileScreenShot-1, MobileScreenShot-2 Upto 10 maximum. 
        ◦ 1080 x 1920, 1920 x 1080, 768 x 1280, 1280 x 768, 720 x 1280, 1280 x 720, 800 x 480 or 480 x 800 pixels
        ◦ Max upload 10 files
        ◦ Landscape or portrait. Accepted file types: .png
        ◦ Less than 50 MB
    • Eg. XboxScreenShot-1, XboxScreenShot-2 Upto 10 maximum 
        ◦ 3840 x 2160 pixels or smaller
        ◦ 1920 x 1080 pixels or larger
        ◦ Max upload 10 files
        ◦ Landscape or portrait, Accepted file types: .png
        ◦ Less than 50 MB
    • Eg. HolographicScreenShot-1, HolographicScreenShot-2 Upto 10 maximum 
        ◦ 1268 x 720 pixels or larger
        ◦ Max upload 10 files
        ◦ Landscape or portrait. Accepted file types: .png
        ◦ Less than 50 MB
    • Store logos  
        ◦ eg. StoreLogoPosterArt.png
            ▪ 9:16 Poster art 720 x 1080 or 1440 x 2160
        ◦ eg. StoreLogoBoxArt.png
            ▪ 1:1 Box art 1080 x 1080 or 2160 x 2160
        ◦ eg. StoreLogoAppTitleIcon.png
            ▪ 1:1 App tile icon !UA 300 x 300 px
    • Windows 10 and Xbox image 
        ◦ eg. Windows10SuperHero.png  
            ▪ 16:9 Super hero art 1920 x 1080 or 3840 x 2160
    • Xbox images 
        ◦ eg. XboxBrandedKey.png
            ▪ Branded key art 584 x 800
        ◦ eg. XBoxTitledHero.png
            ▪ Titled hero art 1920 x 1080
        ◦ eg. XBoxSquareArt.png
            ▪ Featured promotional square art 1080 x 1080
    • Holographic image 
        ◦ eg. Holographic2400x1200.png
            ▪ 2:1 2400 x 1200
    • Windows 8.x and/or Windows Phone 8.x images 
        ◦ eg. Windows8358x358.png
            ▪ 1:1 358 x 358
        ◦ eg. Windows81000x800.png
            ▪ 5:4 1000 x 800
        ◦ eg. Windows8414x180.png
            ▪ 414 x 180

APfMS needs these files in one folder together.  Use the folder picker opened with the "Browse..." button (see #1 below) to select this folder and load the image file(s) and application binary.  The "Item Type" (see #2 below) and "File Name" (see #3 below) columns are blank until APfMS finds the files needed.  

![APfMS_LanguagesImagesAndApplicationTab_4.6.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesImagesAndApplicationTab_4.6.1.png)

The files found in the selected folder that do not match the required naming pattern will show in the "Item Type" column as "Ignored" (see #1 below) next to the "File Name" (see #2 below).

![APfMS_LanguagesImagesAndApplicationTab_4.6.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesImagesAndApplicationTab_4.6.2.png)

Those files that match one of the required types: DesktopScreenShot, MobileScreenShot, XboxScreenShot, and HolographicScreenShot.  

![APfMS_LanguagesImagesAndApplicationTab_4.6.3](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_LanguagesImagesAndApplicationTab_4.6.3.png)

You are done with all prerequsites and you are ready to use the "Upload" tab to complete your submission.  

## 4.7 Update to Store

Uploading the app is easy now that APfMS has its: price, language and store translationed text, images, and binary.  Finally, just click "Update to Store" (see below).  No further action is required until upload either succeeds or fails.  This final step usually requires about 40 to 50 minutes as the API checks the uploaded data.  

*NOTE: the following screenshots are taken from an actual upload containing sensitive information which are covered with "red rectangles."  Do not publicly share screenshots of your "Update to Store" tab.*

![APfMS_UpdateToStoreTab_4.7.1](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.1.png)

Immediately, APfMS will begin pulling together the app's information for upload.  The upload steps taken by APfMS will appear from bottom-to-top in the box under the "Update to Store" button (see below).

![APfMS_UpdateToStoreTab_4.7.2](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.2.png)

After a couple of minutes APfMS will begin "Uploading Package ..." (see below).  

![APfMS_UpdateToStoreTab_4.7.3](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.3.png)

A few more minutes and the app upload will complete and the Microsoft Store will begin validating the upload (see below).

![APfMS_UpdateToStoreTab_4.7.4](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.4.png)

Every minute, APfMS will check the status of your upload using the API (see below).  

![APfMS_UpdateToStoreTab_4.7.5](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.5.png)

When the upload process completes (see "Step 28" in the image below), the success or fail status will be reported in the JSON comprising step 27.  This JSON from the Store API is exactly the contents returned by the Store API and should be carefully examined for errors.  These errors need to be resolved before the Store API (or the web portal), can ingest this app.  *NOTE: we have found that __warnings__ can be ignored.*  

In the screenshot below we show 4 errors being reported:

1.	the package name *in the binary file* must match the name previously reserved on the Microsoft Store,
2.	this error is also caused by the reserved Store name not matching the name in the uploaded binary,
3.	again a filename mismatch with the Portal, and
4.	a warning, which can be ignored, here alerting of a change to the API.  

![APfMS_UpdateToStoreTab_4.7.6](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_4.7.6.png)

Whether or not the app upload is successful, the Microsoft Partner Center will show in the portal screen for the app that the submission as "In progress via API..." (see #1 below).  

![APfMS_UpdateToStoreTab_4.7.7](/AppPublisherForMicrosoftStore/Assets/HOWTO/APfMS_UpdateToStoreTab_5.7.png)

*NOTE: You will see portions of the JSON content exchanged with the Store API on the "Update to Store" tab during upload.  Some of the field names may be similiar but changed from the "Languages - Fields Mapping" tab for clarity when creating distinct fields in the RESX/RESW files.*

# 5 Errors

Early in an upload, to save time, APfMS tries to catch errors that would cause the Store to reject an app.  If the image files do not have the correct dimensions, file size, type, or there is not at least 1 screenshot then APfMS terminates upload with an alert.  The same happens if there is no application binary with the correct extension.  

Sometimes the Store Web Portal changes its app ingestion requirements.  For example, if the "Age Ratings" changes then step #33, "Update to Store", will report "Validation error: InvalidMicrosoftAgeRating."  Usually in all these cases the solution is to open the Web Portal for your app, navigate to the in-progress submission, and complete the form that has mostly been filled out by APfMS.  

Once all errors are resolved, you can "submit" the app within the portal.  Any further errors should only be due to Store validation requirements.  

If you have problems and you think APfMS is the cause, please contact us (see the "Support" entry at the top of this document).  

If your problems are with the Microsoft Store's App Ingestion process you are welcome to contact F&CO, but we are likely to direct you to Microsoft Store Support (see "Microsoft Store Support" at the top of this document).  
