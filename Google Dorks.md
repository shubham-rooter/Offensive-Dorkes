   Google Dorks

# Google Hacking made easy
llintext:"Copperfasten Technologies" "Login"

allintext:"Index Of" "cookies.txt"

allintext:@gmail.com filetype:log

ext:php intitle:phpinfo "published by the PHP Group"

ext:sql | ext:txt intext:"-- phpMyAdmin SQL Dump --" + intext:"admin"

ext:txt | ext:log | ext:cfg "Building configuration..."

ext:txt | ext:log | ext:cfg | ext:yml "administrator:500:"

ext:yml | ext:txt | ext:env "Database Connection Information Database server ="

intext:"Connection" AND "Network name" AND " Cisco Meraki cloud" AND "Security Appliance details"

intext:"Healthy" + "Product model" + " Client IP" + "Ethernet"

intext:"Incom CMS 2.0"

intext:"SonarQube" + "by SonarSource SA." + "LGPL v3"

intext:"user name" intext:"orion core" -solarwinds.com

intext:construct('mysql:host

intitle:"Agent web client: Phone Login"

intitle:"Exchange Log In"

intitle:"Humatrix 8"

intitle:"Insurance Admin Login" | "(c) Copyright 2020 Cityline Websites. All Rights Reserved." | "http://www.citylinewebsites.com"

intitle:"NetCamSC*"

intitle:"NetCamSC*" | intitle:"NetCamXL*" inurl:index.html

intitle:"NetCamXL*"

intitle:"Please Login" "Use FTM Push"

intitle:"Powered by Pro Chat Rooms"

intitle:"Sphider Admin Login"

intitle:"Xenmobile Console Logon"

intitle:"index of" "*.cert.pem" | "*.key.pem"

intitle:"index of" "*Maildir/new"

intitle:"index of" "/.idea"

intitle:"index of" "/xampp/htdocs" | "C:/xampp/htdocs/"

intitle:"index of" "Clientaccesspolicy.xml"

intitle:"index of" "WebServers.xml"

intitle:"index of" "anaconda-ks.cfg" | "anaconda-ks-new.cfg"

intitle:"index of" "config.exs" | "dev.exs" | "test.exs" | "prod.secret.exs"

intitle:"index of" "credentials.xml" | "credentials.inc" | "credentials.txt"

intitle:"index of" "db.properties" | "db.properties.BAK"

intitle:"index of" "dump.sql"

intitle:"index of" "filezilla.xml"

intitle:"index of" "password.yml

intitle:"index of" "service-Account-Credentials.json" | "creds.json"

intitle:"index of" "sitemanager.xml" | "recentservers.xml"

intitle:"index of" intext:"apikey.txt

intitle:"index of" intext:"web.xml"

intitle:"index of" intext:credentials

intitle:"index of" inurl:admin/download

intitle:"irz" "router" intext:login gsm info -site:*.com -site:*.net

intitle:"web client: login"

intitle:("Index of" AND "wp-content/plugins/boldgrid-backup/=")

intitle:Login intext:HIKVISION inurl:login.asp?

intitle:index of .git/hooks/

USG60W|USG110|USG210|USG310|USG1100|USG1900|USG2200|"ZyWALL110"|"ZyWALL310"|"ZyWALL1100"|ATP100|ATP100W|ATP200|ATP500|ATP700|ATP800|VPN50|VPN100|VPN300|VPN
000|"FLEX")

jdbc:mysql://localhost:3306/ + username + password ext:yml | ext:javascript -git -gitlab

jdbc:oracle://localhost: + username + password ext:yml | ext:java -git -gitlab

jdbc:postgresql://localhost: + username + password ext:yml | ext:java -git -gitlab

jdbc:sqlserver://localhost:1433 + username + password ext:yml | ext:java

site:*gov.* intitle:index.of db

site:checkin.*.* intitle:"login"

site:ftp.*.*.* "ComputerName=" + "[Unattended] UnattendMode"

site:gov ext:sql | ext:dbf | ext:mdb

site:password.*.* intitle:"login"

site:portal.*.* intitle:"login"

site:sftp.*.*/ intext:"login" intitle:"server login"

site:user.*.* intitle:"login"

