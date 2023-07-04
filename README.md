# bounty-dorking

# Descirption
This collection of dorkings is essential for any security researcher performing bug bounty, as it offers a rich and updated library of specialized search queries, which allow to identify quickly and efficiently potential vulnerabilities, hidden entry points, and unprotected sensitive information on the Web.

# Bug Bounty Dorkings

## PHP extension w/ parameters
site:jim.com ext:php inurl:?

graphql
 
## Disclosed XSS and Open Redirects
site:openbugbounty.org inurl:reports intext:"jim.com"

 
 
## Juicy Extensions
site:"jim.com" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess

 
 
## Code Leaks
site:pastebin.com "jim.com"
site:jsfiddle.net "jim.com"
site:codebeautify.org "jim.com"
site:codepen.io "jim.com"

 
 
## Cloud Storage
site:s3.amazonaws.com "jim.com"
site:blob.core.windows.net "jim.com"
site:googleapis.com "jim.com"
site:drive.google.com "jim.com"
site:dev.azure.com "jim.com"
site:onedrive.live.com "jim.com"
site:digitaloceanspaces.com "jim.com"
site:sharepoint.com "jim.com"
site:s3-external-1.amazonaws.com "jim.com"
site:s3.dualstack.us-east-1.amazonaws.com "jim.com"
site:dropbox.com/s "jim.com"
site:box.com/s "jim.com"
site:docs.google.com inurl:"/d/" "jim.com"

 
 
## XSS prone parameters
inurl:q= | inurl:s= | inurl:search= | inurl:query= inurl:& site:jim.com

 
 
## Open Redirect prone parameters
inurl:url= | inurl:return= | inurl:next= | inurl:redir= inurl:http site:jim.com

 
 
## SQLi Prone Parameters
inurl:id= | inurl:pid= | inurl:category= | inurl:cat= | inurl:action= | inurl:sid= | inurl:dir= inurl:& site:jim.com

 
 
## SSRF Prone Parameters
inurl:http | inurl:url= | inurl:path= | inurl:dest= | inurl:html= | inurl:data= | inurl:domain= | inurl:page= inurl:& site:jim.com

 
 
## LFI Prone Parameters
inurl:include | inurl:dir | inurl:detail= | inurl:file= | inurl:folder= | inurl:inc= | inurl:locate= | inurl:doc= | inurl:conf= inurl:& site:jim.com

 
 
## RCE Prone Parameters
inurl:cmd | inurl:exec= | inurl:query= | inurl:code= | inurl:do= | inurl:run= | inurl:read= | inurl:ping= inurl:& site:jim.com

 
 
## High % inurl keywords
inurl:config | inurl:env | inurl:setting | inurl:backup | inurl:admin | inurl:php site:jim.com

 
 
## Sensitive Parameters
inurl:email= | inurl:phone= | inurl:password= | inurl:secret= inurl:& site:jim.com

 
 
## JFrog Artifactory
site:jfrog.io "jim.com"

 
 
## Firebase
site:firebaseio.com "jim.com"

 
 
## API Docs
inurl:apidocs | inurl:api-docs | inurl:swagger | inurl:api-explorer site:"jim.com"

 
 
## File upload endpoints
site:jim.com ”choose file”