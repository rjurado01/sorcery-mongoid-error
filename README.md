# Sorcer Mongoid Error

Project to reproduce error with sorcery gem and mongoid.

## Steps to get error

```shell
$ rails c

> User
NoMethodError: undefined method `authenticates_with_sorcery!' for User:Class
	from /home/user/sorcery_mongoid_error/app/models/user.rb:3:in `<class:User>'
	from /home/user/sorcery_mongoid_error/app/models/user.rb:1:in `<top (required)>'
  ...
```
