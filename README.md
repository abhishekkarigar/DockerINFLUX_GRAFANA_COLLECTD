download the zip or git clone

i have tested this using Docker ToolBox on windows
make sure to run it inside the C Drive as it is automatically (default) mounted


fire up the terminal

$ docker-compose up -d --build
 
open the browser 
http://$docker-machine ip:3000/login


add datasource 
url: http://docker-machine ip:8086
database: collectd

open new dashboard--> add panel --> add graph 