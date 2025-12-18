# Internet Blocklists

I’ve aggregated a wide range of DNS blocklist feeds from across the web and organised them into clearly defined categories, allowing specific types of content to be selectively filtered on a per-VLAN basis.

In addition, I developed a custom parser for Apple’s iOS DNS logs, enabling me to create precise domain lists and create targeted filters for reducing distracting content within social media apps. While effectiveness is inherently limited by DNS-level visibility without MiTM inspection, these filters provide a practical balance between control and privacy.

All filtering and policy enforcement is implemented on my OPNsense firewall.
