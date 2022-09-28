![email-from-r](https://github.com/cevaboyz/gh-secrets-mail/workflows/email-from-r/badge.svg)

# gh-secrets

The objective of this repository is to show how to use *GitHub Secrets* from Python and R. To do so I wrote two scripts (one in Python and the other in R) with the same purpose: to send an email.  

Sensible information (email addresses and a password) is stored as *GitHub Secrets* and both scripts read it from there. Especifically, these *Secrets* are:

`EMAIL_SENDER`: sender's email address.  
`EMAIL_PASSWORD`: password for sender's email address.  
`EMAIL_RECIPIENT`: recipient's email address.  
