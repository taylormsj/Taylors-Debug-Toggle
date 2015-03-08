# Taylor's Debug Toggle

Toggle WP_DEBUG on/off through the admin toolbar

### Overview
This plugin adds an option in the admin toolbar to toggle WP_DEBUG on/off.

wp-config.php must be writable by the server and code must be in the default format/spacing - **define('WP_DEBUG', false);**


### Installation
1. Upload the entire `taylors-debug-toggle` folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Ensure wp-config.php is writable by the server and the debug definition is in the default format/spacing - **define('WP_DEBUG', false);**


### Changelog
1.0
Prevented writing something other than "true/false" to wp_config and restructured version number 

0.0.1
Inital release