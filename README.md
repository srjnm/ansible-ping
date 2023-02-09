# ansible-ping

What ansible does:

* Ping the control node
* Create ansible directory if not exists
* Copy playbook, inventory and config file
* Run the playbook from control node
    * Control node pings all the managed nodes
* Display the output from control node