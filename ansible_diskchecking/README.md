In this ansible playbook i have to designed to display the Linux Filesystem details
File Systems like:
- /
- /boot
- /run

These i have taken for example. if you want you can edit the code for your own purpose. 

Here in this playbook i used set_fact variable to store the command output and passing through the jinja2 template after that the
template will generate the HTML Report. 

I appended the color coding based on the thershold it will display like if the mentioned file system goes beyond 75+ then it will dsipaly
the RED Color and in between 50 to 75 then it will display the ORANGE Color and below one it will display the GREEN Color 
