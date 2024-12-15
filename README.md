```
gir clone https://github.com/kamibook/debbuild.git
tar -zxvf steamp-0.1.4-x86_64-unknown-linux-musl.tar.gz
cp steamp debbuild/usr/bin/
dpkg-deb --build steamp
```
