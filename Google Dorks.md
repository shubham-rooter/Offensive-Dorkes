Google Dorks

# Google Hacking made easy
https://pentest-tools.com/information-gathering/google-hacking#

# Search for documents on popular clouds
site:drive.google.com <searchterm>
site:dl.dropbox.com <searchterm>
site:s3.amazonaws.com <searchterm>
site:onedrive.live.com <searchterm>
site:cryptome.org <searchterm>

 # Admins credentials
 intext:company_keyword & ext:txt | ext:sql | ext:cnf | ext:config | ext:log & intext:"admin" | intext:"root" | intext:"administrator" & intext:"password" | intext:"root" | intext:"admin" | intext:"administrator"

# Look for domains indexed by others website
site:bgp.he.net inurl:ndd
site:dnslookup.fr inurl:ndd

# Get information on the internal organization
sites:cadres.apec.fr direction <SOCIETE>

# Financial reports
"périmètre de consolisation"|"rapport de référence"|"rapport annuel" filetype:pdf

# When you use the Google Dork:  site:*.example.com, NEVER forget to check
site:*.*.example.com
site:*.*.*.example.com 

# Google Funny dorks
site:http://trello.com  site:*/boards
site:http://trello.com  password + admin OR username

# Recon to find sensivite data
site:http://ideone.com  | site:http://codebeautify.org  | site:http://codeshare.io  | site:http://codepen.io  | site:http://repl.it  | site:http://justpaste.it  | site:http://pastebin.com  | site:http://jsfiddle.net  | site:http://trello.com  "$TARGET"

# Piwik Anonymous Access
inurl:token_auth inurl:anonymous
