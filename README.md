WordPress XHProf
=========


A WordPress plugin which makes it easy to view XHProf report for the current page request.

To active, add the following to `wp-config.php`, before `wp-settings.php` is included.

  require_once(ABSPATH . 'wp-content/plugins/wp-xhprof/xhprof-loader.php');
  
Please note that `xhprof-loader.php` currently starts XH Prof and sets `DONOTCACHEPAGE` even if the plugin is disabled.

# PHP Version
- 7.0
- 7.1
- 7.2
- 7.3
- 7.4
- 8.0
