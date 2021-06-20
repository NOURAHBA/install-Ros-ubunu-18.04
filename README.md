# install-Ros-ubuntu-18.04
the 1st task in First week in internship at Smart Methods
## 1-install Vmwaer
you have to install Vmwaer from (https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html) as shown below
<img width="949" alt="Capture" src="https://user-images.githubusercontent.com/86157318/122646206-ad37a680-d126-11eb-81e1-73301c454486.PNG">
### * After downloading, open the file, and follow these steps
<img width="379" alt="Capture1" src="https://user-images.githubusercontent.com/86157318/122646355-61d1c800-d127-11eb-8626-555fe8a497ed.PNG">
<img width="369" alt="Capture2" src="https://user-images.githubusercontent.com/86157318/122646774-a65e6300-d129-11eb-915a-c263f728914b.PNG">
<img width="370" alt="Capture3" src="https://user-images.githubusercontent.com/86157318/122646834-ee7d8580-d129-11eb-91bb-81272098d88c.PNG">
<img width="369" alt="Capture4" src="https://user-images.githubusercontent.com/86157318/122646851-fdfcce80-d129-11eb-8ee8-02f33a5dd8e9.PNG">
<img width="367" alt="Capture5" src="https://user-images.githubusercontent.com/86157318/122646857-0a812700-d12a-11eb-8ee4-3d5c74dc0915.PNG">
<img width="369" alt="Capture6" src="https://user-images.githubusercontent.com/86157318/122646872-1cfb6080-d12a-11eb-9543-aa8b8c884e03.PNG">
<img width="371" alt="Capture7" src="https://user-images.githubusercontent.com/86157318/122646892-2dabd680-d12a-11eb-913f-c77d93ec0287.PNG">

## 2-install ubuntu
### * dwonload Ubuntu 16.04 from https://releases.ubuntu.com/18.04/ as shown below
<img width="819" alt="Capture" src="https://user-images.githubusercontent.com/86157318/122647114-47015280-d12b-11eb-8b93-9e538be2694c.PNG">
### * click on New Virtual Machine ,and follow these steps
<img width="720" alt="Capture 1" src="https://user-images.githubusercontent.com/86157318/122647209-be36e680-d12b-11eb-9a5b-41634465689b.PNG">
<img width="715" alt="Capture2" src="https://user-images.githubusercontent.com/86157318/122647359-9300c700-d12c-11eb-917e-ef79aa00b52f.PNG">
<img width="721" alt="Capture 3" src="https://user-images.githubusercontent.com/86157318/122647372-a14ee300-d12c-11eb-8715-c23fb3c7f3ea.PNG">
<img width="719" alt="Capture 4" src="https://user-images.githubusercontent.com/86157318/122647381-af9cff00-d12c-11eb-9bb8-166de458aaa8.PNG">
<img width="721" alt="Capture 5" src="https://user-images.githubusercontent.com/86157318/122647393-bcb9ee00-d12c-11eb-973a-7ae2dce3154e.PNG">
<img width="719" alt="Capture 6" src="https://user-images.githubusercontent.com/86157318/122647411-c9d6dd00-d12c-11eb-8cf1-be63d72a7a63.PNG">
<img width="719" alt="Capture 7" src="https://user-images.githubusercontent.com/86157318/122647453-f559c780-d12c-11eb-80aa-5fa2b1c5b439.PNG">
<img width="556" alt="Capture 8" src="https://user-images.githubusercontent.com/86157318/122647493-276b2980-d12d-11eb-9592-53017c2a3706.PNG">
<img width="553" alt="Capture 9" src="https://user-images.githubusercontent.com/86157318/122647538-4bc70600-d12d-11eb-85a2-9708fd17ac17.PNG">
<img width="582" alt="Capture 10" src="https://user-images.githubusercontent.com/86157318/122647601-85980c80-d12d-11eb-8537-c4d0fcdfb7ff.PNG">
<img width="555" alt="Capture 11" src="https://user-images.githubusercontent.com/86157318/122647613-98aadc80-d12d-11eb-9383-edf86ef510a2.PNG">
<img width="717" alt="Capture 12" src="https://user-images.githubusercontent.com/86157318/122647627-b9733200-d12d-11eb-89b3-52eb4cbd86fd.PNG">
### * click Power on this Virtual Machine
<img width="719" alt="Capture 13" src="https://user-images.githubusercontent.com/86157318/122647683-1ff85000-d12e-11eb-828d-8a25121fbc92.PNG">
#### * install Ubuntu
<img width="958" alt="Capture 14" src="https://user-images.githubusercontent.com/86157318/122680592-a24d4680-d1f8-11eb-88e3-df7fd45d42f1.PNG">
#### * install 3rd part flash,..ect 
<img width="958" alt="Capture 16" src="https://user-images.githubusercontent.com/86157318/122680608-b98c3400-d1f8-11eb-840c-bcd9383efcda.PNG">
#### * Erase
<img width="929" alt="Capture 17" src="https://user-images.githubusercontent.com/86157318/122680624-cdd03100-d1f8-11eb-9bee-a31a9fb25a45.PNG">
then 

#### * choose your region Saudi Arabia 

#### * choose your language English 

#### * put you user name & password 

wait for loading 

#### * Restart 

### now the Ubuntu 16.04 is a new OS ready to work

## 3-install ROS
#### the main target of ROS to link OS with sensors working as node.

first step open Ubuntu 18.04 

then open terminal 

#### CTRL+ALT+T 

then write 

#### *setup your source.list 

`sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'`


<img width="589" alt="Capture" src="https://user-images.githubusercontent.com/86157318/122680939-82b71d80-d1fa-11eb-82c9-1f1bca16e8d7.PNG">


#### *setup your key 

`curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -'`

<img width="586" alt="Capture 1" src="https://user-images.githubusercontent.com/86157318/122681028-053fdd00-d1fb-11eb-83ac-d1aebdea5e47.PNG">

#### * update 

`sudo apt-get update`

<img width="586" alt="Capture 2" src="https://user-images.githubusercontent.com/86157318/122681051-2b657d00-d1fb-11eb-91ea-29fe860f2a1f.PNG">

#### *Full installation 

`sudo apt install ros-melodic-desktop-full`

<img width="589" alt="Capture 3" src="https://user-images.githubusercontent.com/86157318/122681094-5c45b200-d1fb-11eb-8618-975448c45b5c.PNG">

#### *Enviroment setup 

`echo "source /opt/ros/melodic/setup.zsh" >> ~/.zshrc`

`source ~/.zshrc`

<img width="592" alt="Capture 4" src="https://user-images.githubusercontent.com/86157318/122681167-c2cad000-d1fb-11eb-8689-7dd6b22bdd43.PNG">

#### * Dependencies for building packages

`sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential`

<img width="591" alt="Capture 5" src="https://user-images.githubusercontent.com/86157318/122681213-f3ab0500-d1fb-11eb-971d-45cc43653171.PNG">

#### * Initialize rosdep

`sudo apt install python-rosdep`

`sudo rosdep init`

`rosdep update`

<img width="508" alt="Capture 6" src="https://user-images.githubusercontent.com/86157318/122681295-3ec51800-d1fc-11eb-9b95-9f6d28d2826d.PNG">

<img width="579" alt="Capture 7" src="https://user-images.githubusercontent.com/86157318/122681299-44226280-d1fc-11eb-8fcd-5e53b3a9312a.PNG">


### ROS installation finish 






