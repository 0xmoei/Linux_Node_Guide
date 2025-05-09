# 1- Where to buy VPS

The first thing that is needed to participate in Node Testnets is a VPS server

In order to buy a VPS ( Cloud Server), I introduce several good (in my opinion) foreign & Iranian providers with and without crypto payment with brief information

| Rank | Provider |   Payment Method   | Discription                     |
| :-------- | :-------- | :------- | :-------------------------------- |
| 1      | Hetznr      | `Credit card - need KYC` | `Best Hosting , not very cheap`  [auction servers](https://www.hetzner.com/sb/) (min. $30) are good |
| 2      | Contabo      | `Credit card - need KYC` | `Cheap but for a very few nodes we had bandwidth issues` |
| 3      | [Hostbrr](https://my.hostbrr.com/order/forms/a/NTMxNw==)      | `Crypto` | `Cheap to Normal pricing, good performance` |
| 4     | [PQhosting](https://pq.hosting/?from=687947)     | `Crypto, You might need KYC` | `Good performance and some cheap servers` |
| 5     | [Aeza](https://aeza.net/?ref=392339)     | `Crypto` | `Good for hourly servers, or you might findaa good server simetimes` |




### I'm not RESPONSIBLE nor AFFILATED with any of these providers. I just used them before, and I think they are good choice. You can choose wherever you think is better

#

# 2- What system to buy
Before buying a VPS, we must consider several components to choose the required system

* `CPU`: Usually, 4core to 16core
* `Ram`: Usually, 4GB to 32GB
* `HDD`, `SSD`: Projects always consider the hard disk of the Nodes to be higher than required. In few nodes such as `Prover` or `Validator in Active-set` maybe a lot of hard disk is needed. Minimum is better to be `60` 
* `Operating-system` must be `Ubuntu`, `Ubuntu 22` is usually compatible with every project
* VPS must be ipv4 and must NOT be NAT

#

# 3- Let's Buy a VPS
To understand better, let's buy a server from 2 Iranian and foreign providers

This is not an advice to buy from them and I just want to show you the process

### After this guide, I'm not sure if they will get out of stock of their servers, you can consider creating a ticket to ask before proceeding to buy

## Hostbrr
Let's list some of their servers orders:

> High RAM: [Memory-Optimized VPS](https://my.hostbrr.com/order/main/packages/largeram/?group_id=23&a=NTMxNw==)
> 
> High RAM - Better net bandwidth: [RAM-Optimized - Premium](https://my.hostbrr.com/order/main/packages/largeram/?group_id=38&a=NTMxNw==)
> 
> Good CPU: [AMD Ryzen 9 7950XD](https://my.hostbrr.com/order/main/packages/vps7950/?group_id=14&a=NTMxNw==)
> 
> Good CPU - Cheaper: [AMD Ryzen 9 5950X](https://my.hostbrr.com/order/main/packages/vpsgermany/?group_id=13&a=NTMxNw==)
> 
> High SSD - Out of stock right now: [Big Storage Servers]([https://my.hostbrr.com/order/main/index/storage](https://my.hostbrr.com/order/main/index/storage?a=NTMxNw==) 

### 1- I pick $14.99 VPS from [AMD Ryzen 9 5950X](https://my.hostbrr.com/order/main/packages/vpsgermany/?group_id=13&a=NTMxNw==)

* 4 vCore ,8GB RAM, 150 GB Storage can be a good choice for me

![Screenshot_1](https://github.com/user-attachments/assets/3e1cf6a4-583a-41c6-a300-5d3e1b6d0dc2)

### 2- I register my Contact Information and pay with my metamask wallet through Coinbase Commence payment method

### 3- Install Ubuntu.22
* After payment, I wait until my server to get `active` in `services` page
* We must install ubuntu manually in Hostbrr when server is activated

![Screenshot_2](https://github.com/user-attachments/assets/fd9b2384-dba7-4b7b-a4a2-6d457b66ff12)

![Screenshot_106](https://github.com/user-attachments/assets/a55459d4-9520-494a-9f2a-ae76f8c6cc0d)


### VPS details
They will Email your `IP` & `password` after server installed Ubuntu

#

# 4- How to connect to VPS
### 1- You need a client to connect to your VPS through SSH
> List of Clients:
>
> 1- My prefer: Mobaxterm (has SFTP: you can manage your files & directories
>
> 2- Termius (has SFTP)
>
> 3- Putty (No SFTP, Just a terminal)

### 2- VPS Details
You need following details to connect to your VPS through SSH
* `IP`: Provider will email you after activation
* `Port`: Default open port for SSH connection is always `22`
* `User`: Default user is always `root`
* `Password`: Provider will email you after activation

### 3- Connect via Mobaxterm
> 1- Click `session` and open `SSH` tab
>
> 2- In `Remote host` you must fill your server IP, if you write `root@` behind it, it uses `root` as user
>
> 3- Default SSH port is 22
>
> 4- After clicking `OK`, a Terminal opens which needs your `password`, Copy it & Paste it in the reminal by clicking `Mouse Middle Scroll Wheel`, Password will be hidden in terminal
> 
![Screenshot_5](https://github.com/user-attachments/assets/5c63934d-df07-4287-b87a-b98c6eb31156)

### 4- Now you have a Terminal that you can write your commands in it
SFTP: You can see your home: `/root/` directory & its files and folders in left side of the Mobaxterm client

![Screenshot_6](https://github.com/user-attachments/assets/1e42f11e-c621-446a-9400-2ecab6e92546)



