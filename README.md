<br/>
<p align="center">
  <h1 align="center">M346 ref03 ansible</h1>
  <p align="center">
    School project for the module 346.
    <br/>
    <br/>
  </p>
</p>


## Getting Started

To setup this project follow the instructions of the prerequisites and installations

### Prerequisites

For this project you only need ansible and ssh working on your local machine. 
For the target devices you need two working, with ssh accessible machines.

* ansible

```sh
sudo apt-get install ansible
```

### Installation
1. Change the IP addresses in [hosts](./hosts) to your desired locations.

2. Run ```ansible-playbook -i hosts build.yml``` on your local machine.

3. After the playbook run successfully you should be able to see the working spring boot application on port ```8080``` of your ref03 machine.

## Authors

<a href="https://github.com/llynbaum" style="display:flex; align-items:center; gap: 5px;">
<img src="https://avatars.githubusercontent.com/u/124689003?v=4" style="width: 30px; border-radius:50%;"></img>
Llyn Baumann
</a>
<br>
<a href="https://github.com/ninohelfenstein" style="display:flex; align-items:center; gap: 5px;">
<img src="https://avatars.githubusercontent.com/u/116466829?v=4" style="width: 30px; border-radius:50%;"></img>
Nino Helfenstein
</a>  