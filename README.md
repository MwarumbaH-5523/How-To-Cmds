# How-To-Cmds
Resteps to Check

Steps To ssh
  cd ~/.ssh_rsa
  cat id_rsa.pub

Pass Password Manager Set-up with Gpg
    creating the gpg key
    - gpg --full-generate-key (apply defaults options & set key expiration to 0 - not expiring)
    - gpg --list-keys
    cmd : pass init "Gpg Key" 
    - cmd pass
      - pass insert Site/example.com (manually enter the password) or
      - pass generate Site/example2.com *n characters*(auto generate the password)
      - pass example.com (displays the passwords for the site)
      - passmenu (copied site passwd to the terminal)

   Creating Pass in Git (link : https://youtu.be/7t5M4FXqs9E?si=afTioaC7DiDL_Uaz)
   cmd : pass git init (creates password store for git dir)
     - cd .password-store/ (enables one to run git cmds)
     - git.log (interacts with gits cmds this commits the passwords to github)
  
 Docker Desktop Installation and set-up on Linux Machine.
  - Documentation link : https://docs.docker.com/desktop/setup/install/linux/
   
  

  
