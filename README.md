# Log4Shell-Automated
This is an automated script to scan for Log4J vulnerabilities. This is based off of the Datto script. 

The Datto script is here: https://github.com/datto/log4shell-tool

I have simply made the script automated where you only need to run the powershell script itself. It does the heavy lifting. You can also have each server email you if it finds anything. 

All the user variables are at the top. The email portion is setup to use AppPassword however should you want to use the secure application model you can do so. Though you need to do your own leg work. 
