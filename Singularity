Bootstrap: docker
From: neubiaswg5/icy-base:latest

%files
	protocol.protocol /icy/protocols/protocol.protocol
	wrapper.py /icy/wrapper.py
	run.sh /icy/run.sh

%post
	cd /icy && chmod a+x run.sh
	cd /icy && chmod a+x wrapper.py

%runscript
	./icy/wrapper.py