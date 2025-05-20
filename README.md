I got a little frustrated with EPSON's lame support of Linux drivers.  This should work for the various printers that
have PPD files here.

1.  Using the KDE or GNOME settings panel, add a printer and manually specify the PPD file.
2.  Select the PPD file in the repo that matches your EPSON thermal printer
3.  Copy rastertotmt to /usr/lib/cups/filter
5.  Print a test page
