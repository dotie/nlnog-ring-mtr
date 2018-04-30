# nlnog-ring-mtr
Polls the current active list of Nlnog ring nodes, runs an MTR to each and outputs the data to Logstash over a UDP pipeline. 

Useful for monitoring path changes etc.

Crontab:
@hourly /opt/scripts/ringer
