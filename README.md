# cve2020-8835
 
2020-06-24 17:49:25.288 18306-18306/com.kashamalaga.CVE20208835 A/libc: Fatal signal 31 (SIGSYS), code 1 (SYS_SECCOMP) in tid 18306 (aga.CVE20208835), pid 18306 (aga.CVE20208835)
2020-06-24 17:49:25.376 18333-18333/? I/crash_dump32: obtaining output fd from tombstoned, type: kDebuggerdTombstone

2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: Build fingerprint: 'Xiaomi/baiji_sw/baiji:9/PXD7.200315.001.XM082/PXD7.200315.001.XM082:user/release-keys'
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: Revision: '0'
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: ABI: 'arm'
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: pid: 18306, tid: 18306, name: aga.CVE20208835  >>> com.kashamalaga.CVE20208835 <<<
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: signal 31 (SIGSYS), code 1 (SYS_SECCOMP), fault addr --------
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG: Cause: seccomp prevented call to disallowed arm system call 386
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG:     r0  00000000  r1  be86db80  r2  00000070  r3  91c4f240
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG:     r4  a24133e0  r5  ac0b2d8c  r6  be86db80  r7  00000182
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG:     r8  00000000  r9  ac636000  r10 be86de10  r11 ac636000
2020-06-24 17:49:25.429 18333-18333/? A/DEBUG:     ip  be86db60  sp  be86db50  lr  918cfb1d  pc  ac024d58