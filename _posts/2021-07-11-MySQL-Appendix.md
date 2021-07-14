---
layout: post
title:  "이것이 MySQL이다 - Appendix. Linux 환경에서 MySQL "
---

# 1.4 Linux에 MySQL 설치
<설치>
dnf -y install http://....noarch.rpm
dnf -y install mysql-community-server
아니면
wget http://download....tar
chmod 644 mysql80.tar
tar xf mysql80.tar
dnf -y install *.rpm

<MySQL 서비스 시작, 외부에서 접속할 수 있도록 설정>
