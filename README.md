# Wordpress-Revslider-upload-shell
Wordpress Revslider upload shell

# Yapmanız gerekenler ; 

sunucuya dosyaları çekin. 
list.txt ve sites.txt diye dosya olusturun. düşenler sites.txt gelicek 
google de bu dorkları aratın ve list.txt kaydedin 

dork : 

inurl:wp-content/plugins/revslider/
inurl:revslider
inurl:revslider_admin.php
inurl:revslider_front.php
inurl:plugins/revslider/
intext:Powered by Revslider
intitle:"Index Of/ revslider""
intitle:"Index Of/wp-content/plugins/revslider"
intitle:"Index Of/admin/revslider"
intitle:"Index Of/fr/revslider"
intitle:"Index Of/en/revslider"
intitle:"Index Of/us/revslider"
intitle:"Index Of/ar/revslider"
intitle:"Index Of/es/revslider"
intitle:"Index Of/de/revslider"

sonrası 
perl rav.pl list.txt 
dir kg 
