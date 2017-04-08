Mastodon | Rail de cake instance
========

### About 
**Mastodon** is a free, open-source social network server. A decentralized solution to commercial platforms, it avoids the risks of a single company monopolizing your communication. Anyone can run Mastodon and participate in the social network seamlessly.
[Github of the Mastodon project.](https://github.com/tootsuite/mastodon)

#### About this repository
This repository will contain the **client app** of the *Rail de cake* Mastodon instance who is hosted at [masto.raildecake.fr](masto.raildecake.fr).
The purpose of this repo is to list and give the source code of the customized Rail de Cake Mastodon app. 

### Added Features 
#### Local Timeline :
- Renamed the **Community Timeline** to **The Cake Community**
- Change the default icon (a bunch of peoples) by a **cake** (the birthday-cake of font-awesome)
- The 4 columns take all the width of the screen now 

### Install 
1. Login as mastodon
2. Git clone the project
3. Make a backup of the live project just in case. Copy the content of the cloned repo into the live folder with **cp**
4. cd into the live directory and precompile assets with :
```
RAILS_ENV=production bundle exec rails assets:precompile
```
5. Restart the mastodon-web service with a root capable account :
```
sudo systemctl restart mastodon-web.service
```


### Contact 
If you have any questions feel free to open an [issue](https://github.com/shug0/raildecake-mastodon/issues) or to **Toot** me : [shug0@masto.raildecake.fr](https://masto.raildecake.fr/@shug0).

See you in the fediverse friends ;-)
