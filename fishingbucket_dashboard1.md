# **FishingBucket Dashboard** {#fishingbucket-dashboard}

[FishingBucket Dashboard](#fishingbucket-dashboard)

[Overview](#overview)

[Proxies](#proxies)

[Adding proxies](#adding-proxies)

[Equivalent Commands](#equivalent-commands)

[Basic Information](#basic-information)

[ID](#id)

[Name](#name)

[Equivalent Commands](#equivalent-commands-1)

[Nickname](#nickname)

[Equivalent Commands](#equivalent-commands-2)

[Pronouns](#pronouns)

[Equivalent Commands](#equivalent-commands-3)

[Avatar](#avatar)

[Equivalent Commands](#equivalent-commands-4)

[Metadata](#metadata)

[Triggers, Tags, and Forms](#triggers,-tags,-and-forms)

[Triggers](#triggers)

[Equivalent Commands](#equivalent-commands-5)

[Tags](#tags)

[Equivalent Commands](#equivalent-commands-6)

[Forms](#forms)

[Equivalent Commands](#equivalent-commands-7)

[Proxy Description](#proxy-description)

[Equivalent Commands](#equivalent-commands-8)

[Tags](#tags-1)

[Equivalent Commands](#equivalent-commands-9)

[Basic Information](#basic-information-1)

[ID](#id-1)

[Name](#name-1)

[Equivalent Commands](#equivalent-commands-10)

[Marker](#marker)

[Equivalent Commands](#equivalent-commands-11)

[Metadata](#metadata-1)

[Tag Description](#tag-description)

[Equivalent Commands](#equivalent-commands-12)

[Organization](#organization)

[Filter](#filter)

[Grouping](#grouping)

[Sort](#sort)

[Bot Exclusive Features](#bot-exclusive-features)

## 

## **Overview** {#overview}

The FishingBucket dashboard is the website in which you may create and alter your tags and proxies. Although limited in what it may do as compared to using the bot's commands, the dashboard still fulfills basic editing needs.  

When there are unsaved changes on the dashboard, the yellow-orange save button will appear as “\*Save” instead of “Save”.

## **Proxies** {#proxies}

Proxies are the way in which users can send their messages through a different profile, without having to switch their account.  They work by having FishingBucket read the messages in chat, and copying triggered messages as a webhook so that they get sent as your proxy- and additionally deleting the original message from the user.  

#### **Adding proxies** {#adding-proxies}

Proxies may be added by pressing the “+ Proxy” button that is purple with white text.  Proceeding that, you add all the below information that is relevant- excluding the ID which is assigned randomly to all proxies and tags.  When complete make sure to press the yellow-orange “Save” button, so that your information does not get lost.

##### **Equivalent Commands** {#equivalent-commands}

fish\!register \<name: string\>  \<trigger: template\>  
fb\!register \<name: string\> \<trigger: template\>  
pk;register \<name: string\> \<trigger: template\>  
@FishingBucket \<name: string\>  \<trigger: template\>

### **Basic Information** {#basic-information}

#### **ID** {#id}

A proxy’s ID is the hexadecimal number that is automatically assigned to each and every proxy and tag for FishingBucket.  All of them are unique so that if you have multiple proxies that use the same name, you may use the ID when searching for a specific one or using it in command sequences.  
In the proxy edit window there will be a purple button with white text that says “Copy ID: \[insert hexidecimal\]”, with your proxy’s unique ID.

#### **Name** {#name}

Your proxy’s name is what your proxy will be registered as, and how your proxy presents in communities using FishingBucket.  Fluxer allows for a maximum character limit of 32, and minimum of 1 for their nicknames and usernames; meaning that the total number of characters you can add and be displayed will be (32 \- \[character count of tag\]).  However, the dashboard does allow for 100+ characters to be in a name, as long as you recognize that the name will not display properly when sending proxied messages.  
To set a proxy’s name, type in the textbox set beside where you find the text “Name:”, which will be in the “Basic Information” drop category.

##### **Equivalent Commands** {#equivalent-commands-1}

fish\!set name \<proxy: proxy\> \<new name: string\>

#### **Nickname** {#nickname}

Your proxy’s nickname is how your proxy presents in communities using FishingBucket.  Fluxer allows for a maximum character limit of 32, and minimum of 1 for their nicknames and usernames; meaning that the total number of characters you can add and be displayed will be (32 \- \[character count of tag\]).  However, the dashboard does allow for 100+ characters to be in a name, as long as you recognize that the name will not display properly when sending proxied messages.  
To set a proxy’s nickname, type in the textbox set beside where you find the text “Nickname:”, which will be in the “Basic Information” drop category.

##### **Equivalent Commands** {#equivalent-commands-2}

fish\!set nickname \<proxy: proxy\> \[new nickname: string\]

#### **Pronouns** {#pronouns}

A proxy’s pronouns will be shown when you view the proxy in the dashboard in the “Basic Information” category, or when you use the command “fb\!info \[proxy\]”.  They do not display in proxied messages though.    
To set a proxy’s pronouns, type in the textbox set beside where you find the text “Pronouns:”, which will be in the “Basic Information” drop category.  If you would like the pronouns to be displayed in proxied messages, it is best to put them in a nickname.

##### **Equivalent Commands** {#equivalent-commands-3}

fish\!set pronouns \<proxy: proxy\> \[new pronoun: string\]  
fish\!set nickname \<proxy: proxy\> \[new nickname: string\]

#### **Avatar** {#avatar}

A proxy’s avatar is the avatar that appears in a proxied message.  While in Fluxer you may set an avatar for your proxies by sending the image file normally, or by using the image’s URL; in the dashboard you are only able to set them by using a URL as the site does not host the images.  Image hosting will be added in future updates to come though.  
To set a proxy’s avatar in the dashboard, you must first obtain the image’s URL.  Then, you will want to copy the URL into the text box in “Basic Information” located next to the text saying “Avatar:” and a circular icon representing what your chosen avatar will look like.  In the textbox there will also be a purple square with an arrow pointing out from the upper-right corner, when clicked it will open the full picture in its own tab.

##### **Equivalent Commands** {#equivalent-commands-4}

fish\!set avatar \<proxy: proxy\> \[url: url\]  
fish\!set avatar \<proxy: proxy\> (+ attached image in message)

#### **Metadata** {#metadata}

The proxy’s metadata is displayed at the bottom of the “Basic Information” category.  It displays the date of creation on the left side, and the amount of messages sent on the right side.

### **Triggers, Tags, and Forms** {#triggers,-tags,-and-forms}

#### **Triggers** {#triggers}

Triggers are the way in which you mark what messages are to be proxied, and what proxy to use.  It is best that you make every trigger unique as otherwise errors can occur, and the wrong proxy may be triggered.  You may also have multiple triggers for each proxy.  
To set triggers, you need to have the “Triggers, Tags, and Forms” category open, which will be located underneath “Basic Information”.  Automatically there will be a trigger set as “new\#: {}” which you change to whatever you want it to be- as long as {} is included in the beginning or end, to signify the text or attachment part of the message that you wish to be proxied.  To set more than one, press the purple button that says “+ Trigger”, which will be located below your existing triggers textbox.  To delete a trigger you may press the red “X” button in the textbox of any of them, although do be careful as there is no verification pop-up for this action.

##### **Equivalent Commands** {#equivalent-commands-5}

fish\!set triggers \<proxy: proxy\> \<mode: 'set' OR 'add' OR 'remove'\> \[trigger: template\]

#### **Tags**  {#tags}

Tags are the way in which you not only organize your proxies, but also include a tag (such as a system tag) in the name of a proxy when messaging.  To add them to your proxies you first have to create your tag(s).  After the process is complete, you may add them to your proxy by clicking the purple button labeled “Tags:” in the category “Triggers, Tags, and Forms” and selecting the tag you want from a drop-down menu.  You may add multiple tags, but it is important to note that as of writing, only the first one listed and bearing a tag marker will be displayed in a proxy’s name when messaging.  Additionally, you must add tags to each individual proxy manually as the dashboard features no option to mass-set tags.  To edit a tag click the purple button that has a square with what looks like a pencil located directly right of the tag box, and it will take you to the tag editing menu.  To remove a tag from your proxy, click the purple “X” button to the far right of the box for said tag.

##### **Equivalent Commands** {#equivalent-commands-6}

fish\!set tags \<proxy: proxy\> \<mode: 'add' OR 'remove'\> \<tags: proxy tag(s)\>

#### **Forms**  {#forms}

Forms, as of writing, exist as alternate avatars that you can set for specific proxies, without changing their primary avatar.  This will currently affect the proxy in all communities and channels.  To set a proxy’s forms in the dashboard, you must first obtain the image’s URL.  Then, press the purple button with white text that says “+ Form”.  You will want to copy the URL into the text box in the “Triggers, Tags, and Forms” category located under the text on the right saying “Forms:”.  In the textbox there will also be a purple square with an arrow pointing out from the upper-right corner, when clicked it will open the full picture in its own tab.  The textbox on the left side can be used to name specific forms.  If you wish to return a proxy’s avatar to its default, click the purple button with white text that says “Reset current form”.

##### **Equivalent Commands** {#equivalent-commands-7}

fish\!set forms \<proxy: proxy\> \<mode: 'set' OR 'add' OR 'remove'\> \[form: ( \<name: string\> \[avatar: url\] )\]

### **Proxy Description** {#proxy-description}

Underneath the categories labeled “Basic Information” and “Triggers, Tags, and Forms” you will find a textbox labeled “Description:”.  This is where you may insert descriptions for each of your proxies, which will be shown when using the command “fb\!info \[proxy\]”.  On the dash you may have as long of a description as you want, you can even set the *Bee Movie* script as your proxy’s description.  But on the Fluxer end, an embedded message’s description may only contain a maximum of 3,694 characters.  This makes the working character count for descriptions 3,694 characters.

##### **Equivalent Commands** {#equivalent-commands-8}

fish\!set description \<proxy: proxy\> \[new description: string\]

## **Tags**  {#tags-1}

Tags are the way in which you not only organize your proxies, but also include a tag (such as a system tag) in the name of a proxy when messaging.    
To create a new tag you must click the purple button to the right of the “+ Proxy” button, that says “+ Tag”.  Proceeding that, you add all the below information that is relevant- excluding the ID which is assigned randomly to all proxies and tags.  When complete make sure to press the yellow-orange “Save” button, so that your information does not get lost.

##### **Equivalent Commands** {#equivalent-commands-9}

fish\!set tags \<proxy: proxy\> \<mode: 'add' OR 'remove'\> \<tags: proxy tag(s)\>

### **Basic Information** {#basic-information-1}

#### **ID**  {#id-1}

A tag’s ID is the hexadecimal number that is automatically assigned to each and every proxy and tag for FishingBucket.  All of them are unique so that if you have multiple tags that use the same name, or have complex names, you may use the ID when searching for a specific one or using it in command sequences.  
In the tag edit window there will be a purple button with white text that says “Copy ID: \[insert hexidecimal\]”, with your tag’s unique ID.

#### **Name**  {#name-1}

Your tag’s name is what your new tag will be registered as.  This will not be bound by any character limit, only requiring a minimum of one character.  To set a tag’s name you will want to type in the textbox next to where it says “Name:” in the “Basic Information” category.

##### **Equivalent Commands** {#equivalent-commands-10}

fish\!tag set name \<tag: proxy tag\> \<name: string\>

#### **Marker**  {#marker}

Your tag marker will be what appears by a proxy’s name in a proxied message.  It is a general custom for people to keep their tag markers short, to allow for more name flexibility within the 32 character name limit that Fluxer has.  You do not need to have markers for all of your tags, you may choose which ones do and do not have them.  
To add a marker to your tag, type in the textbox next to where it says “Marker:” in the “Basic Information” category.  An example would be; “{} (TAG)” making the proxy’s name for messages appear as “name (TAG)”.

##### **Equivalent Commands** {#equivalent-commands-11}

fish\!tag set marker \<tag: proxy tag\> \[marker: template\]

#### **Metadata**  {#metadata-1}

A tag’s metadata includes only the date of creation.

### **Tag Description** {#tag-description}

Underneath the categories labeled “Basic Information” and “Triggers, Tags, and Forms” you will find a textbox labeled “Description:”.  This is where you may insert descriptions for each of your tags, which will be shown when using the command “fb\!info \[tag\]”.  On the dash you may have as long of a description as you want, you can even set the *Bee Movie* script as your tag’s description.  But on the Fluxer end, an embedded message’s description may only contain a maximum of 3,694 characters.  This makes the working character count for descriptions 3,694 characters.

##### **Equivalent Commands** {#equivalent-commands-12}

fish\!tag set description \<tag: proxy tag\> \[description: string\]

## **Organization** {#organization}

The FishingBucket dashboard automatically lists either proxies or tags, depending on whether you press the purple button for “Proxies” or “Tags”.  The list will display to the left side of the page, underneath the mentioned buttons above.  To the right side, above where you change your information, you will see three buttons in a row.  The left will resemble a funnel, the middle as three cubes stacked in a pyramid, and finally an arrow pointing downwards with horizontal lines to its right side.  These buttons represent the filtering, grouping, and sorting options respectively.

### **Filter**  {#filter}

To filter, you must click on the funnel shaped button.  From there a box saying “Filter proxies/tags” as its title will appear.  Underneath will be a blank box, in which you can click and a drop down menu will appear.  You will have the option to filter the proxies list by the following: ID, Name, Description, Avatar, Triggers, Messages Sent, Date Created, Nickname, Form Names, Current Form, Pronouns, and Tag IDs.  For filtering the tags list you have the options of: ID, Name, Description, Date Created, and Marker.    
Once an option is chosen, to the right you will see up to three boxes in a vertical column labeled, with the top one labeled as “Keep If:” which will always be an option.  Type in whatever you want to search for, like “z” if you want to filter by proxies that contain the letter “z”.

### **Grouping**  {#grouping}

When clicking the stacked cubes button, you open up the grouping options.  There you will see a drop down menu that you can press and select which method you want to see your proxies grouped by.  The options are: none, first tag, all tags, and first letter.

### **Sort** {#sort}

Pressing the button with an arrow pointing downwards with horizontal lines to its right side will lead you to the sorting menu.  You will see three drop down menus that are labeled “Sort By”, “Order By”, and “Place Unsaved IDs”.  The final one will only appear if you are sorting by ID.  These will determine how you want your lists to be sorted- “Sort By” being your criteria and “Order By” being the order in which you want them to be arranged.

## **Bot Exclusive Features** {#bot-exclusive-features}

* Import and Export of stored information.

* Community Commands.

* Proxy Logging.

* Privacy Settings.

* Linking and unlinking accounts to a single profile.

* Dice commands.

* Spotlighting proxies.

Last edit: Oct. 25, 2026

