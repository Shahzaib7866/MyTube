# MyTube
MyTube is all about video playing and sharing platform, just like the youtube but with amazing U.I 


PS C:\Users\hp\Desktop\Mytube> cd mytube
PS C:\Users\hp\Desktop\Mytube\mytube> git status
>> 
On branch master
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .gitignore
        README.md
        eslint.config.js
        index.html
        package-lock.json
        package.json
        public/
        src/
        vite.config.js
nothing added to commit but untracked files present (use "git add" to track)

PS C:\Users\hp\Desktop\Mytube\mytube> rm -rf .git

Remove-Item : A parameter cannot be found that matches parameter name      
'rf'.
At line:1 char:4
+ rm -rf .git(rm and rf is linux commands)
+    ~~~
    + CategoryInfo          : InvalidArgument: (:) [Remove-Item], Paramet  
   erBindingException
    + FullyQualifiedErrorId : NamedParameterNotFound,Microsoft.PowerShell  
PS C:\Users\hp\Desktop\Mytube\mytube> cd ..
PS C:\Users\hp\Desktop\Mytube> git add mytube/  
>> 
warning: in the working copy of 'mytube/.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mytube/README.md', LF will be replaced by 
CRLF the next time Git touches it
ced by CRLF the next time Git touches it
warning: in the working copy of 'mytube/index.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mytube/package-lock.json', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mytube/package.json', LF will be replaced 
by CRLF the next time Git touches it
warning: in the working copy of 'mytube/src/App.jsx', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'mytube/src/main.jsx', LF will be replaced 
by CRLF the next time Git touches it
warning: in the working copy of 'mytube/vite.config.js', LF will be replaced by CRLF the next time Git touches it

PS C:\Users\hp\Desktop\Mytube> git commit -m "start of mytube"
Author identity unknown

*** Please tell me who you are.

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'hp@DESKTOP-DJIJH08.(none)')
PS C:\Users\hp\Desktop\Mytube> git config --global user.name "Shahzaib7866"
PS C:\Users\hp\Desktop\Mytube>   git config --global user.email "shehkhan494@gmail.com"
PS C:\Users\hp\Desktop\Mytube> git commit -m "start of mytube"
[master (root-commit) b832d51] start of mytube
 15 files changed, 4613 insertions(+)
 create mode 100644 mytube/.gitignore
 create mode 100644 mytube/README.md
 create mode 100644 mytube/README.md
 create mode 100644 mytube/eslint.config.js
 create mode 100644 mytube/index.html
 create mode 100644 mytube/package-lock.json
 create mode 100644 mytube/package.json
 create mode 100644 mytube/public/icons8-video-96.png
 create mode 100644 mytube/public/vite.svg
 create mode 100644 mytube/src/App.css
 create mode 100644 mytube/src/App.jsx
 create mode 100644 mytube/src/assets/react.svg
 create mode 100644 mytube/src/components/Home.jsx
 create mode 100644 mytube/src/index.css
 create mode 100644 mytube/src/main.jsx
 create mode 100644 mytube/vite.config.js
PS C:\Users\hp\Desktop\Mytube>




