Building the Homogenius.com web front end and deploying Application using Ansible Playbooks.
-------------------------------------------

These playbooks require Ansible 2.5

Populate the inventory host groups as follows:

	[dreamhost]
	treutlan.dreamhost.com

	[synology]
	10.0.1.10

The stack can be deployed using the following command:

        ansible-playbook -i hosts site.yml

Once done, you can check the results by browsing to http://homogenius.com

You should see a simple test page based upon the HTML5 boilerplate template.
