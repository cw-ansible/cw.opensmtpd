<!--

---
lang: american
---
-->

[![Build Status](https://travis-ci.org/cw-ansible/cw.opensmtpd.svg?branch=master)](https://travis-ci.org/cw-ansible/cw.opensmtpd)
[![Tweet this](http://img.shields.io/badge/%20-Tweet-00aced.svg)](https://twitter.com/intent/tweet?tw_p=tweetbutton&via=renard_0&url=https%3A%2F%2Fgithub.com%2Fcw-ansible%2Fcw.opensmtpd&text=Install%20and%20configure%20%23OpenSMTPD%20using%20%23Ansible.%20CC%20%40OpenSMTPD)
[![Follow me on twitter](http://img.shields.io/badge/Twitter-Follow-00aced.svg)](https://twitter.com/intent/follow?region=follow_link&screen_name=renard_0&tw_p=followbutton)


# OpenSMTPd

Install and configure [OpenSMTPd](https://www.opensmtpd.org/).


## Usage

Include the `cw.opensmtpd` module to your playbook.


## Description

The *OpenSMTPd* is pretty simple meanwhile it is updated to force aliases to
be routed to an fully qualified (if existing) recipient and only relay mail
from local connections.

If `opensmtpd_smarthost` is defined it is used as a smathost for delivery.


## Configuration

See specific documentation in `defaults/main.yml`



## Copyright

Author: Sébastien Gross `<seb•ɑƬ•chezwam•ɖɵʈ•org>` [@renard_0](https://twitter.com/renard_0)

License: WTFPL, grab your copy here: http://www.wtfpl.net
