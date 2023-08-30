## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301022/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301022/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"Humidity": "55"}
        - {"Time_sensor": "50"}
        - {"Airflow_Sensor": "80"}
        - {"Cool_Down": "10"}
        - {"imbalance": "12"}
        - {"Water_Level": "8"}
        - {"load": "6"}
        - {"noise_anomaly": "60"}
        - {"Rotating": "1000"}
        - {"detergent": "60"}
          
        
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/6310301022/model-01/sn-001
    - payload
        - {"Lid sensor": "on/off"}
        - {"Vibration": "8"}
        - {"current": "100"}
        - {"Child_Lock": "off"}




