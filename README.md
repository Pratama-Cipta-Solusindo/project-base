
## How to install
- Get a cup of coffee & some nicotines
- Create .env file
- Run command "composer i"
- Run command "npm i"
- Run command "npm run dev"

## Deployment
- Generate deploy key
- Add deploy key
- Create ssh config
- Pull project
- Install

## Troubleshoot
##### The unauthenticated git protocol on port 9418 is no longer supported

```
git config --global url."https://".insteadOf git://
```


## Related

#### SSH config sample
```
Host github-project.com
        Hostname github.com
        IdentityFile=~/.ssh/your_deploy_key
        
Host github-sub-module.com
        Hostname github.com
        IdentityFile=~/.ssh/your__submodule_deploy_key
```

#### Important Links
* [Generate new ssh key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent#generating-a-new-ssh-key)
* [Managing deploy key](https://docs.github.com/en/developers/overview/managing-deploy-keys#deploy-keys)
