Nagios 'Smoke' - dark mode css files

This is a simple file replacement of the css files, usually found at

/usr/local/nagios/share/stylesheets/

Before deploying, be sure to back up the original files in this directory for a light mode. Then you can build a simple script to switch back and forth as desired. Be sure to check, preserve and transfer ownership and permissions of the original files to the replacement files.

The files take effect immediately when placed, no restart of any service is required.
