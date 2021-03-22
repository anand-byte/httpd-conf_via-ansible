# httpd-conf_via-ansible
#httpd service of apache webserver is configured via ansible-playbook. The restart option of service module if not idompotent in nature and so the service is restarted even if there is no change in thecong file of httpd.
#To make it idempotent we use two option notify and handlers.(For moredetail go throgh playbook)
