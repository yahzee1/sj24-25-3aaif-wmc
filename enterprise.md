# mount enterprise

smbclient --user=htl-wien5.schule/grafg --password=extremgeheim -L //enterprise

mount.cifs //enterprise/administration /enterprise/administration -o user=grafg,dom=htl-wien5.schule,pass=extremgeheim,vers=3,uid=1001,gid=1001

mount.cifs //enterprise/ausbildung /enterprise/ausbildung -o user=grafg,dom=htl-wien5.schule,pass=extremgeheim,vers=3,uid=1001,gid=1001
