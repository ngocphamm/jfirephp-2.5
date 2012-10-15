
OVERVIEW
============

JFirePHP takes FirePHP integration to the next level.

This version of JFirePHP is for Joomla 3.0 only because there're versions for 1.5 and 1.6+ (1.7, 2.5) available:

* For Joomla 1.5: by [Kunena Team](http://joomlacode.org/gf/project/kunena/frs/?action=FrsReleaseView&release_id=11823)
* For Joomla 1.6+: based on 1.5 version but a bit altered. Not sure by whom but you can find it [hosted by webeks.net](http://www.webeks.net/joomla/jfirephp-in-joomla-16.html)

The 3.0 version is still based on 1.5 version but strips out some redundants, for example, support for PHP4 since Joomla 2.5 and up doesn't support PHP4 anymore.

Simply install the system plugin via the Joomla Extension Manager and make sure it is published. If you want to use the plugin without jumping to Joomla Debug mode, please also set the option "Limit functionality to Joomla debug mode" to "No".

<!--IMPORTANT
============

Add the firephp/firephp.defines.php to your project. You can either copy the content into 
your code (e.g. a global defines file) or copy the file into your project. Make sure it is 
included in your distribution. It ensures that all the FirePHP calls can stay in your code
without creating errors on systems without FirePHP.
Make sure you use the fb() or FB::* syntax on all FirePHP calls you place into your code.
DO NOT include any FirePHP files and classes directly. All of that is performed for you
as part of JFirePHP.-->

USAGE
============

Once JFirePHP has been installed you can leverage all of the FirePHP (fb() and FB::*) functionality in your code. See the [FirePHP Headquarters](http://www.firephp.org/HQ/Use.htm) for detailed information about FirePHP and its usage.

For feedback and support please kindly create an issue on this repository.

