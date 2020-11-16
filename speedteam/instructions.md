# Techlore SpeedTeam V3 Instructions

1. Install [VirtualBox + Guest Additions.](https://www.virtualbox.org/) (Make sure virtualization is supported & enabled in your BIOS)
2. Download the SpeedTeam Virtual Machine (VM) linked in the email sent to you.
3. Save the VM in a safe place on your system, configure the VM for your
specific computer [(RAM, CPU, GPU)](https://www.howtogeek.com/124796/the-htg-guide-to-speeding-up-your-virtual-machines/) Max it out without hitting red to prevent VPN bottlenecking.
4. **Important!** [Make sure you are using **Bridged** as your network adapter.](https://geek-university.com/oracle-virtualbox/configure-bridged-networks/)
5. Boot the SpeedTeam VM, login, and go through the [checks.](https://github.com/techlore-official/VPN-reviews/blob/master/speedteam/checks.md) If everything is working as intended, shutdown the VM. If any issues arise or a check is not met, do not ignore them and respond to the email with your issue(s).
6. It's time to schedule a day for VPN testing. Follow the link in the email sent to you to reserve a day. Reserving a day confirms your VM has no issues! **DO NOT** signup unless all checks were passed in Step 5.
7. On the day of your testing, you will receive a new email with any necessary OpenVPN profiles, usernames, or passwords. You have the entire 24 hours to test the VPN.
8. Configure the VPN in the network manager, and make sure it’s properly working by doing a quick before/after IP check in Firefox. [Thorough instructions here](https://www.ch.cam.ac.uk/computing/openvpn-linux-network-manager)
9. Perform your speed testing using the Firefox Bookmarks, a stopwatch (one is installed at the top of the VM), and input results into the spreadsheet on the desktop. **Perform a final [check](https://github.com/techlore-official/VPN-reviews/blob/master/speedteam/checks.md) before testing.** It's recommended to duplicate or *Save As* the template so you have a blank spreadsheet for future VPN tests. Always save and use the XLS format.
10. Once testing is completed, save and upload a copy of your final spreadsheet using the Firefox bookmark labeled *Upload Final Sheet.* It may ask for an email, you'll find another bookmark titled *Dropbox Email* which will give you a temporary email to use.
11. Disconnect from the VPN! Delete the VPN configuration files. And remove the VPN from the network manager. The only difference in the VM after speed testing should be your completed spreadsheet.

There are more thorough instructions given for SpeedTeam V2 [here.](https://techlore.tech/speedteam.pdf) These are out of date! But many of the screenshots and instructions can be applied to V3 as well if you want to be walked through it more throroughly. Always re-check these V3 instructions as these are the most up-to-date instructions.
