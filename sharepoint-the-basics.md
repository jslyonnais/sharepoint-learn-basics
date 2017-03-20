# WHAT IS SHAREPOINT
---
- SP Site to share and make environment within business to share with collegue.
- Can connect multiple external like db to make everything centralized into the same portal.
- Plateforme regrouped multiple applications.

Installation example: On server - SP Designer or Workspace


Sites => SP Make websites [For you, Team, Company, Open to the world, etc.]
    - You are a current contributor and be able to edit
Communites => Help you work with more people
    - Share board
    - Calendars
    - Documents
    - etc.
Content => Place to put content and easy share (without needed to share by email, etc.)
    - Can remote edit
    - Also add functionnalities to edit on browser
Search => Search content, but let's search for people
Insights => Help you bring all your informations together and organize all contents
    - Presenting way that make sens
    - Dashboard
    - Visiodiagram
Composites => Can build on top of itself
    - Can be extended and build easy workflows or form without code
    - Can code plugins
    - Controlled and secure


# What Is a SharePoint Column Type
---
[SharePoint 101: Columns and Column Types](https://en.share-gate.com/blog/sharepoint-101-choosing-column-types)
Column types determine how data is stored and displayed in a list or library.

Site Columns are really useful. They let you reuse a column you’ve configured over and again, and save you lots of time. Without Site Columns, you’d have to recreate your own custom column within each individual List or Library. And that would not be fun.

Nonetheless, you need to be careful with Site Columns. You’ll need to think about columns and architecture each time a column is created and if they’re overused, they can create chaos within sub-sites. So, exercise Site Columns with caution.


## TYPE

### Single Line of Text
A column that displays text in a single line—small amounts of differing information—for example, first names, last names, job title, etc.

### Multiple Lines of Text
Collects and displays lengthier text on multiple lines. Best used when you need to add more information, such as a description or a comment related to an item. You can read the entire text when viewed in a list or library.

### Number
This is a column for your numerical values (note: these are for numbers that do not represent monetary value). These can be used for storing data for calculations (that **do not** require a high level of accuracy); for example, if employees needed to log hours on a particular task.

### Currency
Similar to the Number column, Currency columns are used for numerical values, but these numbers **do represent monetary worth.** Choose this column for financial calculations, and calculations that require a high degree of accuracy.

A currency column is accurate to 15 digits to the left of a decimal place and 4 digits to the right. You can specify min and max values, choose to include decimal places, display a default value, and format the number as a percentage.

### Boolean (Yes/No)
Like most column titles, this one is fairly straight forward. Here we have a column type to store true/false, yes/no, or other binary type information—for instance, as an RSVP to an event. Or if a project is open or closed, in progress, or completed.

### Person or Group
This column type builds a searchable list of **people and groups** that users can choose when adding or editing an item in the site. For instance, you could create a pool of employees that are authorized, or “Assigned To” to complete a certain task on the company ‘to do’ list. The Person or Group column can be customized to **allow multiple selections**, include or exclude groups of people, limit the list to specific users, and specify certain information to display.

### Hyperlink or Picture
This column is for storing hyperlinks, which you can choose to display it as a web URL, a clickable hyperlink: if it’s a resource to be accessed; or a picture: if it’s a graphic for your Intranet or Internet.

## MORE ABOUT THE COLUMNS 

### Choice Column Type
- Define a list of choices — create a list of specific values users can select from.
- Additional custom choices — this function allows users to enter a specific value that is not listed; it’s useful if you don’t know in advance the different values that your users will need to enter.
- Display format — this is more than simply aesthetics; specify a drop-down menu, or radio buttons, and users will select individual choices; specify check boxes and users can choose more than a single value
- Display default value — A certain value is automatically selected when a new item is created; this is designed to help users enter information more quickly. For instance, if your HR team is listing ‘new’ clients most of the time, ‘new’ might be the value that is automatically selected (and can be changed if needed)

### Date and Time Columns
This column is designed for logging times and dates. For example: calendar dates. A Date and Time column can be varied or customized to display only the date or, both the date and time. As well as that, users can avail of an automatic, default value, similar in concept to the above choice column. Again, enabling an automatic date as a default display means a user can enter information faster.

### Calculated values
These can also be built into date and time columns. These are really useful for presenting automatic time and dates, where the date or time may fluctuate depending on the item itself. These are simple calculations that can be configured using information in other columns.

For example, if the date you wanted to display was two weeks after the current date, you would put together the equation: `=[TODAY]+14` in the calculated value box. There are plenty of combinations and formulas you can use here—if you're used to Excel, this will be familiar to you. Need to find the right equation? A simple Internet search will produce any formula you can think of.

### Calculated Columns
A sibling of the above calculated values, calculated columns are a column type created to display data based only on the results of a calculation. It is its own separate column from the above and, when added to a list or library, creates formula operators (+, –, etc.), can be referenced in other column in that same List or Library.

### Lookup Columns
The lookup column is a good example of a function that allows for precision in organizing information that is already stored in the site. 
```
For example, you may want to store the names of client accounts to which your team is assigned, limiting the choices to those who are part of the client accounts list.
```

Similar to choice columns, lookup columns can be customized in certain ways:
- Allow multiple selections — limit the number of values users can assign to the list, or allow users to select as many as they like.
- Choose columns to display — add more columns to indicate specific field values.
- Indicate the source of the lookup values — a further disambiguation is possible by specifying which list, library, or discussion board is the source for the choices (i.e. those connected to the client accounts) stored in the column. Further, you can go on to specify which column in that list/library that contains the choices you want users to select.

### Managed Metadata
This column type enables users to select from a specific set of managed terms, and to apply these terms to data in their list. Metadata is (put as simply as possible) data about data. Or to put it another way, information about the content in your lists and libraries.

```
For example, say you want your users to upload documents and include information about the document’s specific audience? Say the audience is the Project Manager who needs these documents for the proposal she is leading. Well, some users may tag their documents with “Project Manager”, some will tag theirs as “PM”, and others will tag their documents as the project manager’s name, “Jill Coloney”, etc., etc. All different, and that means documents for the project proposal may be easily overlooked or missed.
```

## So, how do you create and use a Site Column?

1. Begin by selecting the `cog` on the top right of your screen and choose the `Site settings` option: ![Option > Site settings](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image1.png)
2. From the Site Settings page, select Site Columns: ![Site columns from Site Settings page](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image2.png)
3. You’ll see that there’s already a long page of column settings. These are the details of your existing columns — **DO NOT change or remove any of these as this will impact on your existing Lists and Libraries and cause havoc.** Create a new Site Column by selecting `Create`: ![Create site columns](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image3.png)
4. We’ve put together an imaginary `customer complaints` column: ![Create customer complaint's column](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image4.png)
5. Don’t forget to add additional useful information which will impact how the column can be used. ![Create column useful information](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image5.png)
6. Click `create` and the new column is ready to use. _Awesome!_

## So, how do I put that new column into action?
Now that you have that column, let’s see how to put it into use. We've created a very simple mock-up to illustrate the process.

1. Go to the List or Library you want to add the column to, as follows: ![add column to List of Library](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image6.png)
2. From the ribbon menu, select Library `Settings`
3. Scroll down and select `add from existing site columns` ![add from existing site columns](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image8.png)
4. Next, you simply add the site columns you’ve created ![Add site columns](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image9.png)
5. And you’re done. You can now add information to that column! ![Customer contact now have the new column!](https://media.share-gate.com/app/archive/media/Sharegate/Images/2016/juillet/spsitecolumn/image10.png)

# User Interface & Navigation
[SharePoint 101: SharePoint 2013 User Interface & Navigation](https://en.share-gate.com/blog/start-to-learn-sharepoint-user-interface-navigation)

### Newsfeed
This is your My Site Newsfeed where you'll see the news coming from the sites you are following. My Site is the social aspect of SharePoint that allows you to be informed and interact with what's relevant to you in SharePoint.

### OneDrive
Previously called SkyDrive, this is a place where you can upload documents, photos and so on and then you can share them with any colleagues. 

### Sites
This is a place where you can see everything that's happening on the sites you're following. To follow a site, you only need to click on the little star in the menu that says "follow" when you're in it.

### Share
You can share your site with other people.

### Follow
You click on this button when you're on a Site you'd like to follow in your "My Site" afterwards.

### Sync
When you choose this option, SharePoint creates a copy on your computer of the List or Library available on the page. 
_*Note that you need a OneDrive for Business license to be able to use this feature._


## List and Library
When you're in one of your List or Library, you'll see the famous Ribbon we talked about earlier. You've probably already realized that it's not the same one as in the Home Page. In a SharePoint List, you have a tab for your items and a tab for your List.

### Items Tab
![Items Tab](https://media.share-gate.com/app/archive/media/Sharegate/Images/2014/April/start-learn-sp/item_tab.png)
There are different actions available like create a new item, edit an item and many others. It's not very complicated to understand the basic ones and we'll get to the more advanced settings later on, as well as Workflows

### List Tab
![List Tab](https://media.share-gate.com/app/archive/media/Sharegate/Images/2014/April/start-learn-sp/list_tab.png)

#### Quick Edit
You can edit many items at the same time with this option. When you select the quick edit, your entire List gets into an edit mode and you can bulk edit any item in your list.

#### Create Column
This is how you create a List column. Refer to the previous articles of this series to know what column to pick!

### Library Ribbon
![Library Ribbon](https://media.share-gate.com/app/archive/media/Sharegate/Images/2014/April/start-learn-sp/library_ribbon.png)
In the Library, we also have a ribbon at the top of the page with two new tabs: Files and Library. When you open the two different tabs, you'll see that the menu is basically the same between Files & Items and List & Library.

#### Files Tab
The only thing we'll look at here are the check in/ check out actions. Everyone should know what this is. _One of my colleague once had a problem with a file that wouldn't have happened if he knew the existence of the check in/ check out options._ It's very simple, when you **check out a document, no one can edit that document at the same time as you do.** This way, you make sure there are no conflicting changes in your file.

Then, when you're done, you can check in and someone else can edit the document afterwards. _My colleague lost all the modifications he made in a PowerPoint document right before a meeting, because there were two persons modifying the file._

# SharePoint 2016 User Interface & Navigation
[SharePoint 2016 User Interface & Navigation](https://en.share-gate.com/blog/sharepoint-2016-user-interface-navigation)

## Hybrid Sites
Probably the biggest new feature in SharePoint 2016 is [hybrid search](https://en.share-gate.com/blog/sharepoint-hybrid-search). While hybrid search may have stolen the headlines, it’s not the only instance of new hybrid functionalities in SharePoint.

The new hybrid SharePoint sites wizard lets you configure a server-to-server connection to join features of both environments. This offers users a simple way to keep track of their most frequently accessed sites, whether they are located on-premises or in the cloud.

