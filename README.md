# acmetest
Unit test project for **acme.sh** project https://github.com/Neilpang/acme.sh



# Here are the latest status:

| Platform | Status| Last Run Time| Comments|
-----------|-------|--------------|---------|
|freebsd| ![](https://neilpang.github.io/acmetest/status/freebsd.svg?1561079108)| Fri, 21 Jun 2019 01:05:08 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/freebsd.out) |
|openbsd| ![](https://neilpang.github.io/acmetest/status/openbsd.svg?1561079659)| Fri, 21 Jun 2019 01:14:19 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/openbsd.out) |
|pfsense| ![](https://neilpang.github.io/acmetest/status/pfsense.svg?1561080101)| Fri, 21 Jun 2019 01:21:41 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/pfsense.out) |
|solaris| ![](https://neilpang.github.io/acmetest/status/solaris.svg?1561080592)| Fri, 21 Jun 2019 01:29:52 GMT| [Failed](https://github.com/Neilpang/acmetest/blob/master/logs/solaris.out) |
|windows-cygwin| ![](https://neilpang.github.io/acmetest/status/windows-cygwin.svg?1561081889)| Fri, 21 Jun 2019 01:51:29 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/windows-cygwin.out) |
|ubuntu:latest| ![](https://neilpang.github.io/acmetest/status/ubuntu-latest.svg?1561082333)| Fri, 21 Jun 2019 01:58:53 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/ubuntu-latest.out) |
|ubuntu:16.04| ![](https://neilpang.github.io/acmetest/status/ubuntu-16.04.svg?1561082755)| Fri, 21 Jun 2019 02:05:55 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/ubuntu-16.04.out) |
|ubuntu:14.04| ![](https://neilpang.github.io/acmetest/status/ubuntu-14.04.svg?1561083135)| Fri, 21 Jun 2019 02:12:15 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/ubuntu-14.04.out) |
|debian:latest| ![](https://neilpang.github.io/acmetest/status/debian-latest.svg?1561083530)| Fri, 21 Jun 2019 02:18:50 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/debian-latest.out) |
|debian:9| ![](https://neilpang.github.io/acmetest/status/debian-9.svg?1561083940)| Fri, 21 Jun 2019 02:25:40 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/debian-9.out) |
|debian:8| ![](https://neilpang.github.io/acmetest/status/debian-8.svg?1561084298)| Fri, 21 Jun 2019 02:31:38 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/debian-8.out) |
|debian:7| ![](https://neilpang.github.io/acmetest/status/debian-7.svg?1561084719)| Fri, 21 Jun 2019 02:38:39 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/debian-7.out) |
|centos:latest| ![](https://neilpang.github.io/acmetest/status/centos-latest.svg?1561085132)| Fri, 21 Jun 2019 02:45:32 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/centos-latest.out) |
|centos:7| ![](https://neilpang.github.io/acmetest/status/centos-7.svg?1561085588)| Fri, 21 Jun 2019 02:53:08 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/centos-7.out) |
|centos:6| ![](https://neilpang.github.io/acmetest/status/centos-6.svg?1561086044)| Fri, 21 Jun 2019 03:00:44 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/centos-6.out) |
|fedora:latest| ![](https://neilpang.github.io/acmetest/status/fedora-latest.svg?1561086506)| Fri, 21 Jun 2019 03:08:26 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-latest.out) |
|fedora:27| ![](https://neilpang.github.io/acmetest/status/fedora-27.svg?1561086910)| Fri, 21 Jun 2019 03:15:10 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-27.out) |
|fedora:26| ![](https://neilpang.github.io/acmetest/status/fedora-26.svg?1561087333)| Fri, 21 Jun 2019 03:22:13 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-26.out) |
|fedora:25| ![](https://neilpang.github.io/acmetest/status/fedora-25.svg?1561087721)| Fri, 21 Jun 2019 03:28:41 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-25.out) |
|fedora:24| ![](https://neilpang.github.io/acmetest/status/fedora-24.svg?1561088155)| Fri, 21 Jun 2019 03:35:55 UTC| [Passed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-24.out) |
|fedora:23| ![](https://neilpang.github.io/acmetest/status/fedora-23.svg?1561088576)| Fri, 21 Jun 2019 03:42:56 UTC| [Failed](https://github.com/Neilpang/acmetest/blob/master/logs/fedora-23.out) |

# How to run tests

First point at least 2 of your domains to your machine, 
for example: `aa.com` and `www.aa.com`

And make sure 80 port is not used by anyone else.

```
cd acmetest
TestingDomain=aa.com   TestingAltDomains=www.aa.com  ./letest.sh
```

# How to run tests in all the platforms through docker.

You must have docker installed, and also point 2 of your domains to your machine.

Then test all the platforms :

```
cd acmetest
TestingDomain=aa.com   TestingAltDomains=www.aa.com  ./rundocker.sh  testall
```

The script will download all the supported platforms from the official docker hub, then run the test cases in all the supported platforms.

Then test single docker platform :

```
cd acmetest
TestingDomain=aa.com   TestingAltDomains=www.aa.com  ./rundocker.sh  testplat   centos:latest
```

# Run tests with ngrok automatically

If you don't want to use 2 domains to test, we can use ngrok to test with temp domain.

Please register an free account at https://ngrok.com/

You will get your ngrok auth token.  Then:

```
export NGROK_TOKEN="xxxxxxxxxx"

./letest.sh

```








