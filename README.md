t# confset
an easy way to set variables in config files

Usage Example: 

perl ./confset.pl example.conf setting=value

found on http://unix.stackexchange.com/questions/139574/change-a-value-in-a-config-file-or-add-the-setting-if-it-doesnt-exist

if your separator is " you need to do it like so

variable=\""net.ifnames=0 biosdevname=0\"" /path/to/file

sudo perl src/confset.pl GRUB_CMDLINE_LINUX=\""net.ifnames=0 biosdevname=0\"" /etc/default/grub


 
