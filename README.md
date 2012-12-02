# Module gitlab

* Tested successfully with Gitlab 3.1.0 [319f0c3]

[GitLab](http://gitlabhq.com) is a free project and repository management application

A ['Puppet Module'](http://docs.puppetlabs.com/learning/modules1.html#modules)
is a collection of related content that can be used to model the configuration
of a discrete service.

This module is based on the admin guides for [gitlab](https://github.com/gitlabhq/gitlabhq/wiki), [stable](https://github.com/gitlabhq/gitlabhq/blob/stable/doc/installation.md) version.

## Testing with vagrant

### Using Debian Wheezy (the default)

$ vagrant up
or
$ OS=debian7 vagrant up

### Using Centos 6

$ OS=centos6 vagrant up

### Using Ubuntu Quantal Quetzal (12.10)

$ OS=ubuntu vagrant up

## Test gitlab
- add the ip and name to your /etc/hosts file (192.168.111.10 gitlab.localdomain.local)
- access via your browser under the hostname (e.g. http://gitlab.localdomain.local)
- **Login**: admin@local.host
- **Password**: 5iveL!fe

1. Add an ssh key to your account, or create another account
2. Create a project
3. Play !
