====== FREE POP - MAGENTO THEME ======

OVERVIEW
--------
Free POP is a nice and clear design template for magento ecommerce site. It is suite for many kind of webshop as music, movie, CD/DVD...

(+) Allow: You have full permission to use or customize for personal website or for your client website.

(-) Not allow: You are not allow to redistribute or sell this design any where.

(*) Required: You must keep our copyright at the footer of the template.

THE FEATURES
------------
+ Compatible with all major browsers(IE6, IE7, IE8, FireFox, Safari, Chrome)
+ Optimized for fast loading
+ Easily customize with PSD files (included in the package)
+ SEO (Search Engine Optimization) compliant
+ W3C HTML & CSS validated
+ Support Magento Version 1.3.x and above

INSTALLATION
------------
1. Copy /app & /skin folder to magento root

2. Goto Admin/Configuration/Design, select Themes session and input following value
+ Templates: freepop
+ Layout: freepop
+ Skin (Images / CSS): freepop

3. Configure Homepage:

* In General Information:

	Page Title *:Home
	SEF URL Identifier *:home
	Store View *: choose freepop.
	Status *:Enable.
	
	Content *: 
		<div class="intro_img"> 
		<a href="#"><img src="{{skin url='images/free_01.gif}}" border="0" /></a>
		</div>

		<div class="content_block">
		<div class="content_block_left">
			   {{block type="core/template" name="newmovies" as="newmovies" template="catalog/product/newmusic.phtml"}}
			   {{block type="core/template" name="newmovies" as="product_featured" template="catalog/product/newmovies.phtml}}
		</div>
		</div>
		
* In Custom Design:

		Layout * :3column

		Layout Update XML:

			<reference name="left">
			<block type="cms/block" name="menuleft" after="currency">
			<action method="setBlockId"><block_id>menuleft</block_id></action>
			</block>
			</reference>

4. Configure left menu on homepage - Create a static block:
		
		Block Title * :Menuleft 	 	 
		Identifier * :menuleft		 
		Store View *: choose freepop.
		Status *  :Enable.	 	 
		Content *:
			{{block type="catalog/navigation" name="catalog.menu" template="catalog/navigation/left_navigation.phtml"}}

3. Goto front-end to see the theme

Feel free to let us know if you have any comment or suggestion to help us producce free theme better.
Please contact us at: 
support@hello-magento.com or http://www.hello-magento.com/contacts

Regards,
Hello Magento Support
http://wwww.hello-magento.com