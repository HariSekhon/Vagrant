#
#  Author: Hari Sekhon
#  Date: 2020-09-02 20:08:39 +0100 (Wed, 02 Sep 2020)
#
#  vim:ts=4:sts=4:sw=4:noet
#
#  https://github.com/HariSekhon/Vagrant
#
#  If you're using my code you're welcome to connect with me on LinkedIn and optionally send me feedback
#
#  https://www.linkedin.com/in/HariSekhon
#

include ../Makefile.in

.PHONY: boot
boot: arch
	vagrant up
	exec vagrant ssh debian
