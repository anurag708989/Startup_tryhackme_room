# Startup_tryhackme_room
room related to gobuster, wireshark 
### Startup


## nmap result:

PORT   STATE SERVICE <br>
21/tcp open  ftp <br>
22/tcp open  ssh <br>
80/tcp open  http <br>



### gobuster result:

/files










what the website:port80 saying

No spice here!

Please excuse us as we develop our site. We want to make it the most stylish and convienient way to buy peppers. Plus, we need a web developer. BTW if you're a web developer, contact us. Otherwise, don't you worry. We'll be online shortly!

— Dev Team



notice.txt:Whoever is leaving these damn Among Us memes in this share, it IS NOT FUNNY. People downloading documents from our website will think we are a joke! Now I dont know who it is, but Maya is looking pretty sus.


found ftp upload 
![](/recipe.png)


### then uploading php reverse shell and turning a netcat listner


![](/uploading_reverse_shell.png)
found some credentials from wireshark:
www-data@startup:/home$ cd lennie
cd lennie
bash: cd: lennie: Permission denied
www-data@startup:/home$ sudo -l
sudo -l
[sudo] password for www-data: c4ntg3t3n0ughsp1c3





![](/gaining_shell_on_server.png)






root flag:THM{f963aaa6a430f210222158ae15c3d76d}






