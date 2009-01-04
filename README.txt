$Id$

Content Profile Module
------------------------
by Wolfgang Ziegler, nuppla@zites.net

With this module you can build user profiles with drupal's content types.


Installation 
------------
 * Copy the module's directory to your modules directory and activate the module.
 
 Usage:
--------
 * There will be a new content type "profile". Customize its settings at
   admin/content/types.
 * At the bottom of each content type edit form, there is a checkbox, which allows
   you to mark a content type as profile.
 * When you edit a profile content type there will be a further tab "Content profile",
   which provides content profile specific settings.


Content profiles per role:
--------------------------
You may, but you need not, mark multiple content types as profile. By customizing 
the permissions of a content type, this allows you to create different profiles for
different roles.


Hints:
------

 * When using content profiles the "title" field is sometimes annoying. You can rename
   it at the content types settings or hide it in the form and auto generate a title by
   using the auto nodetitle module http://drupal.org/project/auto_nodetitle.