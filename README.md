Profile picture
=========

Installs account service and configure it to use specified profile picture.

Example Playbook
----------------

    - hosts: desktop
      roles:
         - profile-picture
      vars:
        picture_src: "{{ playbook_dir }}/pictures/profile.jpg"

License
-------

MIT