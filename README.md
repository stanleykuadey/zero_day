<h1> <strong> Using VirtualBox and Vagrant </strong> </h1>

<h3> This project is to explore the use of virtual environments on our local machine. </h3>

<strong> Installation Instructions below: </strong>

<h3> For Windows Users </h3>
1. Download VirtualBox from https://intranet.alxswe.com/rltoken/gnDuZRjo-TxXIvnH4aAG5g

2. Install VirtualBox

3. Download Vagrant from https://intranet.alxswe.com/rltoken/rTqEUgxwGx2C-11h6lLcQA

4. Install Vagrant

5. Open the command prompt

6. Add the Ubuntu 20.04 (Focal) image to your box list:
	<ul>
	<li> C:\Users\julien> vagrant box add ubuntu/focal64 <strong> Warning: this step can take time </strong> </li>
	<li> Many other images are available here: https://intranet.alxswe.com/rltoken/i2j9GY2ou1zBvZ9wUeavRw </li>
	</ul>

<h3> Create your first virtual machine: </h3>
<ul> 
</li> C:\Users\julien> vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" -you don’t have to execute this command line everyday, only once, to create a new virtual machine </li>
</ul>
<ul>
<li> C:\Users\julien> vagrant plugin install vagrant-vbguest -> to avoid issue with the last version of Vagrant (2.2.4 or latest) </li> 
<li> C:\Users\julien> vagrant up -> it will start your virtual machine </li>
</ul>
<ul>
<li> C:\Users\julien> vagrant ssh -> now you are inside your virtual machine.</li>
</ul>


<h3> For Ubuntu Users: </h3>
1. Open the Terminal application:
<ul> <li>Now you will execute command line in your Terminal (each of them start with $) </li> </ul>
2. Install VirtualBox: $ sudo apt-get install virtualbox
3. Install Vagrant: $ sudo apt-get install vagrant
4. Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time
<ul> <li>Many other images are available https://intranet.alxswe.com/rltoken/i2j9GY2ou1zBvZ9wUeavRw </li> </ul>

5. Create your first virtual machine:
<ul>
<li> $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine </li>
<li> $ vagrant up -> it will start your virtual machine </li>
<li> $ vagrant ssh -> now you are inside your virtual machine. </li>
</ul>


<h3> For Mac OSx Users: </h3>
1. Download VirtualBox from https://intranet.alxswe.com/rltoken/gnDuZRjo-TxXIvnH4aAG5g
2. Install VirtualBox
3. Download Vagrant from https://intranet.alxswe.com/rltoken/rTqEUgxwGx2C-11h6lLcQA
4. Install Vagrant
5. Open the Terminal application:
<ul>
<li> Now you will execute command line in your Terminal (each of them start with $) </li>
<li> Add the Ubuntu 20.04 (Focal) image to your box list: $ vagrant box add ubuntu/focal64 Warning: this step can take time </li>
<li> Many other images are available here </li>
</ul>

6. Create your first virtual machine:
<ul>
<li> $ vagrant init ubuntu/focal64 -> it will generate a Vagrantfile with base = "ubuntu/focal64" - you don’t have to execute this command line everyday, only once, to create a new virtual machine </li>

<li> $ vagrant up -> it will start your virtual machine </li>

<li> $ vagrant ssh -> now you are inside your virtual machine. </li>
</ul>





