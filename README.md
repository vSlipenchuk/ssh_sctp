# ssh_sctp

This is https://mirror.yandex.ru/pub/OpenBSD/OpenSSH/portable/openssh-6.8p1.tar.gz
build with patch https://bugzilla.mindrot.org/attachment.cgi?id=2573
from https://bugzilla.mindrot.org/show_bug.cgi?id=1604 applied


To build it

 ./configure --with-sctp
 make

And call ssh client with "-z" key

 ssh -z MYSERVER.COM


