# The MiSTer Manuals DB - Nintendo Famicom Disk System

This is a database for the MiSTer project that downloads the English manuals in .pdf form for the Nintendo Famicom Disk System to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

Or download this .ini file and put it in /media/fat https://github.com/ajgowans/manualsdb-fds/blob/db/downloader_ajgowans_manualsdb-fds.ini


```ini
[ajgowans/manualsdb-fds]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-fds/db/db.json.zip

