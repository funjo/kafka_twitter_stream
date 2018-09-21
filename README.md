# kafka_twitter_stream
A project that I use to play around with Kafka streaming process.

Run the application:
```
fangzhou$ mvn compile
fangzhou$ mvn exec:java -Dexec.mainClass=kafkaTwitterStream -Dexec.args="<twitter-consumer-key> <twitter-consumer-secret> <twitter-access-token> <twitter-access-token-secret> <topic-name> <twitter-search-keywords>"
```

For step by step guide, visit my blog at: https://fangzhoucheng.com/2018/09/21/real-time-kafka-streaming-twitter-hashtags-what-is-happening/
