Role Name
=========

Install Windows Web Server and management tools

Requirements
------------

Windows Server 2016 - Windows Server 2019 or above

Role Variables
--------------
<p>**wiw_iis_message:** Message to display in index.html</p>
<p>**wiw_index_dest:** Path to index.html</p>

Extra Vars
--------------
<p>**wiw_iis_action:**</p>
<p>**present** (install IIS)</p>
<p>**absent**  (uninstall IIS)</p>

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: Windows servers
      roles:
         - { role: windows_install_web_server }

License
-------

BSD

Author Information
------------------

Enrique Moreno Velasco - (Enrique.Moreno.Velasco@itnow.es)