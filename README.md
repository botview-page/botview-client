  ./common-client -setConfig
  ./common-client -loadClient=<"CLIENT ID"/LIST>
  ./common-client -printConfiguration
  ./common-client -warmupCache [./path/to/URLlist FILE (optional)]
  ./common-client -purgeAllCache
  ./common-client -purgeURLCache <URI> OR <Image URL> OR <./path/to/URLlist FILE>
  ./common-client -downloadLogReport <date>
  ./common-client -reloadMyConf
  ./common-client -updateTTL=<TTL>
  ./common-client -getStats=<month>
  ./common-client -fetchLiveLogs
  ./common-client -whitelistIPs <Space separated IPV4 and IPV6>
