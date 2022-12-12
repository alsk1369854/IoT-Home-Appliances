# IoT Home Appliances
基於ESP8266與SG90舵機之遙控開關，分為以下兩種版本:

1. IoT Home Appliances Access Point (將設備作為AP節點操作)
2. IoT Home Appliances Ｗith Router (將設備連上WiFi操作)

## 1. IoT Home Appliances Access Point (將設備作為AP節點操作)
設備預設配置如下
```
# Pin 
設備正常工作提示LED: 0
開關舵機: 2

# 設備 AP 配置
SSID: Switch AP
Password: 12345678

# 遙控介面 DNS 配置
http://www.switch.com

# 相關 API
開(動作): http://www.switch.com/operate?operate=on
關(動作): http://www.switch.com/operate?operate=off
```

## 2. IoT Home Appliances Ｗith Router (將設備連上WiFi操作)
設備預設配置如下
```
# Pin 
設備正常工作提示LED: 0
開關舵機: 2

# WiFiManager 配置
SSID: Switch AP
Password: 12345678
WiFi 設定頁面: http://192.168.4.1

# 遙控介面
http://192.168.1.6

# 相關 API
開(動作): http://192.168.1.6/operate?operate=on
關(動作): http://192.168.1.6/operate?operate=off
```

## DEMO
<p align="center">
    <img height="400px" src="https://raw.githubusercontent.com/alsk1369854/IoTHomeAppliances/master/screenshot/DeviceWorkingVideo.gif"/>
</p>

#### _END_