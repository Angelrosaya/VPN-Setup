<h1>VPN Setup and Usage (Proton VPN)</h1>

<h2>Description</h2>
In this lab we will see how a VPN masks your ip address giving you safer tunneling capabilites from suspicous actors. Although this isn't a fullproof way to keep your information from them it makes it more difficult for someone if they were to try. 
<br />


<h2>Environments and Technologies Used</h2>

- <b>Virtual Machines in Azure</b> 
- <b>Proton VPN</b>
- <b>Remote Desktop</b>
<h2>Operating Systems Used</h2>

- <b>Windows 10 Enterprise Gen 2 (22H2) </b> 

<h2>Create a Vitual Machine:</h2>

<p align="center">
Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file: <br/>
 <img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/35508640-e78e-4298-8ebe-a2bcf6695b5f" />
<br />
<br />
Create a resource group named vpn-test, create a windows 10 virtual machine named vpn-test-win 10, any region of your choice, use a windows 10 image of your choice, for your size use anything with 4vcpu's for best performance, Username: labuser Password: Password123! Make sure to select the box stating you "Confirm you have an eligible windows 10/11 license with multi-tenant hosting rights" like on the last picture posted, finally click review and create once validation passes click create and wait until your VM is created:  <br/>
<img width="90%" height="90%" alt="On Microsoft azure click virtual machine" src="https://github.com/user-attachments/assets/cb864c00-427b-4fe6-ba37-151eb5c768d0" />
 <br/>
 <br/>
 <img width="90%" height="90%" alt="image" src="https://github.com/user-attachments/assets/79b557d6-c45f-42e2-bcf8-ab094f521908" />
 <br/>
 <br/>
<img width="90%" height="90%" alt="image" src="https://github.com/user-attachments/assets/5818d410-109d-4328-a56d-d7223f06ef4e" />
 <br/>
 <br/>
<img width="90%" height="90%" alt="image" src="https://github.com/user-attachments/assets/12c7fe4f-19e2-4ab5-a547-2f9eaf01944a" />
 <br/>
 <br/>
 <img width="90%" zoom= "100%" height="90%" alt="image" src="https://github.com/user-attachments/assets/85011945-487c-4a96-95c6-4291ee39b6d2" />
 <br/>
 <br/>
 <img width="90%" height="90%" alt="image" src="https://github.com/user-attachments/assets/d56142a3-6feb-4bac-9adc-70314af4794d" />
<br />
<br />
Copy your VM's public ip address, log into the VM with Remote Desktop. On your VM browse to https://whatismyipaddress.com/ and take note of this in a text file:  <br/>
<img width="1918" height="909" alt="image" src="https://github.com/user-attachments/assets/60eea5cf-507f-4852-9c0d-83159eefa232" />
<br/>
 <br/>
<img width="70%" height="70%" alt="image" src="https://github.com/user-attachments/assets/18c2f518-90f5-44cf-a13a-bf1cca223947" />
 <br/>
 <br/>
<img width="70%" height="70%" alt="image" src="https://github.com/user-attachments/assets/b1faacfc-7650-4098-855f-86a79accdb5a" />
 <br/>
 <br/>
<img width="449" height="512" alt="image" src="https://github.com/user-attachments/assets/df5b52e5-1c20-49f7-87f3-98771f9edfd4" />
<br />
<br />
 <img width="1916" height="1072" alt="image" src="https://github.com/user-attachments/assets/ab040c81-05f3-4771-a7c7-6a4736bb004f" />

On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en:  <br/>
<img width="951" height="931" alt="image" src="https://github.com/user-attachments/assets/f3644834-93bc-4071-bb60-4a8d55e19ab3" />
<br />
<br />
Back within your VM, download the Proton VPN client:<br/>
<img width="1900" height="994" alt="image" src="https://github.com/user-attachments/assets/16baedc4-0465-4b12-962b-ffc59efe0f16" />
<img width="1913" height="1003" alt="image" src="https://github.com/user-attachments/assets/cd0d426f-1b30-4fdb-821f-852ffb96a32e" />
<img width="1902" height="998" alt="image" src="https://github.com/user-attachments/assets/1417d3b5-889d-48cd-840e-b833131627e8" />


<br />
<br />
Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country. Browse to https://whatismyipaddress.com/  and take note of this in a text file. Notice on my end my VM public ip address was 20.55.252.13 and now that I connected to the VPN it changed to 212.8.243.62:  <br/>
<img width="997" height="650" alt="image" src="https://github.com/user-attachments/assets/094f4f25-5dd6-49bd-a050-1f3e78c90264" />
<img width="1915" height="1046" alt="image" src="https://github.com/user-attachments/assets/fdf102cb-147b-4fd5-ac99-6e33a78c5dcd" />
<img width="1916" height="1043" alt="image" src="https://github.com/user-attachments/assets/9b4f47d1-f019-4d21-9b66-768c3c646161" />
<img width="1918" height="1006" alt="image" src="https://github.com/user-attachments/assets/e8a48f0f-d82f-4da5-b495-2602b0baf093" />

<br />
<br />
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different and in my case my VPN connected to a server in the Netherlands and the language changed as such as if I was in the Netherlands:<br/>
<img width="1914" height="1003" alt="image" src="https://github.com/user-attachments/assets/244875ca-bec5-44b2-b5a1-9b4d8532aaaa" />


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
