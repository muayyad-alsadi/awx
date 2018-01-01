[![Run Status](https://api.shippable.com/projects/591c82a22f895107009e8b35/badge?branch=devel)](https://app.shippable.com/github/ansible/awx)

AWX
===

AWX provides a web-based user interface, REST API, and task engine built on top of [Ansible](https://github.com/ansible/ansible). It is the upstream project for [Tower](https://www.ansible.com/tower), a commercial derivative of AWX.  

To learn more about using AWX, and Tower, view the [Tower docs site](http://docs.ansible.com/ansible-tower/index.html).

The AWX Project Frequently Asked Questions can be found [here](https://www.ansible.com/awx-project-faq).

Quick Start
-----------

You can start by deploying all-in-one `AWX` using docker compose:

```
mkdir awx && cd awx
curl -sSL -o docker-compose.yml https://gist.githubusercontent.com/muayyad-alsadi/4f2db7a0a5ed4e6b8da0033cb1da47ab/raw/ed44a5d5679b2be241fbf9b00f399dfcf30bef94/docker-compose.yml
docker-compose up
```

For more details deployment options, building your own AWX images, your custom branding, ..etc.
please view the [Install guide](./INSTALL.md).

Contributing
------------

- Refer to the [Contributing guide](./CONTRIBUTING.md) to get started developing, testing, and building AWX.
- All code submissions are done through pull requests against the `devel` branch.
- All contributors must use git commit --signoff for any commit to be merged, and agree that usage of --signoff constitutes agreement with the terms of [DCO 1.1](./DCO_1_1.md)
- Take care to make sure no merge commits are in the submission, and use `git rebase` vs `git merge` for this reason.
- If submitting a large code change, it's a good idea to join the `#ansible-awx` channel on irc.freenode.net, and talk about what you would like to do or add first. This not only helps everyone know what's going on, it also helps save time and effort, if the community decides some changes are needed.

Reporting Issues
----------------

If you're experiencing a problem, we encourage you to open an issue, and share your feedback. But before opening a new issue, we ask that you please take a look at our [Issues guide](./ISSUES.md).

Code of Conduct
---------------

We ask all of our community members and contributors to adhere to the [Ansible code of conduct](http://docs.ansible.com/ansible/latest/community/code_of_conduct.html). If you have questions, or need assistance, please reach out to our community team at [codeofconduct@ansible.com](mailto:codeofconduct@ansible.com)   

Get Involved
------------

We welcome your feedback and ideas. Here's how to reach us:

- Join the `#ansible-awx` channel on irc.freenode.net
- Join the [mailing list](https://groups.google.com/forum/#!forum/awx-project) 
- [Open an Issue](https://github.com/ansible/awx/issues)

License
-------

[Apache v2](./LICENSE.md)

