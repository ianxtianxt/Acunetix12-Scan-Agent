# Acunetix12-Scan-Agent
awvs批量扫描
扫描规则存放于config.py


"full": "11111111-1111-1111-1111-111111111111",
"highrisk": "11111111-1111-1111-1111-111111111112",
"XSS": "11111111-1111-1111-1111-111111111116",
"SQL": "11111111-1111-1111-1111-111111111113",
"Weakpass": "11111111-1111-1111-1111-111111111115",
"crawlonly": "11111111-1111-1111-1111-111111111117"
                




如指定全部扫描
Usage : python3 Acunetix12-Scan-Agent.py -f url.txt full

如指定高危扫描
Usage : python3 Acunetix12-Scan-Agent.py -f url.txt highrisk
