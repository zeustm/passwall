#installition   for  rb951ui-2hnd            add these lines in  opkg/customfeeds.conf
```
src/gz passwall_luci https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall_luci
src/gz passwall_packages https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall_packages
src/gz passwall2 https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall2
```

#then run to install passwall
```

rm -f passwallx.sh && wget https://raw.githubusercontent.com/zeustm/passwall/main/passwallx.sh && chmod 777 passwallx.sh && sh passwallx.sh
```
#then run to install xray
```
rm -f amirhossein.sh && wget https://raw.githubusercontent.com/zeustm/passwall/main/amirhossein.sh && chmod 777 amirhossein.sh && sh amirhossein.sh
```

