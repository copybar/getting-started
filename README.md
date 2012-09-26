Getting Started with Copybar
============================

Copybar is an instant CMS.  Using a snippet like the one below, you can enable dynamic content editing.  

```html
<script src="//copybar.io/USERNAME/ELEMENT_ID.js"></script>
```

Replace USERNAME with your own username, and then create a unique element id for each snippet.

Embed as many snippets as you want (each with its own id), anywhere you want to be able to edit content. That means anywhere on the web, anywhere you can edit HTML.

In this demo, we show you how to serve a dynamic HTML5 site from your Dropbox account.

How to Host a Copybar site on Dropbox
-------------------------------------

1. Download or clone the 'Getting Started' demo into your /Dropbox/Public folder
	
	If you are new to git, then use the 'ZIP' button to download an .zip file.  Double-click to unzip, and when you see the 'getting-started' folder, open it.

	The folder needs to be in your Public Dropbox folder to be hosted online.

3. Run the site in your browser

	Right-click on index.html and select 'Copy Public Link'.  
	
	This will put a copy of the public link into your clipboard.  Now you can open your browser and paste this link into the address bar.  Hit enter to load the page.

5. What are you seeing now?

	Let's examine the'index.html' file.  Open this file in a text editor.

	We put one of our own code snippets into the demo:

	```html
	<script src="//copybar.io/copybarrista/hello.js"></script>
	```

	Notice 2 interesting features:

	```html
		copybarrista
	```
	This is to be replaced with your own username.  The username you pick will become your Copybar account name.  When you signup for your account at Copybar.io, you get password protection for editing your content wherever it appears on the web.

	```html
		hello	
	```

	Each time you paste in a Copybar snippet with the same ELEMENT_ID, then it will show that specific content.  But, use a new name, like ELEMENT_ID_2, and Copybar creates a new element to edit.  

	*element id's must end with '.js'*

6. Make your own snippet and refresh the browser

	Since our sample snippet uses our own protected account, you won't be able to edit this element.  But switch "copybarrista" to a name of your own and reload the page! Copybar will create a new account for you and a new element with an 'Add Copy' button to get started.

	*If nothing happened, you might need to do a hard reload.  It's simple:
	Mac: command+shift+R
	Windows: ctrl+shift+R*
	
7. Check out your account at Copybar.io
	
	You created a snippet with your own username and Copybar has an account ready for you.  Visit [Copybar.io/signup](https://copybar.io/signup).  Confirm your account to manage your elements, keep them password protected, and invite collaborators.

	*Note, until you have confirmed your account with a password and email, your Copybar elements will be editable by anyone.*  

---

Did you like this demo?  Feel free to create snippets and put Copybar content anywhere you want!

There's more you can learn at [Copybar.io](http://copybar.io).    And don't hesitate to give us your feedback, it will help guide us in creating the world's easiest CMS.

Contact
=======
* Website: [Copybar.io](http://copybar.io)
* Email: [hello@copybar.io](mailto:hello@copybar.io)
* Twitter: [http://twitter.com/copybar](http://twitter.com/copybar)

License
=======
This material is Copyright &copy;2012 Copybar and licensed under the [Creative Commons Attribution-Share Alike 3.0 United Stateslicense](http://creativecommons.org/licenses/by-sa/3.0/us/). You are free tocopy, distribute, transmit, and remix this work, provided you attribute the work to Copybar as the original author and reference [this repository](http://github.com/copybar/getting-started). If you alter, transform, or build upon this work, you may distribute the resulting work only under the same, similar or a compatible license. Any of the above conditions can be waived if you get permission from the copyright holder. For any reuse or distribution, you must make clear to others the license terms of this work. The best way to do this is with a link to the [Creative Commons Attribution-Share Alike 3.0 United States license](http://creativecommons.org/licenses/by-sa/3.0/us/).




