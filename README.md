#add these lines in  opkg/customfeeds.conf
```
src/gz passwall_luci https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall_luci
src/gz passwall_packages https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall_packages
src/gz passwall2 https://master.dl.sourceforge.net/project/openwrt-passwall-build/releases/packages-22.03/mips_24kc/passwall2
```

#then run
```
rm -f passwallx.sh && wget https://raw.githubusercontent.com/zeustm/Passwall/main/passwallx.sh && chmod 777 passwallx.sh && sh passwallx.sh
```

