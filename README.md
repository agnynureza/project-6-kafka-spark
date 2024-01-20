# project-6-kafka-spark

ETL process used python as main programming language, Kafka and Spark

1. Membuat Image Docker untuk project realtime streaming
<img src="img/01_build_image.png" width="700"/>

_Picture 1: build image_

2. Sign up pada Confluent, untuk menggunakan cloud kafka
<img src="img/02_create_confluent_kafka-ps.png" width="700"/>

_Picture 2: Confluent Kafka_

3. Docker Image berhasil di buat
<img src="img/03_docker_images.png" width="700"/>

_Picture 3: success Create Image Docker_


4. Container berhasil di run  
<img src="img/04_docker_image_running.png" width="700"/>

_Picture 4: success Run Container_

5. Check isi dari container
<img src="img/05_check_container.png" width="700"/>

_Picture 5: check container_

6. Generate Credential buat Confluent Kafka
<img src="img/06_create_kafka_cloud_key.png" width="700"/>

_Picture 6: Credential Kafka_

7. Pindahkan Credential di local ke container
<img src="img/07_cp_local_creden_to_docker.png" width="700"/>

_Picture 7: Copy Credential_


8. Test buat 1 topic di cloud kafka  
<img src="img/08_test_create_topic.png" width="700"/>

_Picture 8: test topic_

9. Check Topic Test yang baru saja di buat di confluent
<img src="img/09_check_topic_on_confluent_kafka.png" width="700"/>

_Picture 9: check test topic_

10. Buat 2 topic lain (raw and clean)
<img src="img/10_create_topic.png" width="700"/>

_Picture 10: topics_

11. Check topic yang baru saja dibuat
<img src="img/11_check_topic.png" width="700"/>

_Picture 11: check topic_


12. Testing Producer dan Consumer Confluent-Kafka  
<img src="img/12_test_producer_and_consumer.png" width="700"/>

_Picture 12: Producer & Consumer_

13. Push Data CSV (raw data) to topic reza-data-raw
<img src="img/13_push_reza_data_raw.png" width="700"/>

_Picture 13: push raw data to topic reza-data-raw_

14. Check raw daat yang di kirim ke topic reza-data-raw
<img src="img/14_check_topic_message.png" width="700"/>

_Picture 14: check raw data_

15. Consume reza-raw-data
<img src="img/15_clean_data_with_spark.png" width="700"/>

_Picture 15: cleaning data from topic raw-data_


16. Proses Transform data dan dikirim ke topic reza-clean-data
<img src="img/16_clean_data_from_topic_raw.png" width="700"/>

_Picture 16: transform to clean data_

17. Running Dashboard untuk melihat/consume dari topic reza-clean-data
<img src="img/17_running_dashboard_consume_topic_clean.png" width="700"/>

_Picture 17: running dashboard become consumer_

18. Check dashboard
<img src="img/18_check_dashboard.png" width="700"/>

_Picture 18: dashboard_


19. Realtime Streaming kafka and spark 
<img src="img/19_changes_stream_clean_data.png" width="700"/>

_Picture 19: realtime dashboard_

