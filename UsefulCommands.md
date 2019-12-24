     
     #Git Alias for add commit push
     git config --global alias.acp '!f() { git add -A && git commit -m "$@" && git push; }; f'

     # Deleting multiple git branches`
     git branch | grep '$branch_filter' <branches you want to be deleted> | xargs git branch -D
 
     # mac touch id for sudo
     # edit /etc/pam.d/sudo
     auth sufficient pam_tid.so
