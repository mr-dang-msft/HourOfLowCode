# Hour of Low Code 2021: Create your own library

Staying organized is a healthy habit that has many benefits including clearing the mind and relieving stress. With the right tools you can organize everything from upcoming school assignments to words you’ve learned from another language, and even toys and games you own.
This session will guide you in creating an app in Power Apps for cataloguing your own library. You can use it to organize books that you have read, books that you want to read, or simply books that you own. You can even change the scenario altogether to organize anything else you want. How you use it and customize it is up to you.

## Table of contents

1. Getting started
    - Setup a team
    - Add Power Apps to Teams
2. Create your first app
    - Start the app
    - Create a table
    - Add columns
    - Create controls
    - Test the app
    - Save and publish
    - Open the app
3. Update your app
    - Add more columns
    - Update the form
    - Save, publish, and test

## Getting started

You will be creating an app in the Power Apps editor which you can find in Microsoft Teams. So you will need:

- access to Microsoft Teams
- membership in a team (there will be instructions on how to create one)
- basic understanding of how to read a table, its rows, and columns

### Setup a team

You will need to have a standard team or be part of a standard team where your apps will be. Note that a standard team is different from a 'classroom' team. If you already have a team, you can skip this section.
Step 1.

- Open Microsoft Teams and sign in. (Alternatively go to [teams.microsoft.com](https://teams.microsoft.com) and sign in.)
[![A screenshot of the page for signing into Microsoft Teams.](https://pahandsonlab.blob.core.windows.net/docsapp/f468aadb-e68a-4c2f-89d8-66c980a4a081.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/f468aadb-e68a-4c2f-89d8-66c980a4a081.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 2.

- Click 'Join or create team' at the top right to create a new team.
[![A screenshot of Microsoft Teams. The button for 'Join or create team' is at the top right corner of the program.](https://pahandsonlab.blob.core.windows.net/docsapp/416a2235-349c-4f54-93b2-60c98b55d286.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/416a2235-349c-4f54-93b2-60c98b55d286.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 3.

- Name your team.
- Click Next and wait for the team to be created.
- In the next dialog, search for and add members to the team, or click Skip.
[![A screenshot of the dialog box that appears for creating a team. There are fields for: Team name, Description, Privacy. At the bottom of the dialog are buttons for Cancel and Next.](https://pahandsonlab.blob.core.windows.net/docsapp/568cb7d6-8a1f-4abf-9924-d04bbabcfa47.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/568cb7d6-8a1f-4abf-9924-d04bbabcfa47.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 Your team is ready. You can create individual channels for each person in the class so everyone has their own space to share their apps.

### Add Power Apps to Teams

Once you have a team where your apps will stay, you can add the Power Apps editor to Teams so that you can create apps.
Step 4.

- From the left navigation, click the Apps icon.
- In the search box at the top left, search for 'Power Apps'.
- Select Power Apps from the search results.
- Click 'Add'. Or if Power Apps is already added, click 'Open'.
🏆 Power Apps is now added to Teams and you will land on the Power Apps page once it is done loading.
[![A screenshot of the search results from the Apps screen in Microsoft Teams](https://pahandsonlab.blob.core.windows.net/docsapp/160e5369-50d6-4794-b02a-db0e7500021d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/160e5369-50d6-4794-b02a-db0e7500021d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

## Create your first app

### Start the app

You are now ready to create your first app in Power Apps.
Step 5.

- Click 'Start now' in the top area of the screen.
[![A screenshot of the Power Apps portal in Teams. At the top are tabs for Home, Build, About. In the top area is a box on 'How to create an app for your team' which has a button for 'Start now' and 'Learn more' below that.](https://pahandsonlab.blob.core.windows.net/docsapp/b5cec9db-43f5-4c9c-91e4-ad736110bdfa.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/b5cec9db-43f5-4c9c-91e4-ad736110bdfa.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

A prompt will appear where you can select the team where you want your apps to stay.
Step 6.

- Find and select the team where you want your app to belong.
- Click Create.
[![A screenshot of a prompt for "Create an app". It has a scrolling list for selecting a team, and a button for Create at the bottom.](https://pahandsonlab.blob.core.windows.net/docsapp/b1592a19-ea6f-43f0-9035-65e3572d34d9.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/b1592a19-ea6f-43f0-9035-65e3572d34d9.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 7.

- Name your app.
- Click Save.
In this example, the app name is 'My Books'. If there will be multiple people making apps in the same team, consider including the name of the person in the app name.
[![A screenshot of a modal that appears for 'Name your app.' It has a field for inputting App name and a button for Save.](https://pahandsonlab.blob.core.windows.net/docsapp/31b531a8-0495-41c5-8194-ee707d4bfe32.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/31b531a8-0495-41c5-8194-ee707d4bfe32.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Creating an app involves some key steps:

- Creating a place where our information will be saved.
- Creating the look and feel of our app.
- Testing our app
First, you will create a table where you can save details about our books.
[![A screenshot of the Power Apps studio in Teams. It has a blank canvas area in the middle, two panels on the side and menus at the top.](https://pahandsonlab.blob.core.windows.net/docsapp/e843d8fe-d2cb-4ff4-803e-c4913c887fc8.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/e843d8fe-d2cb-4ff4-803e-c4913c887fc8.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

### Create a table

A table is a place to keep information in an organized way. It is made up of horizontal columns and vertical rows. In our case, each column is a kind of detail about our books: title, author, genre, and so on. Each row in our table is a different book and its details for each column.
Step 17.

- From the left navigation in Power Apps, select the cylinder icon for 'Data'. The Data pane will appear.
[![A screenshot highlighting the cylinder icon to click to see the data pane.](https://pahandsonlab.blob.core.windows.net/docsapp/1306fc6b-c83c-41d4-a93d-a275a92609a0.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/1306fc6b-c83c-41d4-a93d-a275a92609a0.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 18.

- In the Data pane, click '+ Add data' to reveal options.
- Click '+ Create new table' in the options for 'Select a data source' that appear.
[![A screenshot of a modal for 'Select a data source'](https://pahandsonlab.blob.core.windows.net/docsapp/8ba084b0-c54e-40c6-80ff-1d224becdfd5.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/8ba084b0-c54e-40c6-80ff-1d224becdfd5.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 19.

- Name your table where you will save books. In this example, the table name is 'Book' and it has a plural name 'Books'.
If you expect to have many library apps, consider adding a prefix before 'Book' so that everyone's table of books is different.
[![A screenshot of a modal for 'Create a table. It includes a field for Table name and Plural table name. At the bottom are buttons for Create and Cancel.](https://pahandsonlab.blob.core.windows.net/docsapp/d2e04780-53f9-4a8a-a175-d4d5614bad8c.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d2e04780-53f9-4a8a-a175-d4d5614bad8c.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

### Add columns

The table is created, but it is empty to start. You will edit an existing column and add different kinds of columns for practice, which include:

- Title
- Author
- Genre
- Condition (optional)
First you will revise the Name column so that it is called Title instead.
Step 20.

- Click the Name column and a menu will appear.
- From the menu, click 'Edit column.'
[![A screenshot of the quick edit experience for editing a table. The Name column is selected and a menu appears below it.](https://pahandsonlab.blob.core.windows.net/docsapp/d93cf465-f32a-4b54-9f01-ab168e9ba492.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d93cf465-f32a-4b54-9f01-ab168e9ba492.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 21.

- Change 'Name' to 'Title'.
- Click 'Advanced options' to show more options.
- Change 'Max length' to 300.
- Click Save.
[![A screenshot of a modal for 'Edit column.' It has fields for Name, Type, and Max length. At the bottom are buttons for Save and Cancel.](https://pahandsonlab.blob.core.windows.net/docsapp/2ac7033b-e7cd-4b55-983e-16ab4ae3c892.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/2ac7033b-e7cd-4b55-983e-16ab4ae3c892.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Next, you will create another column of text for the Author(s) of the books we have. To create a new column, follow this pattern:
Step 22.

- Click the + icon at the end of the first Title column. This brings up options for 'Add new column'.
- Set the Name of the column to 'Author'.
- Set the Type of the column to Text.
- Click 'Advanced options' and set the 'Max length' to 300.
- Click Create.
[![A screenshot of the quick data editor in Power Apps studio. It shows the modal for adding a new text column for Authors.](https://pahandsonlab.blob.core.windows.net/docsapp/e98d040b-417f-4434-b56a-3b89ba8a0e3e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/e98d040b-417f-4434-b56a-3b89ba8a0e3e.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

So far you have worked with columns that expect text. There are many other column types. The Choice type of column lets the user pick from a list of options. You could use a Choice type of column for the genre of a book: is it fiction or non-fiction? And you can add as many choices as you want.
Step 23.

- Click the + icon at the end of the Author column. This brings up options for 'Add new column'.
- Set the Name of the column to 'Genre'.
- Set the Type of the column to Choice.
- Enter 'Fiction' as a choice.
- Click 'New choice'.
- Enter 'Non-fiction' as another choice.
- Repeat the earlier steps for other choices you want.
- Click Create.
As an optional challenge, can you repeat these steps to add a Choice column for the Condition of a book with the choices: New, Good, Used, Damaged?
[![A screenshot of a modal for adding a new column of type Choice for a book's genre. It includes choices for Fiction and Non-fiction.](https://pahandsonlab.blob.core.windows.net/docsapp/15ab7754-4ce0-4610-b1ab-2451942f4261.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/15ab7754-4ce0-4610-b1ab-2451942f4261.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 You added columns to your table that would describe the details about your books: title, author, and genre.

### Create controls

After the table of books is created, you need your app to show ways of interacting with that table. How will someone more easily enter information into it?
'Controls' are the objects that can be inserted on the screen for interaction. They include labels for showing text, boxes for typing in, sliders, timers, and more.&nbsp;There are also templates that can insert many controls at once for you. They will save you a lot of time.
On the blank screen, without any controls inserted, there are options to 'Start this screen' 1) with data, or 2) with a layout. Since you created a table, you could start your first screen with data.
Step 8.

- On the blank screen, under 'Start this screen' select 'With data'.
- In the options that appear, select the table of books you had created earlier. In this example, the table is called 'Books' though your table may be named differently.
[![A screenshot of a blank canvas with the option for 'Start this screen' 'with data' selected. It shows a modal for 'Select a data source' with the table for Books highlighted.](https://pahandsonlab.blob.core.windows.net/docsapp/d157ebf7-1fed-40e4-917a-53ec84ea7d8d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/d157ebf7-1fed-40e4-917a-53ec84ea7d8d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆&nbsp;The basic app is nearly complete since it has controls for adding new books, viewing book entries, and deleting books with the click of a few buttons.

### Test the app

An app should not be used until you have tested it to make sure it works the way you expect. Test out the app.
Step 24.

- Click 'Preview' at the top right of the Power Apps studio. This puts the app in a preview mode so controls can be clicked as if you were using the app and not editing it.
- While previewing the app, click 'New record' to add a new book to the table.
- Type in Title, Author, and select a genre for a book.
- Click the check mark at the top right of the app to save the new book entry.
- Leave preview mode by pressing Esc.
[![A screenshot of the top right corner of Power Apps studio showing the Preview button highlighted.](https://pahandsonlab.blob.core.windows.net/docsapp/f0419dc8-5169-41e5-aafb-afe2d52762a2.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/f0419dc8-5169-41e5-aafb-afe2d52762a2.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

### Save and publish

Your table is created and you tested out your app. Power Apps will auto-save every 2 minutes. If you have not already done so, click Save at the top right corner as you go along.
But nobody can see the app or any changes you make until you publish the app.
Step 9.

- At the top right of the Power Apps studio, click 'Publish to Teams'.
- Click Next on the prompt that appears.
[![A screenshot of the Power Apps studio in Teams. At the top right corner the 'Publish to Teams' button is highlighted.](https://pahandsonlab.blob.core.windows.net/docsapp/5fd0beac-e67d-4e33-a831-402191985e0d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/5fd0beac-e67d-4e33-a831-402191985e0d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Options will appear for where you want the app to be published and available.
Step 10.

- Scroll to the channel where you want the app to be shown.
- Click the + icon to the right of the channel.
- Click 'Save and close'.
[![A screenshot of a modal for 'Add to channel' showing a list of the available channels to publish an app. At the bottom is a button for 'Save and close'.](https://pahandsonlab.blob.core.windows.net/docsapp/4c918258-9ab0-433d-a6ab-60bd9024610d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/4c918258-9ab0-433d-a6ab-60bd9024610d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 The app is now published in the channel you selected.

### Open the app

You tested your app and published it, but next, you need to try it out inside Teams itself. So you will leave Power Apps for a moment to see the app in the Teams channel.
Step 11.

- From the left navigation in Teams, click the icon for Teams.
- When the list of teams finishes loading, select the team where the app was created.
- When the selected team loads, select the channel where the app was published.
- At the top of the channel, select the tab for the app. Try out the app again.
[![A screenshot of an app embedded in a tab in Teams.](https://pahandsonlab.blob.core.windows.net/docsapp/93d366a8-5c20-4cb8-9b54-dba6621638c4.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/93d366a8-5c20-4cb8-9b54-dba6621638c4.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 You have successfully created your first app in Power Apps, and you did it in Teams!
The next section is optional and shows how to update the app to include more columns. You can use that practice to add any other columns you want in the future.

## Update your app

The steps so far allowed you to create a very basic app. But what someone wants in an app for organizing books might be different from what someone else wants in theirs.
This section is optional and provides instruction on how to add a new column and update the app. You can take the practice in this section to add any other columns that YOU want.

## Add more columns

Return to Power Apps when you are ready to make more changes to your app.
Step 12.

- Click the ellipsis (3-dot) icon in the left navigation of Teams.
- Search for 'Power Apps'.
- If you want Power Apps to stay in the left navigation, click the ellipsis to the right of it in the search results. Then click Pin from the menu of options.
- Select Power Apps.
[![A screenshot of Teams showing the menus to select for pinning Power Apps to the left navigation of Teams.](https://pahandsonlab.blob.core.windows.net/docsapp/201b39e5-4e6a-41b6-b81c-fa7d44d36cb4.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/201b39e5-4e6a-41b6-b81c-fa7d44d36cb4.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

So far you have taken the shortest path to getting started in Power Apps. To see even more options and to view apps and tables you have already created, you will explore the Build tab.
This next section will guide you on how to add an image column for saving a photo of the book cover and longer text column for a description of the book.
Step 25.

- From the top of Power Apps, click Build.
[![A screenshot of the Power Apps portal in Teams. It shows the Build tab highlighted at the top of the page.](https://pahandsonlab.blob.core.windows.net/docsapp/374c1f9e-144f-4066-bf2a-16efa1113915.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/374c1f9e-144f-4066-bf2a-16efa1113915.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

Step 26.

- From the page that loads, select the team where your apps are created. This loads a page with the content created in that team.
- In the box for 'Items created' for your team, click 'See all' at the bottom to see more.
[![A screenshot of the apps, tables, and more created in a team.](https://pahandsonlab.blob.core.windows.net/docsapp/eb8cf66c-939b-4259-807a-6a17a57a204b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/eb8cf66c-939b-4259-807a-6a17a57a204b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

To add a new column to our table of books, we need to find and open it up again. We are using the Build tab because it includes columns that are not in the quick editor we used before for adding columns.
Step 13.

- From the list of items created in the team, search for your table of books that you created.
[![A screenshot of the list of all items created in a team.](https://pahandsonlab.blob.core.windows.net/docsapp/f6a96717-eadc-4388-9f56-b117c6f4b86b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/f6a96717-eadc-4388-9f56-b117c6f4b86b.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The table for our books will load and show a list of all its columns, even the hidden ones that were automatically created.
Step 27.

- To add a new column, click '+ Add column' from the top bar.
[![A screenshot showing the columns of a table. The button for 'Add column' is highlighted in the command bar.](https://pahandsonlab.blob.core.windows.net/docsapp/73eb50de-d3c2-4d2a-bf10-da424952181a.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/73eb50de-d3c2-4d2a-bf10-da424952181a.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

A pane for the new column will appear on the right side of the screen.
Step 28.

- Set the name of the column to 'Cover'.
- Change the Data type to 'Image'.
- Click Done at the bottom of the pane.
- Click 'Save Table' at the bottom of the page to save all of your changes.
[![A screenshot of the pane for adding a new column in Dataverse. It shows the properties of an image column called Cover.](https://pahandsonlab.blob.core.windows.net/docsapp/17a7c38c-293d-4f83-a21c-ecb1df1aa3a9.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/17a7c38c-293d-4f83-a21c-ecb1df1aa3a9.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The column for writing multiple lines of text is also not available in the quick table editor in Power Apps. We can add it here now though.
Step 16.

- Click '+ Add column' from the top bar.
- Set the Display name of the column to 'Description'.
- Change the Data type to 'Multiline Text'.
- Click 'Advanced options'
- Change the 'Max length' to the number of characters (letters) you want or keep it at 2,000.
- Click Done at the bottom of the pane.
- Click 'Save Table' at the bottom of the page to save all of your changes.
[![A screenshot of the 'Add column' experience in Dataverse for Teams. It shows a new multiline text column being added called 'Description.'](https://pahandsonlab.blob.core.windows.net/docsapp/ee209496-3d88-47d9-ad71-15565bc88646.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/ee209496-3d88-47d9-ad71-15565bc88646.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 The table has been updated. You can add any other columns you want in the same way.
Now we need to update our app to include the new columns.

### Update the form

To return to the app we were editing, we can find it in the Apps section of the Build tab.
Step 14.

- From the list of different kinds of content on the left, click Apps. This shows a list of all apps in the team.
- From the list of apps, click the app that you had created.
[![A screenshot of the Apps list in the Build tab of Power Apps in Teams.](https://pahandsonlab.blob.core.windows.net/docsapp/41ede0f2-59a9-488d-9d2c-93765a8f80dc.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/41ede0f2-59a9-488d-9d2c-93765a8f80dc.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The Power Apps studio will load and reopen your app. Next, we will edit the form control in the app to show the new column we added.
Step 29.

- Click the blank area below the columns for Title, Author, and Genre. A blue box will appear around the form control. EditForm1 will also be highlighted in the Tree view on the left to show that the form is selected.
- In the properties pane on the right side of the screen, click 'Edit fields' beside Fields. This will show a pane for Fields.
[![A screenshot of an app in the Power Apps studio in Teams. It shows the property pane for Fields for the selected form.](https://pahandsonlab.blob.core.windows.net/docsapp/e0afdc7b-7128-4477-b722-f806ce52bb66.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/e0afdc7b-7128-4477-b722-f806ce52bb66.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

The Fields pane lets us show any other columns in the form that were not already visible.
Step 15.

- From the top of the Fields pane, click '+ Add field'.
- Search for and select the columns for 'Cover' and 'Description' that we added to the table earlier.
- Select any other columns you added and want to show.
- Click Add.
[![A screenshot of the pane for choosing which fields to show in a form in Power Apps.](https://pahandsonlab.blob.core.windows.net/docsapp/93b725f8-4153-448d-9f33-5244d9761f5f.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/93b725f8-4153-448d-9f33-5244d9761f5f.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

There is a little more to change so that the changes to the form looks good. We want the new columns in the form to fit the width of the form.
Step 30.

- Select the card in the form for 'Cover'. A blue rectangle will appear around only the card for Cover.
- From the properties pane on the right side of the screen, turn on 'Width fit'. This will allow the card to fit better in the app.
- Repeat the steps for 'Description': select the card in the form for 'Description' and turn on its 'Width fit' property.
[![A screenshot of a form in Power Apps. It shows a card in the form selected and with its Width fit property turned on.](https://pahandsonlab.blob.core.windows.net/docsapp/1cc657d4-90dd-4a35-acd0-15d899b082b1.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/1cc657d4-90dd-4a35-acd0-15d899b082b1.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

For smaller screens and in general, it may be easier to view the form with just one column per row. This is an optional step to change the way the form looks.
Step 31.

- Click the white space at the bottom of the form so that the entire form is selected. A blue border will appear around the entire form.
- From the properties pane in the right side of the screen, change the Columns property to 1 or 2.
[![A screenshot of the Power Apps studio showing a form that is selected changing its Columns property to 1.](https://pahandsonlab.blob.core.windows.net/docsapp/fcbd30c1-09b0-496e-bbb6-b291e38a60fb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/fcbd30c1-09b0-496e-bbb6-b291e38a60fb.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 You updated the form with the new columns that you added to the table.
You can repeat these steps any time you decide to add a new column to your table that is not available in the quick table editor.

### Save, publish, and test

Any time you make changes to the app, you need to save it. When you want everyone else to see the changes, you publish the app.&nbsp;
You can get into this habit as you update your app:

- Make changes to the app.
- Test the app.
- Save the changes.
- Publish the app.
- Repeat the steps.
These steps are shown in the earlier section on 'Create your first app', but here are some reminders:

- Test your app by clicking 'Preview' at the top right to enter a preview mode that lets you interact with the app. When you're done testing, click Escape to return to editing.
- Save the changes to the app by clicking Save at the top right.
- Publish the app by clicking Publish at the top right and clicking 'Save and close'.
[![A screenshot of a finished app in Teams.](https://pahandsonlab.blob.core.windows.net/docsapp/998c70e7-c299-46fb-a9c2-174a67343c6d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)](https://pahandsonlab.blob.core.windows.net/docsapp/998c70e7-c299-46fb-a9c2-174a67343c6d.png?sp=rl&st=2021-04-14T15:00:10Z&se=2030-04-15T15:00:00Z&sv=2020-02-10&sr=c&sig=jFZFWDDigKXqbHOmF1517W16JWWYbi1CaW4ARQu3gYE%3D)

🏆 You successfully updated your table and app!
It is up to you to decide what details you want for books and how you want your app to look.

- Do you want to add a star rating and review for each book?
- Do you want to add a check in and check out system?
And this tutorial showed you how to organize books that you have, but how can you use these same skills to organize other things? Enjoy creating your next app and making this one even better!
