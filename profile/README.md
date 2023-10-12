# Well, hello! 👨🏽‍💻
Invise Labs is a division of [Invise Solutions](https://invisesolutions.com/). **We're a team of IT professionals who fly by night as computer programmers – well, not anymore, but we were**, things are a bit more serious now in comparison to back in the day, when we started in November 2016.

**We primarily create software for IT Pros and Cyber Security Pros**, we're paving the way for exciting new technological software inventions inspired by our every day IT business, our malware hunting, and in addition to the end possiblities we think of every day.

Through our day-to-day business we come up with all sorts of ideas for coding and automating things, if something works it's way into being a project, you'll find it here at Invise Labs. If it's not project worthy, you'll likely find it (scripts or other small trinkets) over at our [Invise Solutions Github page](https://github.com/invisesolutions/).

# Donations
We are asking our supporters, people who believe in us, and those who want to see our projects succeed, to please consider making a donation to support development. We don't mind giving lifetime subscriptions in exchange - for projects that we eventually will be charging for. It costs money to run developement, pay for servers such as Google Cloud instances, and pay ourselves if we will be spending enough personal time. A dedicated project donations page will be created soon, in the meantime, you can use our [pay page at Invise Solutions](https://invisesolutions.com/pay).

# Featured Projects 💽
### 1️⃣ Quick Dagger
Built for IT Pros to detect problems with computer systems. **Featuring Nexgen**, break-through malware detection algorithm and machine learning to detect malicious files on a Windows Operating System.

### 2️⃣ Prober Scripts
Collection of RMM dashboard command-line scripts that collect and report important information such as hardware temperatures, SMART data, etc. for you to see on your list of computers you manage. These scripts are ready to upload onto your RMM dashboard and by default deloy into the C:\IT folder of machines you manage, and report back stats to your RMM dashboard software.

[TempProber](https://github.com/mikelierman/temprober): Uses OpenHardwareMonitor API to collectt HW temps.

[SMARTProber](https://github.com/mikelierman/smartprober): HDD/SSD SMART data (pwr on hrs, current pending sectors, etc) - I'm still surprised to this day that RMM dashboard implementations of SMART data does not detect this information - neither day windows.

[DeviceProber](https://github.com/mikelierman/smartprober): Scans Device Manager information and reports any devices or drivers with a Warning, Failure, or Missing status attached to them.

[NICProber](https://github.com/inviselabs/nicprober): Reports ethernet adapter connection speed status as 1gbps or 100mbps, which can assist you in troubleshooting network performance issues or be on the watch for clients using old cables or obsolete hardware.

[ConnectivityProber](https://github.com/inviselabs/connectivityprober): (Name might change.) Every time your scripts fire, this does a ping to Google for 50 packets and measures the latency and connectivity issues. Reports average ms, latency issues, jitter, and dropped packets. Fantastic tool to give you information about whether a client's ISP has issues or not. We found a few of ours at Invise Solutions, when we deployed this script to a couple hundred machines. 

[FanProber](https://github.com/inviselabs/fanprober) **(COMING SOON)** Pulls fan speed information and attempts to detect abnormalities as such intermittent stopping. Collects and reports fan speeds and correct operation of fans. You would think that the motherboard and BIOS would monitor this informaiton correctly, but over at Invise Solutions, we had a biz client that was reporting occational PC crashing. After being physically there onsite during another occurence, we disocvered that the CPU fan was randomly stopping, and the CPU was heating up. 

### 3️⃣ Hashet
**COMING SOON**

### 4️⃣ Hunter Script
**COMING SOON**

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
