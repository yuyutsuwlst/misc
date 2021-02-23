# misc


Amit Deo is inviting you to a scheduled Zoom meeting.

Topic: Amit Deo's Personal Meeting Room

Join Zoom Meeting
https://us04web.zoom.us/j/4569539504?pwd=MTRKMC9pNE1KSGY1WGl5REdaRDRSUT09

Meeting ID: 456 953 9504
Passcode: Ag2ed6


2021-02-22T11:25:13.660-0500: 6754275.823: [Full GC (Ergonomics) [PSYoungGen: 255328K->0K(5259264K)] [ParOldGen: 11046588K->5626359K(11185152K)] 11301916K->5626359K(16444416K), [Metaspace: 111247K->111247K(1155072K)], 37.4445907 secs] [Times: user=315.68 sys=7.78, real=37.44 secs]

Jvm params
=====================================================================================================================================================
57-13:55:31 /bin/java -Xms16g -Xmx16g -XX:+UseParallelOldGC -XX:+AlwaysPreTouch -server -Xss1m -Djava.awt.headless=true -Dfile.encoding=UTF-8 -Djna.nosys=true -XX:-OmitStackTraceInFastThrow -Dio.netty.noUnsafe=true -Dio.netty.noKeySetOptimization=true -Dio.netty.recycler.maxCapacityPerThread=0 -Dlog4j.shutdownHookEnabled=false -Dlog4j2.disable.jmx=true -XX:+HeapDumpOnOutOfMemoryError -XX:HeapDumpPath=/apps/elasticsearch -XX:+PrintGCDetails -XX:+PrintGCTimeStamps -XX:+PrintGCDateStamps -Xloggc:/apps/elasticsearch/logs/gc.log -XX:+UseGCLogFileRotation -XX:NumberOfGCLogFiles=32 -XX:GCLogFileSize=128M -agentpath:/nas/apps/agents/dynatrace/agent/lib64/libdtagent.so=name=p05-Elastic,server=seigwpprddync01.gwp.seic.com -Des.path.home=/usr/share/elasticsearch -Des.path.conf=/etc/elasticsearch -Des.distribution.flavor=default -Des.distribution.type=rpm -cp /usr/share/elasticsearch/lib/* org.elasticsearch.bootstrap.Elasticsearch -p /var/run/elasticsearch/elasticsearch.pid --quiet
