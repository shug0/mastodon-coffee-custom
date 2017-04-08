Mastodon | Rail de cake instance
========

### About 
**Mastodon** is a free, open-source social network server. A decentralized solution to commercial platforms, it avoids the risks of a single company monopolizing your communication. Anyone can run Mastodon and participate in the social network seamlessly.
[Github of the Mastodon project.](https://github.com/tootsuite/mastodon)

#### About this repository
This repository will contain the **client app** of the *Rail de cake* Mastodon instance who is hosted at [masto.raildecake.fr](masto.raildecake.fr).
The purpose of this repo is to list and give the source code of the customized rail de cake Mastodon app. 

### Added Features 
#### Local Timeline :
- The **Community Timeline** who is the instance timeline is changed to **The Cake Community**
- The default icon who represent a bunch of peoples is now a **cake** (the birthday-cake of font-awesome)
- The 4 column take all the width of the screen now 

### Install 
1. Connect to the ssh 
2. Git clone next mastodon live folder
3. Copy the content of the cloned repo to the live folder with **cp** (will overwrite files)
4. Launch the precompile command for recompile assets

```
RAILS_ENV=production bundle exec rails assets:precompile
```
5. With a admin account restart the web service 
```
sudo systemctl restart mastodon-web.service
```


### Contact 
If you have any questions feel free to open a [issue](https://github.com/shug0/raildecake-mastodon/issues) or to **Toot Me** here : [shug0@masto.raildecake.fr](https://masto.raildecake.fr/@shug0).

Have nice toot friend of the fediverse !
