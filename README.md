Getting Started with Copybar
============================

Copybar is an instant CMS.  Using a snippet like the one below, you can enable dynamic content editing.  

```html
<script src="//copybar.io/USERNAME/ELEMENT_ID.js"></script>
```

Replace USERNAME with your own username, and then create a unique element id for each snippet.

Embed as many snippets as you want (each with its own id), anywhere you want to be able to edit content. That means anywhere on the web, anywhere you can edit HTML.

In this demo, we show you how to get a simple dyanmic HTML5 site running from your Dropbox public folder.

How to Host a Copybar site on Dropbox
-------------------------------------

1. Download or clone the 'Getting Started' demo into your /Dropbox/Public folder
	
	If you are new to git, then use the 'ZIP' button to download an .zip file.  Double-click to unzip, and when you see the 'getting-started' folder, open it.

	The folder needs to be in your Public Dropbox folder to be hosted online.

3. Open '/index.html' in a text editor.

	This is a very basic HTML file, with nothing fancy.  It should work in most text editors, but code editors enjoy syntax highlighting to make things easier to read.

4. Right-click on index.html and select 'Copy Public Link'.  
	
	This will put a copy of the public link into your clipboard.  Now you can open your browser and paste this link into the address bar.  Hit enter to load the page.

5. What are you seeing now?

	Let's examine the'index.html' file.

	We put one of our own code snippets into your demo:

	```html
	<script src="//copybar.io/mhurwi/hey_buddy.js"></script>
	```

	There are just 2 interesting features to this code snippet:

	```html
		mhurwi
	```
	This is to be replaced with your own username.  The username you pick will become your Copybar account name.  When you signup for your account at Copybar.io, you get password protection for editing your content wherever it appears on the web.

	```html
		hey_buddy	
	```

	Each time you paste in a Copybar snippet with the same ELEMENT_ID, then it will show that specific content.  But, use a new name, like ELEMENT_ID_2, and Copybar creates a new element to edit.  

	*element id's must end with '.js'*

6. Make your own snippet

	Since our sample snippet uses our own protected account, you won't be able to edit this element.  But switch "mhurwi" to a name of your own! Copybar will create a new account for you and a new element with an 'Add Copy' button to get started.
	
7. Check out your account at Copybar.io
	
	You created a snippet with your own username and Copybar has an account ready for you.  Visit [Copybar.io/signup](https://copybar.io/signup).  Enter your information to manage your elements, keep them password protected, and invite collaborators.

	*Note, until you have confirmed your account with a password and email, your Copybar elements will be editable by anyone.*  






