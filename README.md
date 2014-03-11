chef-rails
==========

Chef repo with rvm, ruby2.0, rails, postgres, nodejs, and redis

# How to use #

```bash
brew install ssh-copy-id
ssh-copy-id -i [~/.ssh/id_rsa.pub] [user@]host

bundle install

berks install

knife solo prepare [user@]host

knife solo cook [user@]host
```


