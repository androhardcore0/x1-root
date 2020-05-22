# CVE-2020-0041

This repository contains LPE code for exploiting CVE-2020-0041 implemented by bluefrostsecurity as released at https://github.com/bluefrostsecurity/CVE-2020-0041/tree/master/lpe .
The exploitation approach for this part can be found at https://labs.bluefrostsecurity.de/blog/2020/04/08/cve-2020-0041-part-2-escalating-to-root/ .

This forked repository shall host ports for other kernels / devices in their specific branches.
Big thanks to bluefrostsecurity for their awesome writeup and the exploit release.

# CVE-2020-0041 LPE port for Sony xperia TAMA platform phones

This fork supports sony xperia xz2/xz2c/xz2p/xz3 android 10 phones running kernel 4.9.

# Scripts to startup magisk from temp root

Implemented special hack to allow magisk startup from the exploit, including working su permission asking notification in android.
You can find it in the 'scripts' subdirectory.
