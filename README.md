# LB1120
Perl script to talk to Netgear LB1120 / LB1121 LTE modem

```
Usage: LB1120 [OPTIONS] COMMAND
Where COMMAND := {
          inbox     Show contents of SMS InBox
          info      Print selection of useful information
          raw       Print raw JSON formatted data from LTE modem
          set       Use --config to set key=value in LTE modem
          sms       Send SMS message }
      OPTIONS := {
          -c, --config    Key=Value to set in LTS modem
          -d, --debug     Print debug information to STDOUT
          -h, --help      Show this help text, ignore all other OPTIONS or COMMAND
          -l  --log       Log info, warning and error to syslog
          -m, --message   Text for SMS message, enclose in "quotes if necessary"
          -p, --password  Password for LTE modem
          -s, --sendto    Phone number for recipient of SMS message
          -u, --url       IPv4, Domain or URL to LTE modem
          -v, --verbose   Print more information to STDOUT }
```



Inspired by https://github.com/amelchio/eternalegypt
