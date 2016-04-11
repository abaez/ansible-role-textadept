Role Name
=========
[![license][2i]][2p]
[![twitter][3i]][3p]

Install my favorite texteditor; [Textadept][4]

Description
-----------

I tend to use [Textadept][4] for quite a number of choices in text editing. It's my go to texteditor. However, the texteditor that can does not have the great support I would enjoy for it when doing a new install. This role rectifies that wrong. The texteditor is installed with all the modules I tend to use and configurations I like to have for a full setup. As such, the role provisions specifically to the needs of a heavy user of the product. You can however navigate through the *yaml* files, of the role, to get what you desire as well.

Role Variables
--------------

A couple of variables to note for use:

* ta: holds textadept configurations
  * src: the location for  the textadept install
  * version: the version of textadept to install

* user: holds user information
  * name: the name of the user for the provisioned client.
  * home: home of the user.


Requirements
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Usage
-----

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

``` yaml
- hosts: servers
    roles:
        - { role: username.rolename, x: 42 }
```

Author Information
------------------

[Alejandro Baez][1]

[1]: https://keybase.io/baez
[2i]: https://img.shields.io/badge/license-BSD_2-green.svg
[2p]: ./LICENSE
[3i]: https://img.shields.io/badge/twitter-a_baez-blue.svg
[3p]: https://twitter.com/a_baez
[4]: http://foicica.com/textadept
