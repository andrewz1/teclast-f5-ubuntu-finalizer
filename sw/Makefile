all:
	fakeroot dpkg-deb --build teclast-f5-finalizer_1.1-1

install: all
	sudo dpkg -i teclast-f5-finalizer_1.1-1.deb

clean:
	rm *.deb
