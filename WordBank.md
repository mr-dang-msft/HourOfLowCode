# Hour of Low Code 2021: Make your own vocabulary app

It can be overwhelming to learn a new language or a new topic. If you had an app to keep track of high frequency words,&nbsp;new spelling words, or key vocabulary words, it could be more manageable to recall what they mean and how to use them.
In this session, you can learn how to create an app in Power Apps for saving words to a word bank. You can even translate them and add any additional details that can be helpful for studying.

## Table of contents

1. Getting started
2. Creating the basic app
    - Create a table
    - Add form controls
    - Insert more controls
3. Working with connectors
    - Add a connector
    - Configure controls
4. Writing a formula
    - Translate text
    - Text to speech
5. Summary

## Getting started

This project has the same requirements as previous projects:

- access to Microsoft Teams
- membership in a team
Please view the 'Getting started' section of the ['Create your own library app' project](https://aka.ms/houroflowcode/library) if you do not have a team. Then return to this tutorial to begin creating your app.


Step 1.

- Open Power Apps in Teams.
- Click the 'Start now' button in the top box of the screen.

[![A screenshot of the Power Apps portal in Teams. At the top are tabs for Home, Build, About. In the top area is a box on 'How to create an app for your team' which has a button for 'Start now' and 'Learn more' below that.](https://pahandsonlab.blob.core.windows.net/docsapp/d72cd495-c939-4655-91fb-0f1308277e66.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d72cd495-c939-4655-91fb-0f1308277e66.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

A prompt will appear where you can select the team where you want your apps to stay.

Step 2.

- Find and select the team where you want your app to belong.
- Click Create.

[![A screenshot of a prompt for "Create an app". It has a scrolling list for selecting a team, and a button for Create at the bottom.](https://pahandsonlab.blob.core.windows.net/docsapp/19b9a52a-1c20-4ef1-a636-3a8a622f952e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/19b9a52a-1c20-4ef1-a636-3a8a622f952e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 3.

- Name your app.
- Click Save.
This app will be about words, vocabulary, and translating, so choose something that is appropriate. You can still change the name of the app later.

[![A screenshot of a modal that appears for 'Name your app.' It has a field for inputting App name and a button for Save.](https://pahandsonlab.blob.core.windows.net/docsapp/175fa471-e3a5-4f00-92a4-7ff1417d8deb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/175fa471-e3a5-4f00-92a4-7ff1417d8deb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

## Creating the basic app

Translation apps do a good job of telling you want a word or phrase can mean, but they do not save that information. That is a limitation, and a problem you can solve. So this project will begin by creating a table where you can save your words that you've learned or encountered.

### Create a table


Step 4.

- From the left navigation of Power Apps Studio, click the cylinder icon for 'Data'. A Data pane will appear.
- Click 'Create new table'.

[![A screenshot of the Data pane on the left side of the Power Apps Studio. It is empty and shows a large button for 'Create new table'](https://pahandsonlab.blob.core.windows.net/docsapp/39100f8a-2e81-46fe-941a-64c4fb4c0687.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/39100f8a-2e81-46fe-941a-64c4fb4c0687.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 5.

- Name the table 'Word'. Its plural name will be automatically written.
Note: If there are multiple people making the same app in the same team, you can include your name ahead of the table name: "AdeleV Word".

[![A screenshot of a modal for 'Create a table. It includes a field for Table name and Plural table name. At the bottom are buttons for Create and Cancel.](https://pahandsonlab.blob.core.windows.net/docsapp/dee1b563-8dd3-4741-8651-4a7b07220aee.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/dee1b563-8dd3-4741-8651-4a7b07220aee.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The table will start with a 'Name' column. We will change that to 'Word' instead since it will be the column where we write new words.

Step 6.

- Click the Name column.
- From the options, click 'Edit column'.

[![A screenshot of the quick edit experience for editing a table. The Name column is selected and a menu appears below it.](https://pahandsonlab.blob.core.windows.net/docsapp/817d4502-f4d6-4bcf-b826-ae854835c68c.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/817d4502-f4d6-4bcf-b826-ae854835c68c.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 7.

- Change the 'Name' column to 'Word'.
- Change the 'Max length' to 500 since you might want to translate sentences.

[![A screenshot of a modal for 'Edit column.' It has fields for Name, Type, and Max length. At the bottom are buttons for Save and Cancel.](https://pahandsonlab.blob.core.windows.net/docsapp/6b1456f4-a0c3-4d6f-8bff-aeaf440a6b53.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/6b1456f4-a0c3-4d6f-8bff-aeaf440a6b53.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Now you can create two more columns:

- Meaning: the meaning of the word when it is translated
- Language: the language that the word belonged to

Step 8.

To create the Meaning column:

- Click the + icon beside the Word column. This opens up options to add a new column.
- Change the name of the new column to 'Meaning'.
- Click Advanced options.
- Change the 'Max length' to 500 so that translations can be as long as the original word or phrase.
- Click Create.

To create the Language column:

- Click the + icon beside the Meaning column.
- Name the column 'Language'.
- Click Create.

[![A screenshot of the quick data editor in Power Apps studio. It shows the modal for adding a new text column for Meaning.](https://pahandsonlab.blob.core.windows.net/docsapp/c319feac-0fdb-4490-978d-872d31204858.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/c319feac-0fdb-4490-978d-872d31204858.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 9.

- Click Done at the bottom right when you're done adding columns.

🏆 The three basic columns for describing our words are created. You can always go back to edit the table to add even more columns.

[![A screenshot of the full screen of the quick table editor in Power Apps Studio. There are three columns total: Word, Meaning, and Language. At the bottom right is a button for 'Close'.](https://pahandsonlab.blob.core.windows.net/docsapp/dd858e78-d102-4d6e-b1a5-c98ba8740505.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/dd858e78-d102-4d6e-b1a5-c98ba8740505.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

### Add form controls

The table for saving words you are studying is ready. Next you need to add that table in your app so that you can add new words and translate them.

Step 10.

- In the middle of the blank screen, click 'With data'. This will bring up options for 'Select a data source'.
- Click your table of words that you created earlier.

[![A screenshot of a blank canvas with the option for 'Start this screen' 'with data' selected. It shows a modal for 'Select a data source' with the table for Words highlighted.](https://pahandsonlab.blob.core.windows.net/docsapp/a99d906d-1ff1-4766-93c1-158843f87823.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/a99d906d-1ff1-4766-93c1-158843f87823.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Power Apps will create several controls for you so that you do not have to add them one by one. This includes a form for adding, editing, and viewing data. Next, you can change the look and feel of your form. It is easier to view the app on a small screen if there is only one field per row instead of 3.

Step 11.

- Click the blank white space below the fields in the form. A blue border will appear around the entire form to show that it is selected.
- From the properties panel on the right side of the screen, change the Columns to 1 (it starts at 3).

[![](https://pahandsonlab.blob.core.windows.net/docsapp/85a2037c-1718-4597-8729-cc4737db9798.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/85a2037c-1718-4597-8729-cc4737db9798.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 12.

- Save your app. Click Save at the top right of the Power Apps Studio.

🏆 At this point, you have a working app. It does not have all the features we will put in, but it works.

### Insert more controls

The basic app is ready, but in order to translate words, you need to have more controls to tell the app what language you want it to translate to and from and more. This section will show you how to get started adding a place where you can keep those controls.

Step 13.

- Select the form again. A blue border will appear around it when the entire form is selected.
- From the properties pane on the right, click 'Edit fields'. That will reveal the Fields pane. This is where you can show or remove columns in the form.
- From the top of the Fields pane, click the ellipsis (3-dot icon). Then click 'Add a custom card'. This inserts a blank card in the form.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/061b902d-87ea-4b05-b00f-f149b3dffc35.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/061b902d-87ea-4b05-b00f-f149b3dffc35.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The container control is useful for organizing and spacing out controls very easily. You will use one in this app for keeping the controls for translation tidy.

Step 14.

- From the left navigation of Power Apps, click the + icon for the Insert pane.
- Search for container at the top of the insert pane.
- With the blank card in the form still selected, click 'Vertical container' from the Insert pane. This will insert a container into the card.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/edfc583c-fbab-4043-9421-5b9dda8ea839.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/edfc583c-fbab-4043-9421-5b9dda8ea839.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

You will insert many controls into this container, so you will need to set it up so that it spaces them out.

Step 15.

- Select the container (if it is not selected.
- From the properties pane on the right, Change the Gap property to 24. Any controls you insert will be spaced 24 pixels apart now.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/6fdcfb0d-34f6-4ddd-829e-aee32005d595.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/6fdcfb0d-34f6-4ddd-829e-aee32005d595.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Next, you will create the control for selecting languages. You will only need to setup one of these, then you can copy and paste it so that you have two:

- a combo box for the language that you are translating from
- a combo box for the language that you are translating to

Step 16.

- Select the container you made in the previous step (if it is not already selected).
- From the Insert pane, search for and add a combo box.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/2e3f6713-3e6d-4c75-95fa-1765bcbe60bb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/2e3f6713-3e6d-4c75-95fa-1765bcbe60bb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

A combo box is a special kind of drop down menu that allows you to search. This combo box will be showing languages, and since there are many of them, you will want to be able to search for the right one.

Step 17.

- Select the combo box you just created (if it is not already selected).
- From the properties pane, turn on 'Allow searching'.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/8b55cdb5-3513-4703-98d0-af6c958f5b28.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/8b55cdb5-3513-4703-98d0-af6c958f5b28.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

## Working with connectors

So far you have created a place to save new words and inserted some of the controls needed to help with translation. In order to do the actual translation, you need to use a service that can translate what it is given. That kind of service is called a 'connector'. There are many different kinds of connectors that do different actions such as sending email, scheduling events. You will be using the Microsoft Translator connector to translate words.


Step 18.

- From the left navigation of Power Apps, click the cylinder icon. This will show the Data pane.
- Click '+ Add data'.
- Search for 'translator'. There will be two options: 'Microsoft Translator' and 'Microsoft Translator V2'
- Click 'Microsoft Translator'.
Note the 'V2' means 'Version 2'. It is always best to use the latest version of a connector. For your purposes though, the first version is able to do something extra you will need.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/ec6fc024-fdc1-41ed-aa4c-53c7017ea469.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/ec6fc024-fdc1-41ed-aa4c-53c7017ea469.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

A pane will appear on the right side that asks for a subscription key. You do not have one, so you can keep it blank and use the free version.

Step 19.

- In the pane that appears, keep the 'Subscription Key' blank.
- Click Connect at the bottom of the pane.

🏆 You have successfully added a connector to your app. Check out some of the other connectors that are available and find out which ones you want to try in the future.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/721bea33-4d2f-41fd-8faf-007a32e69769.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/721bea33-4d2f-41fd-8faf-007a32e69769.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

### Configure controls

Now that you have added a connector, you can start using its abilities in formulas. This is where you will be writing some of your first code. There will be many guides in Power Apps to help you. The steps in this section will show you patterns so that you can be successful on your own as you explore other connectors.
The Microsoft Translator connector can get you a list of all the languages that it supports. You can use that list in the combo box you inserted.

Step 20.

- Select the combo box you inserted earlier.
- Make sure the property drop down menu at the top left of the Power Apps studio has the 'Items' property selected. (It should be by default.)
- In the formula bar at the top (where you see 'fx'), type 'languages'. This will search for any functions that contain the word 'languages'. The option for 'MicrosoftTranslator.Languages' will be the first option.
- Click 'MicrosoftTranslator.Languages'. That is the function that can get you a list of supported languages.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/83fa2841-c32c-4b94-8a47-1578ab2d8267.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/83fa2841-c32c-4b94-8a47-1578ab2d8267.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

You just used auto-complete to help find the right function. In Power Apps, it's called Intellisense and it is there to help you so that you do not need to memorize everything.
The MicrosoftTranslator.Languages function just needs a closing ')' though.

Step 21.

- After you select&nbsp;MicrosoftTranslator.Languages, it appears with an open parenthesis:*MicrosoftTranslator.Languages(*
- Add a closing parenthesis ')':*MicrosoftTranslator.Languages()*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/835de2b6-7a6a-4cf8-9e1c-a9315a0abe9a.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/835de2b6-7a6a-4cf8-9e1c-a9315a0abe9a.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The combo box now has access to the list of languages. You have a choice of which detail to show when someone clicks the combo box: the 2-letter code for the language or the name of the language. It makes more sense this time to show the name of the language.

Step 22.

- Select the combo box (if it is not already selected).
- From the properties pane on the right, click 'Edit' beside 'Fields'. This will open a Data pane.
- From the Data pane, click '+ Add field' and select Name.
- Click Add.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/5e858d3e-7274-4d77-8b19-1e3b502fb417.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/5e858d3e-7274-4d77-8b19-1e3b502fb417.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Most of the settings needed for the combo box are ready, so it is time to make a copy of it. Copy and paste works exactly as it does in other programs you use. You can use keyboard shortcuts, right-click options, or even the tree view.

Step 23.

- Select the combo box (if it is not already selected).
- Press Ctrl+C (Cmd+C on a Mac).
- With the combo box or container still selected, press Ctrl+V (Cmd+V on a Mac). This will paste the combo box in the same container.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/af16f5a6-a9e4-4da6-a00c-14af7364f2b7.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/af16f5a6-a9e4-4da6-a00c-14af7364f2b7.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Before proceeding to the next section write any formulas, you should rename controls that will be used in the formulas. This makes it much easier to keep track of what's happening in the formula.

Step 24.
Rename the field where a new word is entered:

- Click the card in the form for Word.
- Click the text box in the card. It will likely be called something similar to DataCardValue1.
- At the top of the properties pane on the right, click the name of the control and rename it to 'MyWord'. So anywhere that mentions MyWord.Value is the text that is typed into that box.
Rename the combo boxes:

- Select the top combo box. This will be for selecting the language to translate *from*.
- At the top of the properties pane, click the name of the combo box and rename it to 'LanguageFrom'.
- Select the bottom combo box. This will be for selecting the language to translate *to*.
- At the top of the properties pane, click the name of the combo box and rename it to 'LanguageTo'.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/25b41b55-04bb-47bd-b520-5bf2a8e70a80.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/25b41b55-04bb-47bd-b520-5bf2a8e70a80.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 In this section, you added a connector. Then you used that connector to show a list of languages in combo boxes. You renamed controls that will be used in formulas.

## Writing a formula

The Microsoft Translator connector is able to do many actions. So far you have used it to get a list of languages. This section will show you how to translate and even turn text into speech that you can listen to.

### Translate text

You will use a button that can be clicked to do the translation.

Step 25.

- Select the container that you created earlier.
- Click the + icon on the left navigation to open the Insert pane.
- Click Button to insert a button in the container. It will appear below the combo boxes.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/02e69a68-f838-4f92-8cc7-4bcfcdd0c61e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/02e69a68-f838-4f92-8cc7-4bcfcdd0c61e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Each control has many properties--its width, height, color, and more. A button has a special property called OnSelect that lets it perform actions when it is selected (clicked). Go to that property to give it some actions.

Step 26.

- Select the button (if it is not already selected).
- From the top left of the Power Apps Studio, click the property drop down menu. This will show the different properties available to the button.
- Scroll and select OnSelect.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/d39bfecb-fc79-4eb7-acdd-4bdc0afdd4b8.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d39bfecb-fc79-4eb7-acdd-4bdc0afdd4b8.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Pay close attention as you write your first formula. Intellisense will be back to help you again.

Step 27.

- With the OnSelect property chosen, click into the formula bar and erase its contents: 'false'.
- Type in 'translate' to let the Intellisense (auto-complete) find the translate function for you.
- Select 'MicrosoftTranslator.Translate'.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/2f1a84f6-1a52-49e2-98c4-cf41ced6a27e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/2f1a84f6-1a52-49e2-98c4-cf41ced6a27e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The translate function needs some help so that it knows what to do:

- What should it translate?
- What language should it translate to?
- What language is it translating from?
These are called parameters, and you will write them in the order that it asks. Notice that above the formula bar is some help text that shows what details to enter next. For instance, after 'MicrosoftTranslator.Translate(', the first parameter is the 'query': the text to translate.

Step 28.

- After 'MicrosoftTranslator.Translate(', type MyWord.Value*MicrosoftTranslator.Translate(MyWord.Value*
- Place a comma (,) after that to show what detail to enter next. Your region might use a semi-colon instead (;).*MicrosoftTranslator.Translate(MyWord.Value,*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/d56307da-64bd-4b0a-b5ed-76a32731a252.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d56307da-64bd-4b0a-b5ed-76a32731a252.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The next parameter to enter is what language to translate to. We can reference it through the LanguageTo combo box that we renamed earlier. This time, we do not want the name of the language, but its code. We can reference the code of the language that is selected in the combo box by: LanguageTo.Selected.Code. The dots let you reference properties of the control.

Step 29.

- Type in&nbsp;LanguageTo.Selected.Code as the second parameter:*MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code*
- Place a comma (,) after that to show what detail to enter next. Your region might use a semi-colon instead (;).*MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/45931ee5-8fac-4e4d-8624-49aac5e01efd.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/45931ee5-8fac-4e4d-8624-49aac5e01efd.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The next parameters are actually optional. Microsoft Translator is smart enough to try to figure out what language a word came from. But some words could have different meanings when they have the same spelling in other languages. The Intellisense shows the optional parameters in the selection below the formula bar after you placed the comma or semi-colon.

Step 30.

- Select '{languageFrom:' from the options below the formula bar.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/3ddeae7b-0dc0-4868-abcc-0b5876c3657d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/3ddeae7b-0dc0-4868-abcc-0b5876c3657d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Fill in the combo box for the language you will be translating from and then close the curly brace '}' and parenthesis ')'.

Step 31.

- Beside '{languageFrom:', type in LanguageFrom.Selected.Code:*MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,{languageFrom: LanguageFrom.Selected.Code*
- Close the curly brace and parenthesis:*MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,{languageFrom: LanguageFrom.Selected.Code})*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/0edf1e55-08cd-48f8-8b4c-47dcafcf66f1.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/0edf1e55-08cd-48f8-8b4c-47dcafcf66f1.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The formula you've written doesn't work yet. Clicking the button would activate Microsoft Translator, but you need to tell Power Apps where to put the translation. To do that, you can keep the translation in a 'variable', which can hold information in an app. You will use the Set() function to create that variable.

Step 32.

- Type in 'Set(' at the start of the formula.
- Type in the name of the variable; you can use 'Meaning' for this tutorial. You can name variables anything you want. They simply hold information and their names are completely made up.
- Insert another closed parenthesis ')' at the end so Set() wraps around the entire formula:*Set(Meaning,MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,{languageFrom: LanguageFrom.Selected.Code}))*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/76e6dc1d-bdda-4b97-b962-d39f998ae68b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/76e6dc1d-bdda-4b97-b962-d39f998ae68b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The button can now do the translation, and it will be kept in the variable. But in order to show that translation somewhere, you need to put it in a text box somewhere. In your case, you will put that translation in the column in the table that you created for 'Meaning'.

Step 33.

- Select the card in the form for 'Meaning'. A blue border will appear around the card when it's selected.
- From the properties pane on the right, click 'Unlock to change properties'. You can make changes to the card now.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/34499e0e-8a03-46d2-bd7d-d00f533b8483.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/34499e0e-8a03-46d2-bd7d-d00f533b8483.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)


Step 34.

- Keep the selection on the card in the form for Meaning.
- From the properties drop down menu at the top left, scroll down and choose the Default property.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/0a7d6077-13bf-4285-9d56-7fc2dd49413b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/0a7d6077-13bf-4285-9d56-7fc2dd49413b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

You will change what will appear in the text box for Meaning by changing its Default property. There you will show the variable. The Coalesce() function tells the app to try the first parameter. If that is blank (there is no translation), then it will try the second one, and so on.

Step 35.

- In the formula bar, change the Default property to:*Coalesce(Meaning, ThisItem.Meaning)*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/20d9f916-2180-43c0-95d0-1b99583f781b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/20d9f916-2180-43c0-95d0-1b99583f781b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Now you're getting more out of creating the app since it is automatically putting in the details into your form. You will need to use a similar formula so that the Language is automatically filled in.

Step 36.

- Select the card in the form for 'Language'.
- From the properties pane on the right, click the Advanced tab and then click 'Unlock to change properties'.
- From the properties drop down menu at the top left, choose the Default property.
- Change the Default property to:*Coalesce(LanguageFrom.Selected.Name,ThisItem.Language)*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/0b3d0d12-d4d7-4175-a112-42cc4359af10.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/0b3d0d12-d4d7-4175-a112-42cc4359af10.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 If you were to preview the app and test it, you could translate the word that is typed into the top box and its translation would appear in the box for 'Meaning'.

### Text to speech

The finishing touch of the app will involve changing the text into sound. You can include more than one action in a button by using a semi-colon (;). You may be in a region where you will use two semi-colons (;;) to separate actions.

Step 37.

- Select the button.
- Go to the button's OnSelect property from the property drop down menu at the top left.
- At the end of the formula, type a semi-colon (or two-semi-colons).*Set(Meaning,MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,{languageFrom: LanguageFrom.Selected.Code}));*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/7e84b2b1-8174-43f6-b308-ff0ea0e01c62.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/7e84b2b1-8174-43f6-b308-ff0ea0e01c62.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

You will use the text to speech ability of Microsoft Translator in a second action after translating. You can keep the sound in a variable called 'Audio'.

Step 38.

- Press Enter at the end of the formula to go to the next line in the formula bar.
- Start by creating a new variable called Audio:*Set(Audio,*
- Type in 'textto' so that Intellisense can search for the MicrosoftTranslator.TextToSpeech function.
- Click 'MicrosoftTranslator.TextToSpeech':*Set(Audio,MicrosoftTranslator.TextToSpeech(*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/c72badca-e2e8-4c73-b7f2-6550e863fa4b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/c72badca-e2e8-4c73-b7f2-6550e863fa4b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Fill out the details that the function asks for. To create a sound file, it needs the text and what language it is in.

Step 39.

- Use 'MyWord.Value' as the first parameter. That is the text that will be turned into sound.
- Use 'LanguageFrom.Selected.Code' as the second parameter. That is the language that the word or phrase is in.
- The final formula should look like this:*Set(Meaning,MicrosoftTranslator.Translate(MyWord.Value,LanguageTo.Selected.Code,{languageFrom: LanguageFrom.Selected.Code}));Set(Audio,MicrosoftTranslator.TextToSpeech(MyWord.Value,LanguageFrom.Selected.Code))*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/f75bf0d7-afc9-4de5-98e0-116fd4a48678.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/f75bf0d7-afc9-4de5-98e0-116fd4a48678.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The button is ready, but you will need a control to play the sound.

Step 40.

- Select the container control in the form.
- Click the + icon in the left navigation of Power Apps. It will show the Insert pane.
- Search for and insert an Audio control.

[![](https://pahandsonlab.blob.core.windows.net/docsapp/cd24fcff-2bff-45e4-a9b1-0e2a8d725ffd.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/cd24fcff-2bff-45e4-a9b1-0e2a8d725ffd.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Next you need to tell the audio control what sound to play.

Step 41.

- Select the audio control (if it is not already selected).
- Go to the 'Media' property of the control using the property drop down menu at the top left. (This should be the default.)
- In the formula bar, change the Media property to the variable that is holding the sound:*Audio*

[![](https://pahandsonlab.blob.core.windows.net/docsapp/37a695c0-c18a-4ca8-abf5-6c973a3ad4a7.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/37a695c0-c18a-4ca8-abf5-6c973a3ad4a7.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 Your app is now able to translate words, fill in the translation into your form, and even playback a sound for the word.

## Summary

In this tutorial, you will have exercised several skills in app-building:

- Creating a table
- Inserting controls
- Adding a connector
- Writing a formula
- Adding more functions to a formula
- Showing the contents of variables inside controls
Now you have an app that can not only translate words, but most importantly, can save them to an ongoing list. You will be able to track your learning more easily with this app. Besides words, what else can you think of that could use the same ideas in this project? If you want to include more columns in the table, such as one for an image to go with the word, you can view [the previous project for details on updating a table](https://aka.ms/houroflowcode/library).
Good luck with your learning!
