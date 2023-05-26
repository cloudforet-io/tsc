# Overview

OWNERS files are used to designate responsibility over different pars of the Cloudforet codebase.
Today, we use them to assign the reviewer and approver roles.

# OWNERS spec

OWNERS files are in YAML format and support the following keys:

* approvers: a list of GitHub usernames
* reviewers: a list of GitHub usernames

All users are expected to be assignable. In GitHub terms, this means they must be members of the organization to which the repo belongs.

A typical OWNERS file looks like:

~~~
# See the OWNERS docs at https://github.com/cloudforet-io/tsc/blob/master/OWNERS.md

approvers:
  - alice
  - bob
revierwers:
  - carol
~~~

# Maintaining OWNERS files

OWNERS files should be regularly maintained.

We encourage people to self-nominate, self-remove or switch to emeritus from OWNERS files vi PR's.

Bad examples of OWNERS usage:

* OWNERS files that have a single person as both approver and reviewer
* OWNERS files that haven't been touched in over 6 months
* OWNERS files that have non organization members present

Good examples of OWNERS usage:

* there are more reviewers than approvers
* the approvers are not in the reviewers section
* OWNERS files that are regularly updated (at least once per release)
