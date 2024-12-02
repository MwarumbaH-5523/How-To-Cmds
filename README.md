# How-To-Cmds
Resteps to Check

Steps To ssh
  cd ~/.ssh_rsa
  cat id_rsa.pub

Pass Password Manager Set-up with Gpg
    cmd : pass init "Gpg Key"
    creating the gpg key
    - gpg --full-generate-key (apply defaults options & set key expiration to 0 - not expiring)
    - cd .gnupg
    - touch gpg-agent.conf
    edit - vim gpg-agent.conf
           - pinentry-program /run/current-system/sw/bin/pinentry-qt (:wq to exit vim)
    - gpgconf --reload gpg-agent       
    - cd ~ gpg --list-secret-keys --keyid-format LONG
    - copy rsa/"gpg key"
    - pass init "gpg key"
    - cmd pass
      - pass insert Site/example.com (manually enter the password) or
      - pass generate Site/example2.com *n characters*(auto generate the password)

    

  
