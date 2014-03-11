chef-rails
==========

Chef repo with rvm, ruby 2.0, rails 4, postgres, nodejs, and redis

# How to use #

Prepare environment:

```bash
brew install ssh-copy-id
ssh-copy-id -i [~/.ssh/id_rsa.pub] [user@]host

bundle install

berks install

knife solo prepare [user@]host
```

Install rvm, nodejs, ruby 2.0, rails, postgres, and redis

1. Copy the content of template.jso_n
2. Go to chef-rails/nodes/[host].json and paste the content of the template.jso_n file
3. Run ```knife solo cook [user@]host```





