Prepare your Ruby on Rails environment with Chef
==========

Chef provisioning configuration for Ruby on Rails.

This will install postgres, redis, rvm, nodejs, ruby and rails.

# How to use #

Prepare the environment:

```bash
brew install ssh-copy-id
ssh-copy-id -i [~/.ssh/id_rsa.pub] [user@]host

bundle install

berks install

knife solo prepare [user@]host
```

Install rvm, nodejs, ruby, rails, postgres, and redis

1. Copy the content of template.jso_n
2. Go to chef-rails/nodes/[host].json and paste the content of the template.jso_n file
3. Run ```knife solo cook [user@]host```





