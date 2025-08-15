# 🛜 Monitoring vs Segmentation: What I Learned the Funny Way

So here's the situation:  
I’m diving deep into securing nanny cams—setting up VLANs, scanning IPs with Nmap, planning mitigations—and I realized... I didn’t actually understand how my own monitoring setup *functioned* until I brought it up to my professor.

We laughed, because here I was talking about hacking my nanny cams, and I hadn't fully grasped **the relationship between monitoring apps, local networks, and cloud subscriptions**. And honestly? I think a lot of users are in the same boat.

## 🌐 The Reality I Uncovered

- When I switched my cams to the **guest network** (yay, segmentation!), I lost access to them via my phone.
- Why? Because my phone was still on the **main network**, and the monitoring app **requires LAN access** unless you pay for cloud functionality.
- The devices were still recording, but I couldn’t check the feed unless I **manually switched networks** or **subscribed to the cloud service**.

## 🔐 Security Implications

- I *thought* separating networks would harden security (it did), but I didn’t realize I was also cutting off **my own visibility**.
- It reminded me that security isn’t just about isolation—it’s about **how the pieces communicate**.

## 💡 Solution I'm Exploring

- I’m considering setting up a **dedicated device** (an old phone/tablet) that stays connected to the guest network for monitoring purposes.
- This keeps my main devices secure and still gives me quick access to the cams without subscribing to cloud storage I don’t want or need.

## 🔄 Takeaway

> “It’s not just about knowing terms like ‘link-local’ from CompTIA A+—it’s about seeing how they apply when your baby’s crying and you can’t load the cam feed.”

This moment deepened my understanding of **network segmentation**, **IoT behavior**, and the **real-world trade-offs between privacy and convenience**.
