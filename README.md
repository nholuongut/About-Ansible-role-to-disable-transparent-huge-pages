# Disable disables Transparent Huge Pages

![](https://i.imgur.com/waxVImv.png)
### [View all Roadmaps](https://github.com/nholuongut/all-roadmaps) &nbsp;&middot;&nbsp; [Best Practices](https://github.com/nholuongut/all-roadmaps/blob/main/public/best-practices/) &nbsp;&middot;&nbsp; [Questions](https://www.linkedin.com/in/nholuong/)
<br/>

===========

This role disables Transparent Huge Pages on Ubuntu server.

Role Variables
--------------

- `disable_thp_init_system`: OS init system (upstart or systemd). (default 'systemd')
- `disable_thp_state`: Desired daemon state after role execution (default: 'started')
- `disable_thp_before_service`: If set, disable THP before this service (Ex: 'mongod')

Example Playbook
----------------

    - hosts: servers
      roles:
        - {
          role: disable_thp,
          disable_thp_before_service: 'mongod'
        }

# 🚀 I'm are always open to your feedback.  Please contact as bellow information:
### [Contact ]
* [Name: nho Luong]
* [Skype](luongutnho_skype)
* [Github](https://github.com/nholuongut/)
* [Linkedin](https://www.linkedin.com/in/nholuong/)
* [Email Address](luongutnho@hotmail.com)

![](https://i.imgur.com/waxVImv.png)
![](Donate.png)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/nholuong)

# License
* Nho Luong (c). All Rights Reserved.🌟
