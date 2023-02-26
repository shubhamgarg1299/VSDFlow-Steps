# VSDFlow-Steps
In this repository, I have discussed the steps with the screenshots to install opensource EDA Tools for VLSI Design.

Steps to Install on Ubuntu:

1) Open Terminal:
![VirtualBox_ubuntu_two_26_02_2023_11_53_56](https://user-images.githubusercontent.com/48863499/221396702-9c09b248-926b-4e79-8641-b1fd287f5de5.png)

2) Install Git: 
sudo apt-get install git
![VirtualBox_ubuntu_two_26_02_2023_12_04_23](https://user-images.githubusercontent.com/48863499/221396722-947402ce-4bfb-434b-a01e-117a3e0092f5.png)

3) Clone the following repository:
git clone https://github.com/kunalg123/vsdflow.git
![VirtualBox_ubuntu_two_26_02_2023_12_08_03](https://user-images.githubusercontent.com/48863499/221396772-dc482403-40b2-446b-9efa-07a8cb8eeecd.png)

4) Change Directory to vsdflow:
cd vsdflow
![VirtualBox_ubuntu_two_26_02_2023_12_08_25](https://user-images.githubusercontent.com/48863499/221396778-b48e550f-36a1-4db2-ac51-ad327c70cf45.png)

5) Now we can see the following items in vsdflow directory:
![VirtualBox_ubuntu_two_26_02_2023_12_08_51](https://user-images.githubusercontent.com/48863499/221396810-261bd355-5cee-4b36-a903-1c4b3095dbcf.png)

6) chmod 777 opensource_eda_tool_install.sh
![VirtualBox_ubuntu_two_26_02_2023_12_09_07](https://user-images.githubusercontent.com/48863499/221396815-9b63c762-2cf6-471e-9c67-8e70fca67239.png)

6) ./opensource_eda_tool_install.sh 
![VirtualBox_ubuntu_two_26_02_2023_12_09_25](https://user-images.githubusercontent.com/48863499/221396823-e435a3de-112c-45b9-b27d-1be8411129b4.png)
![VirtualBox_ubuntu_two_26_02_2023_12_14_08](https://user-images.githubusercontent.com/48863499/221396839-d8f88d8e-7e88-4c95-9386-efe92764fa38.png)


List of Tools installed:
a) Yosys - RTL Synthesis
b) blifFanout - High fanout net (HFN) synthesis
c) graywolf - Placement
d) qrouter - Detailed routing
e) magic - VLSI Layout tool
f) netgen - LVS
g) OpenTimer and OpenSTA - Static timing analysis tool

Now test some tools:

a) Yosys
![VirtualBox_ubuntu_two_26_02_2023_12_14_25](https://user-images.githubusercontent.com/48863499/221396935-9667e9ff-66a1-4cdd-a3aa-39a087aa10ed.png)
![VirtualBox_ubuntu_two_26_02_2023_12_14_36](https://user-images.githubusercontent.com/48863499/221396948-67ce038f-1307-4ed5-9298-6aeb6db07eeb.png)

b) Magic
![VirtualBox_ubuntu_two_26_02_2023_12_14_51](https://user-images.githubusercontent.com/48863499/221396958-c9bbd8a5-026e-4666-9003-b4c534cc6197.png)
![VirtualBox_ubuntu_two_26_02_2023_12_15_11](https://user-images.githubusercontent.com/48863499/221396963-8c2994a6-feef-4366-a895-dc4b24c8509c.png)

c) qflow and qflowgui
![VirtualBox_ubuntu_two_26_02_2023_12_16_22](https://user-images.githubusercontent.com/48863499/221396983-e6cd880d-0b5d-4b1b-ac09-a7c11a9172e2.png)
![VirtualBox_ubuntu_two_26_02_2023_12_16_40](https://user-images.githubusercontent.com/48863499/221396988-e028d9e7-16f1-4d9c-b008-9d8341e2c5b9.png)
![VirtualBox_ubuntu_two_26_02_2023_12_16_49](https://user-images.githubusercontent.com/48863499/221396992-2ebdc2a9-1f52-44e6-8706-cb2ca9baeb08.png)

Steps to test vsdflow on Ubuntu
1) cd outdir_spi_slave
2) qflow display spi_slave
