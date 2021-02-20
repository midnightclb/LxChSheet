# LxChSheet
Useful linux commands

##Find latest added files in a directory
List and show latest file at the end
ls -Art | tail

Shows the last file
ls -Art | tail -n 1

##Combine
Combine 2 similar csv files
cat *.csv >combined.csv

##Generate SSH keys
ssh keygen -t rsa -b 4096 -C "your@email.com"

##Copy to clipboard
pbcopy <  ~/dest/to/file