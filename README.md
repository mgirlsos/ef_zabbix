# zabbix_agent
 

1.edit cron job  /etc/cron.d/zabbix 
##### cron job  for zabbix #####
*/2 * * * * zabbix bash /var/lib/ef_zabbix/cron/nc_vmstat_cron.sh
*/2 * * * * zabbix bash /var/lib/ef_zabbix/cron/nc_iostat_cron.sh
