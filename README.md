# provisioning_with_vagrant

Provisioning multiple machine with both ansible and shell scripts at same time.

I am provisioning 3 machines for zabbix server with shell script to set root password and ansible playbook to install some basic package which I fill required for me. In your case you can change it.

Lets check out files in my current working directory :

ravikumar@ravikumar-RV409-RV509-RV709 ~/vgrnt_mchns $ tree                                                                          
.                                                                                                                                  
└── zabbix                                                                                                                             
    ├── os_setup_dependency.yml                                                                                                     
    ├── set_root_pass.sh                                                                                                           
    └── Vagrantfile                                                                                                                
                           
                           
1 directory, 3 files                                                                                                                                                      
ravikumar@ravikumar-RV409-RV509-RV709 ~/vgrnt_mchns $ 
