# Ansible Role - Create a www vhost

#### Variables

* use_php: includes role php if set to true (default: false)
* use_perl: installs mod-perl2 if set to true (default: false)
* vhost_ssl_only: configures redirection to https if set to true (default: false)
* vhost_ssl_certificate: path to ssl certificate for https (default: "/etc/ssl/certs/ssl-cert-snakeoil.pem")
* vhost_ssl_key: path to ssl key for https (default: "/etc/ssl/private/ssl-cert-snakeoil.key")
* vhost_user_shell: set the vhost user shell (default: /bin/false)
* vhost_user_bash_files: create .bash_history, .bashrc and .viminfo (default: false)
