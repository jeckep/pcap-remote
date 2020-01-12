PCAP Remote is a non-root network sniffer app that allows you to debug and analyze
Android traffic on your desktop PC using the app's built-in SSH server, which is useful and often a must when developing mobile applications that use complex/custom network protocols. The traffic is captured using an Android OS feature called VpnService.

<p align="center">
<img src="https://raw.githubusercontent.com/egorovandreyrm/pcap-remote/master/github_assets/device-2020-01-12-123805.png" width="200" />
</p>

The app is primarily designed to be used in conjunction with Wireshark, which is the most famous tool for network troubleshooting, analysis, software and communications protocol development, and education.

Although Wireshark is the tool that is recommended, other similar tools can also be used as captured packets are saved in the commonly used pcapng format.

Features:
- Remote capturing using the built-in SSH server;
- Supporting Wireshark sshdump tool (https://www.wireshark.org/docs/man-pages/sshdump.html);
- Capturing traffic as .pcap file;
- MITM (Man-in-the-middle) functionality, which allows you to decrypt traffic in Wireshark;
- No root required.

Limitations:
- TLS 1.3 is not supported when using the MITM functionality;
- The SSH server only supports IP v4 clients;
- Hotspot/Tethering traffic can't be captured.

Info/How-to: https://egorovandreyrm.com/pcap-remote-tutorial/
