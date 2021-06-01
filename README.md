The repository contains two folders *server1* and *server2*. *server1* and *server2* mainly contain 4 files *set_vxlan, vxlan_create_docker, vxlan_flow_table and vxlan_bdl*.
* ***set_vxlan*** : build vxlan based on ovs.
* ***vxlan_create_docker*** : create a specified number of containers and connect them to ovs.
* ***vxlan_flow_table*** :  realize the flow table configuration of ovs with ***flow_table***.
* ***vxlan_bdl*** : realize the control of link parameters in **multi-process mode**.

else :
* *vxlan_link* : realize the flow table configuration of ovs in **multi-process mode**.
* *flow_table* : a text file that contains zero or more flows in the same syntax, one per line.
* *mapping* : a shared folder about the commands of the control of link parameters for dockers.
