![Visitors](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fgithub.com%2Fadtitas%2Fngrok-rdp%2F&labelColor=%2314213d&countColor=%23e5e5e5&style=flat-square) ![GitHub forks](https://img.shields.io/github/forks/adtitas/ngrok-rdp?style=social)

## 📮 Description

**What is RDP?**<br>

- RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.

**How long does this RDP stay active?**<br>

- This RDP stays active for up to 2 hour (previously 5-6 hours).<br>
- Currently, I'm working on it to make again 5-6 hours.

## 📮 Setup Tutorial

#### First Step

1. Press the `fork` button
2. Login or signup to ngrok: https://ngrok.com
3. Now go to `Getting Started > Your Authtoken` & copy your token

#### Second Step

1. In your forked repo, go to `Settings > Secrets > Action > New Repository Secret`
2. In the name section, enter this text: **NGROK_AUTH_TOKEN**
3. In the value section, put the **ngrok token**
4. Then press **Add Secret**
5. Now go to `Action > AWS`
   <details> <summary>Screenshot</summary> <img src="https://i.ibb.co/QmKHbnp/Screenshot-191-proc.png" alt="ss" width="80%"/> </details>
6. Click **Run Workflow** from AWS dashboard.
   <details> <summary>Screenshot</summary> <img src="https://i.ibb.co/MfL8Ghg/Screenshot-192.png" alt="ss" width="80%"/> </details>
7. Refresh the page and go to `AWS > build` option
   <details> <summary>Screenshot</summary> <img src="https://i.ibb.co/p29Z7wZ/Screenshot-193-proc.png" alt="ss" width="80%"/> </details>
8. You'll get IP, Username & Password from **Connect to RDP** section
   <details> <summary>Screenshot</summary> <img src="https://i.ibb.co/Bf4r5F9/Screenshot-194-proc.png" alt="ss" width="80%"/> </details>

#### Third Step

1. Search **Remote Desktop Connection** from Windows Start Menu and open
2. Put IP without `tcp://` 🔴
3. Later on, put the **username & password** for credential/auth
   <details> <summary>Screenshot</summary> <img src="https://i.imgur.com/WQr9N1A.png" alt="ss" width="80%"/> </details>

## 📮 Screenshots

<img src="https://i.ibb.co/s3Ns3bF/Screenshot-2.png" alt="ss" width="100%"/>

<details> 
   <summary>Desktop & Speedtest Result</summary> 
      <img src="https://i.ibb.co/DM1SGQW/Screenshot-1.png" alt="ss" width="100%"/>
      <img src="https://www.speedtest.net/result/14108384759.png" alt="ss" width="100%"/>
</details>

## 📮 Terms & conditions

1. Don't share this script without credit!
2. Don't misuse this script!

## 📮 License

The content of this project itself is licensed under the [Creative Commons Attribution 3.0 Unported License](https://creativecommons.org/licenses/by/3.0/), and the underlying source code used to format and display that content is licensed under the [MIT License](LICENSE.md).
