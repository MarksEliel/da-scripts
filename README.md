# da-scripts
Scripts para DirectAdmin

#Rebuild Total\
chmod 755 /root/etc-virtual-fix.sh\
/root/etc-virtual-fix.sh\
\
\
#Rebuild Domains\
cd /etc/\
chmod 755 fix_domains.sh\
./fix_domains.sh > domains\
chmod 644 domains\
chown mail:mail domains\
\
\
#Rebuild Domain Owners\
cd /etc/virtual\
chmod 755 fix_domainowners.sh\
./fix_domainowners.sh > domainowners\
chmod 644 domainowners\
chown mail:mail domainowners\
