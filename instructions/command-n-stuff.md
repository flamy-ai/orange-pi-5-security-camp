[thermal pad]: /more/terminology.md#thermal-pad "Soft pad that conducts heat away from computer chips."
[soc]: /more/terminology.md#soc-system-on-chip "System-on-Chip: includes multiple processors with different functions in a single chip."
[cpu]: /more/terminology.md#cpu-central-processing-unit "Central Processing Unit: main computing chip, the brains."
[ram]: /more/terminology.md#ram-random-access-memory "Random-Access Memory: stores data the computer is currently working on."
[gpu]: /more/terminology.md#gpu-graphics-processing-unit "Graphics Processing Unit: processes visual tasks, like games."
[npu]: /more/terminology.md#npu-neural-processing-unit "Neural Processing Unit: processes neural networks (AI)"

<h1 align=center>This has commands I ran, will add to instructions later</h1>

<br>

<h2 align=center>Commands</h2>


Note: For IPs on Cams and virtual adapter on Orange Pi 5 i'm using 172.21.4.1/22 so subnet mask 255.255.252.0 and I set Orange Pi 5 to 172.21.4.1 and Gateway to 172.21.4.2 and first camera to 172.21.4.3


1. Hello
```
Best Code Block
```
2. Thing
```
E
```
3. E
4. Set local timezone
```
sudo timedatectl set-timezone America/New_York
```
5. Download `docker-compose.yml` for Frigate
```
sudo wget -P /opt/docker/frigate/ https://raw.githubusercontent.com/flamy-ai/orange-pi-5-security-cam
p/master/src/docker-compose.yml
```
6. Add IP to Orange Pi which allows it to access camera subnet.
```
sudo ip addr add dev eth0 172.21.4.1/22
```
7. 

<br><br><br>

<table align=center>
    <tr>
        <td>

[Go Back](/README.md)
        </td>
        <td>
[Table of Contents](/README.md)
        </td>
        <td>
[Continue](/README.md)
        </td>
    </tr>
</table>
