# Generate ssh key pair
`ssh-keygen -t ed25519 -C "erizon.encina@gmail.com"`

# Configuration example for ssh [~/.ssh/config]
```
Host github.com
    HostName github.com
    User git
    IdentityFile ~/.ssh/personal_key
    IdentitiesOnly yes
```

<b>Remember to define `chmod 600 ~/.ssh/config`</b>
