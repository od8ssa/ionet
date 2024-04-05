1)Register OVH cloud and add payment method to be eligible for free 200$ credits
https://www.ovhcloud.com/en/

2)Create B3-16 instances(3-4 with free credits available)

3)SSH to the created instance and run this command to download preparation script

1) sudo apt install wget -y
2) wget https://github.com/od8ssa/ionet/blob/main/prepare.sh

4)Execute script to create VM for ionet worker depolyment

1) chmod +x prepare.sh
2) ./prepare.sh

5)Reconnect to the instance

6)Open console of the created VM
virsh console ionet
user: user
password: user

Follow the instructions on the io.net website to connect the worker!
