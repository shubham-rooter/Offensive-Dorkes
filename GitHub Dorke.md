Github Dorks

https://gist.github.com/jhaddix/77253cea49bf4bd4bfd5d384a37ce7a4

# Github dorks work a lot with filename and extension
# You can build search like this
filename:bashrc
extension:pem
langage:bash

# Possible to search terms and use these keywords
# Some usefull examples
extension:pem private # Private SSH Keys
extension:sql mysql dump # MySQL dumps
extension:sql mysql dump password # MySQL dumps with passwords
filename:wp-config.php # Wordpress config file
filename:.htpasswd # .htpasswd
filename:.git-credentials # Git stored credentials
filename:.bashrc password # .bashrc files containing passwords
filename:.bash_profile aws # AWS keys in .bash_profiles
extension:json mongolab.com # Keys/Credentials for mongolab
HEROKU_API_KEY language:json # Heroku API Keys
filename:filezilla.xml Pass # FTP credentials
filename:recentservers.xml Pass # FTP credentials
filename:config.php dbpasswd # PHP Applications databases credentials
shodan_api_key language:python # Shodan API Keys (try others languages)
filename:logins.json # Firefox saved password collection (key3.db usually in same repo)
filename:settings.py SECRET_KEY # Django secret keys (usually allows for session hijacking, RCE, etc)
