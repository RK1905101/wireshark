![image](https://user-images.githubusercontent.com/64470404/138563177-3f622fee-df04-4efa-8da1-e85243ae93f7.png)

# WIRESHARK 

Wireshark is an open-source packet analyzer or in simple words, packer sniffer or sniffer
as it is used to track the packets.<br>
And as it is open source packet sniffer and so it is free application, which is also available for windows, mac or in linux distribution.<br>
It is also known as sniffer, network protocol analyzer, and network analyzer.<br>

## ADVANTAGES:

- It sniffs packet to the micro level and captures live packets and analyzes it offline.<br>
- Inspects number of packets in the deep level and hence have the most powerful display filters in the industry.<br>
- Has the power to inspect and analyse VoIP.<br>
- It can also capture raw USB traffic.

Since it is a multiplatform software, and so here's the example from RHEL 8.0 (Red Hat Enterprise Linux 8.0) starting from it's installation.<br>

### Installation of Wireshark in RHEL

- First of all, we'll access the root linux system, or in simple words, gain the admin previledges by logging in as Root user.
- To install package in RHEL, we either use 'yum' or 'dnf' command.
- For GUI application, we'll be using :
 ``dnf install wireshark``
 
- And for CLI application, we'll be using command:
``dnf install wireshark-cli``

<img src="https://user-images.githubusercontent.com/64470404/138584940-63746af2-ad78-4033-ae53-b8a924986cc0.png" height="50%" width="70%">

<br>

### Launching Wireshark

We'll launch wireshark:<br>
We can check either from GUI that our application is installed or not or else we can just verify it with the help of cmd: <br> ``tshark --version``

We'll get the output of the cmd as follows:<br><br>
<img src="https://user-images.githubusercontent.com/64470404/138585113-84024ca5-2122-4ca4-bd76-6a60c72c0926.png" height="50%" width="70%">

And for GUI, we get as like this:<br><br>
<img src="https://user-images.githubusercontent.com/64470404/138585174-cee4019e-77fb-4ab8-9d58-6ccac1d25f64.png" height="40%" width="45%">

Here, in the GUI app, we can see, the different types of network interface card which contains different types of IP available there.<br>
We can also see, some kind of activities are going on beside the name of network interface, like zigzag motion, which updates regularly.<br>
And since, it is being running inside the virtual machine and so it shows the all the network which are available there.

<img src="https://user-images.githubusercontent.com/64470404/138585401-35346332-5659-42d8-bd03-25b8decffe5a.png" height="100%" width="100%">

<br>
When we open any of the ntw interface, we see that, live network packets are being captured by this application.<br>

![image](https://user-images.githubusercontent.com/64470404/138586406-3673bf4f-0099-4af8-9660-1faf330b76d5.png)


