# WG-Method
🚀 **Fix High Ping in Rainbow Six Siege Using WireGuard + VPNJantit**

If you’re experiencing high ping in Rainbow Six Siege, this project provides a simple solution: route your game traffic through a **WireGuard VPN** using low-latency servers from **VPNJantit**.  
This can help reduce ping caused by poor ISP routing or regional server issues.

---

## 🔧 Requirements
- [WireGuard](https://www.wireguard.com/install/) installed (Windows, macOS, Linux)  
- A free VPN profile from [VPNJantit](https://www.vpnjantit.com/free-vpn)

---

## 📥 Step-by-Step Setup

### 1. Download a Free WireGuard Config
- Visit [VPNJantit Free VPN](https://www.vpnjantit.com/free-vpn)  
- Select a **WireGuard server** close to your game region (e.g., Singapore, Germany, US East)  

You’ll see multiple servers like:  
```
yourcountry1.vpnjantit.com
yourcountry2.vpnjantit.com
yourcountry3.vpnjantit.com
```
Test them to find the best latency.

---

### 2. Test Latency
1. Open **Command Prompt** (`Win + R`, type `cmd`, press Enter).  
2. Run:
   ```sh
   ping yourcountry1.vpnjantit.com
   ```
   Example:
   ```sh
   ping ae3.vpnjantit.com
   ```
3. Look for:
   - **Average ping (ms)** — lower is better (ideally <80ms)  
   - **No packet loss**  

Pick the server with the best results.

---

### 3. Create Account & Download Config
- Create a username and complete the captcha.  
- Download the `.conf` file (ignore the QR code, look for the ZIP with configs).  

---

### 4. Import Config into WireGuard
1. Open **WireGuard**.  
2. Click **Add Tunnel → Import from File**.  
3. Select the `.conf` you downloaded.  

---

### 5. Activate the VPN Tunnel
- Click **Activate** in WireGuard.  
- Confirm your IP has changed and the tunnel is stable.  

---

### 6. Test in Game
- Launch Rainbow Six Siege and **jump into a quick match** to see if your ping improves.  
- You can compare results with and without the VPN to check the difference.  

---

## 🧠 Why This Works
Some ISPs use inefficient or overloaded routes to Ubisoft’s servers (especially in regions like the Middle East, where I currently reside).  
By using a closer or better-routed **WireGuard VPN server**, your traffic reaches Siege servers with **lower latency and less jitter**.

---

## ⚠️ Notes
- VPNJantit is free — servers may get overloaded. Test different ones for best results.  
- **Important:** VPNJantit accounts expire every few days. This means you’ll need to create a new profile and download a fresh config regularly.  
- The method may sometimes be buggy — I apologize for that. I’ll be looking into this issue further and working on finding a more stable, long-term solution.  
- This method **does not bypass bans or region locks** — it only improves routing.
- This can work on any game if you know the **server location**

  ---
## Video Tutorial 
[https://youtu.be/YOUTUBE_VIDEO_ID](https://youtu.be/vwoEBWzVD_w)







