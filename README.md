# 5
Данный скрипт реализует примитивную защиту от ddos
Он запускается по cron считает кол-во процессов httpd если их > 100 то добавляет ip с которого больше всего запросов  в .httaccess deny from <ip addr>
	
DDOS будем siege (siege -c150 -t60S -b http://192.168.1.25/)
