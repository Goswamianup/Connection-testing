# Connection Tester 
 
 small wrapper script for ping that reports on connectivity outage periods and packet loss rates.

 Installtion Guide 
 
  Sudo chmod +x connectiontesting
  
  sudo ./connectiontesting

  Options:
  -i INTERVAL          Ping interval in seconds (default: 3s)
  -t THRESHOLD         Show warning when time elapsed since last packet exceeds this value (default: 4s)
  -f REPORT_FREQUENCY  Report frequency in minutes (default: 15m)
  -d DOMAIN            Domain to append to the host
  --help               Display this help message
  -debug               Enable debug logging


  Example 
  sudo ./connectiontesting -i 3 -t 10 -f 10 example.com  google


  Use this  tool for eductional purpose  


                                               
