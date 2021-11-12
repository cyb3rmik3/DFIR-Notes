# Memory Dump Procedures

- https://docs.microsoft.com/en-us/sysinternals/downloads/livekd

# Volatility cheat sheet

| Command | Description |
| --- | --- |
| python vol.py -f filename.filetype imageinfo | imageinfo will help you to get more information about the memory dump |
| python vol.py -f filename.filetype --profile=WinXPSP3x86 | specify to volatility the OS profile (--profile=WinXPSP2x86) |
| python vol.py -f filename.filetype --profile=WinXPSP3x86 pslist | what were the running processes using the pslist plugin |

# Memory Forensics References

- https://newtonpaul.com/malware-analysis-memory-forensics-with-volatility-3/
- https://www.secjuice.com/malware-analysis-memory-forensics/
- https://eforensicsmag.com/finding-advanced-malware-using-volatility/
- https://resources.infosecinstitute.com/topic/ransomware-analysis-with-volatility/
- https://book.hacktricks.xyz/forensics/basic-forensic-methodology/memory-dump-analysis/volatility-examples
- https://www.aldeid.com/wiki/Volatility/Retrieve-hostname
- https://stackify.com/how-to-monitor-a-windows-process/
- https://adamtheautomator.com/powershell-get-process/
- https://programtalk.com/python-examples/volatility.debug.warning/
- https://danielsauder.com/2016/02/06/memdumps-volatility-mimikatz-vms-part-2-windows-7-full-memory-dump-get-hashes/
- https://fossies.org/linux/volatility/volatility/plugins/overlays/windows/win10.py
- https://www.andreafortuna.org/2017/08/21/volatility-my-own-cheatsheet-part-8-filesystem/
- https://steemit.com/security/@nybble/forensic-extracting-files-from-mft-table-with-volatility-part-2-en
- https://www.andreafortuna.org/2017/08/21/volatility-my-own-cheatsheet-part-8-filesystem/

# Volatility GitHub

- https://github.com/volatilityfoundation/volatility
