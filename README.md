cookiecutter-salt-formula
=========================

[Cookiecutter][cookiecutter] template for creating an [saltstack][saltstack] formula
alongside [Test-Kitchen][test-kitchen].

I have grown used to, and love, developing Chef Cookbooks using a TDD
approach with [Test-Kitchen][test-kitchen] and [Serverspec][serverspec] and
wanted to develop my saltstack formulas in a similar fashion.  This
[Cookiecutter][cookiecutter] template quickly scaffolds everything needed to TDD
an [Saltstack][saltstack] role.

Usage
-----

Generate an saltstack role TDD-syle with:

    cookiecutter https://github.com/eedgar/cookiecutter-salt-formula

Once the Saltstack role project has been setup `cd` into it and get the Rubygems
needed for running [Test-Kitchen][test-kitchen] with:

    bundle install

Edit the `.kitchen.yml` to suit your specific needs, e.g. change the platform - the
template defaults to CentOS 7

If you're not familiar with [Test-Kitchen][test-kitchen] just run:

    bundle exec kitchen -h

[cookiecutter]:       https://github.com/audreyr/cookiecutter
[saltstack]:          http://www.saltstack.com
[test-kitchen]:       https://github.com/test-kitchen/test-kitchen
[serverspec]:         http://serverspec.org/
