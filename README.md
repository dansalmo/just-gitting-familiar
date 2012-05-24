just-gitting-familiar
=====================

Just for getting familiar with git and github

I created an account and installed GitHub for Windows
Found that it modifies Power Shell to display the Git branch in the prompt.  
Something I had previously wished for.  Should have wished for world peace instead.

Found this cool utility called posh-git to add the feature to power shell:
Just had to run these two commands at the power shell prompt:

  (new-object Net.WebClient).DownloadString("http://psget.net/GetPsGet.ps1") | iex
  install-module posh-git

and then close and re-open power shell.

What happens if I edit directly on Github?  I found out about it locally with git status.
