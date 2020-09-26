# neomirror
NeoHosts Ad/Tracker Blocklist Mirror

This is simply a mirror of the ad/tracker blocklist for PiHole (and others?) that was sourced off of neoFelhz's Blog which used to be at https://hosts.nfz.moe/basic/hosts which now returns a "Not Found" error.

Originally found this list under the "Suspicious Lists" category of Wally3k's Big Blacklist Collection here: https://firebog.net/

Just recreating the last cached version of the list my PiHole had on here so it stops giving me these errors:
  [i] Target: https://hosts.nfz.moe/basic/hosts
  [✗] Status: Not found
  [✗] List download failed: using previously cached list
  [i] Received 4823 domains

...in case my cached list ever gets inadvertently removed. Don't want to lose these domains since they have been getting picked from quite a bit:

id          enabled     total_domains  domains_covered  hits_covered  unique_domains_covered  address
----------  ----------  -------------  ---------------  ------------  ----------------------  ----------------------------------------------------------------
29          1           211970         528              245320        100                     https://www.github.developerdan.com/hosts/lists/ads-and-trackint
1           1           56949          375              212704        1                       https://raw.githubusercontent.com/StevenBlack/hosts/master/host
12          1           7950           282              206692                                https://adaway.org/hosts.txt
15          1           40870          322              201904        10                      https://raw.githubusercontent.com/anudeepND/blacklist/master/ad
20          1           18707          299              178007        4                       https://raw.githubusercontent.com/bigdargon/hostsVN/master/host
13          1           36360          105              95869         2                       https://v.firebog.net/hosts/AdguardDNS.txt
50          1           20567          182              88704         3                       http://sysctl.org/cameleon/hosts
10          1           4823           92               77384                                 https://hosts.nfz.moe/basic/hosts

If the blog ever returns I'll just delete this mirror as it won't be added to, it's just for clearing the error from PiHole.
