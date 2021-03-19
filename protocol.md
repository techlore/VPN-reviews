# Techlore VPN Review Protocol
**Version 3.1** [View Changelog Here](https://github.com/techlore-official/VPN-reviews/blob/master/review-protocol-changelog.md)

## How Scoring Is Calculated
- Every category is scored out of 5
- For the security, privacy, and speed category, scores are calculated based on the value for each requirement. For example, the kill switch requirement under security is labeled as: “Kill Switch? 0.75/0.5/0: Full System KS/Program KS/No KS” This means if there is a full system-wide kill switch, that’s an extra 0.75 points towards security, program-by-program kill switch will add 0.5 instead, and no kill switch will add 0. All of the requirements added together can get a maximum score of 5 for each category. 

```
Total VPN Score (Out of 5) = (Category 1 Score * Category 1 Percentage) + (Category 2 Score * Category 2 Percentage)...
```

#### Security 25% 
- Previous History? **1.0|0.5|0**  Nothing questionable | Some questions | Not trusted
- OpenVPN and/or WireGuard Support?  **0.7|0**  Yes | No
- Changes IP Address on Devices?  **0.7|0**  Yes | No
- Passes DNS Tests? **0.7|0**  Yes | No
- Kill Switch? **0.35|0.2|0**  Full System KS | Program KS | No KS
- IPV6 Leak Protection? **0.35|0**  Yes | No
- Strongest Data Encryption? **0.25|0**  256bit+ | 128bit-
- Strongest Handshake Encryption? **0.25|0.15|0**  4096bit+ | 2048bit | 1024bit-
- Two-Factor Authentication? **0.2|0**  Yes | No
- VPN Infrastructure Audit **0.2|0**  Yes | No
- VPN Client Audit **0.2|0**  Yes | No
- Misleading Marketing? **0.1|0**  No | Yes

#### Privacy 25%
- Previous History? **1.0|0.5|0**  Nothing questionable | Some questions | Not trusted
- Logging Policy? **1.0|0.75|0**  No logs | Bandwidth/Timestamp Logs | Stores Logs
- First-party DNS Servers? **1.0|0**  Yes | No
- Jurisdiction? **0.5|0.3|0.2|0**  No Eyes | 14 Eyes | 5 Eyes | China
- Site Analytics or tracking concerns? **0.4|0.15|0**  None | Some | Lots
- Warrant Canary?  **0.4|0**  Yes | None
- Simple private payment method? **0.2|0**  Yes | No 
- Is any information required to register? **0.2|0**  No | Yes
- First-party VPN Servers? **0.2|0.1|0**  Yes | Some | None
- Misleading Marketing? **0.1|0**  No | Yes

#### Speed 15% 
- https://speedof.me/ Ping Test x5 (Measured by ping decrease)  
**1|0.75|0.25|0**     0-15ms | 15-30ms | 30-100ms | 100+ms
- https://speedof.me/ Download Test x5 (Measured by percent of non-VPN speed)  
**1|0.75|0.5|0.25|0**     95+% | 90+% | 80+% | 70+% | 0+%
- https://speedof.me/ Upload Test x5 (Measured by percent of non-VPN speed)  
**1|0.75|0.5|0.25|0**     95+% | 90+% | 80+% | 70+% | 0+%
- Android Studio Download (Measured by percent of non-VPN speed)  
**1|0.75|0.5|0.25|0**     95+% | 90+% | 80+% | 70+% | 0+%
- Google Drive File Download (Measured by percent of non-VPN speed)  
**1|0.75|0.5|0.25|0**   95+% | 90+% | 80+% | 70+% | 0+%

Speed results are gathered using our worldwide speed team. A final score is gathered based on an average of percentage decrease for each individual. This will eventually be fully relative scoring. Ex. The fastest VPN we’ve tested will be the only service with a perfect speed score.

#### Settings 5%
- Program customization (Evaluated on most customizable client offered) Compared directly to other VPN services and score is evaluated accordingly.  
**Open to interpretation by user.**  

#### Usage 10%
- Overall experience on Windows
- Overall experience on MacOS
- Overall experience on Linux 
- Overall experience on Android
- Overall experience on iOS
- Speed consistency & Auto-Connect feature
- Stance on torrenting and censorship of traffic  
**Open to interpretation by user.**

#### Stability 20%
- Any crashes? 
- Any bugs? 
- Any performance issues?  
**May vary by user.**

#### Additionally Address
- Total simultaneous devices?
- Split-Tunneling?
- Multihop?
- Server & country selection?
- Lowest price?
- Free trial and/or money-back policy?
- Helps Privacy Causes?
- Who the VPN is geared towards? Label 'Beginner', 'Intermediate', or 'Advanced'
