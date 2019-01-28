top -b -n 1 > top.txt
write a cron job for taking snapshots

  top -hv | -bcEHiOSs1 -d secs -n max -u|U user -p pid(s) -o field -w [cols]
top -p 5173 9176 -b -n30 > cron.txt
