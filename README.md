Role Name
=========

An Ansible role to install the Tor Browser Crawler.

Requirements
------------

This role has been tested with Ansible version 2.1.1.0

Role Variables
--------------

	git_repo: "https://github.com/webfp/tor-browser-crawler.git"
	git_tag: "master"
	dirpath: "~" # Parent directory of the crawler
	dirname: "tor-browser-crawler" # Name of the crawler directory
	virtualenv_path: "~/.virtualenvs/tor-browser-crawler"
	python_executable: "python2.7"

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: parmegv.ansible-tor-browser-crawler, git_repo: " }

License
-------

BSD

Author Information
------------------

Rafael Gálvez Vizcaíno
Ph.D. student at ESAT/COSIC KU Leuven
