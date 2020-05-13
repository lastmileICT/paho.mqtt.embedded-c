# SPDX-License-Identifier: Apache-2.0

zephyr_include_directories(src)

target_sources(app PRIVATE src/MQTTConnectClient.c)
target_sources(app PRIVATE src/MQTTConnectServer.c)
target_sources(app PRIVATE src/MQTTDeserializePublish.c)
target_sources(app PRIVATE src/MQTTFormat.c)
target_sources(app PRIVATE src/MQTTPacket.c)
target_sources(app PRIVATE src/MQTTSerializePublish.c)
target_sources(app PRIVATE src/MQTTSubscribeClient.c)
target_sources(app PRIVATE src/MQTTSubscribeServer.c)
target_sources(app PRIVATE src/MQTTUnsubscribeClient.c)
target_sources(app PRIVATE src/MQTTUnsubscribeServer.c)
