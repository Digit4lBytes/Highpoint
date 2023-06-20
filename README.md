# Highpoint V 0.1



# Description
Highpoint is a tool for Google Dork Hacking. All Google dorks in this tool can be found in the GHDB. The creator is not responsible for any misuse of this tool. Please use legally.


# Dependecies
Python 3 </br>
Selenium</br>
Selenium Firefox Webdriver</br>

# Usage
python Highpoint.py <dork> <output_mode> <tld> Tld is optional Tld is the top level domain or target site you wish to dork. Example: .org or nscs.gov

# Output Modes

-f This will put all data into a file in a clean format. </br>
-t This will print all of the information, in an unclean format. URLS and Descriptions. </br>
-c This will format the scraped information cleanly. The URLS will be output in this format: url.com > route > file > ext The > mean / or . Here the unformatted url would be: url.com/route/file.ext </br>

# Available Dorks

-fp for password files. </br>
-av for advisories and vulnerabilities. </br>
-ws for web servers.</br>
-vs for vulnerable servers</br>
-lp for login portals</br>
-fh for footholds.</br>
-vo for various online devices.</br>
-cam for online cameras.</br>
-ji for pii information.</br>
-si for sensitive shopping info.</br>
