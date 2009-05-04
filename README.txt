Special Menu Items Module
------------------------
Written by Tamir Al Zoubi and Karim Djelid - Servit Open Source Solutions - www.servit.ch



Description
-----------
Special menu items is module that enables placeholder and separator menu items.Placeholder is a menu item which is 
actually not a link. Something like this is useful with drop down menus where we want to 
have a parent link which is actually not linking to a page but which is just acting as a parent grouping some children below it.
A separator menu item is something like "-------" which is also not linking anywhere but merely a mean to structure menus.

This is how the module work:
  - User can create a new menu item and place either "nolink" or "separator" to the URL 
   field, without quotes.
  - When the menu is rendered the "nolink" item will be rendered similar to a normal menu link 
   item but there will be no link just the title.
  - When the menu is rendered the "separator" item will be rendered to an item which is no link
   and the title will always be "-------".

This module depends on Menu module. It is recommended to use SimpleMenu module or other drop down menu module or you will 
not be able to acess children of nolink menu items.

  