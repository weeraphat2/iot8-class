## How do you design MQTT topics and payloads for smart washing machine

1. สถานะเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001/
    - payload
        - {"STATUS": "POWER ON|START|STOP|FINISHED|POWERED OFF"}
1. เซนเซอร์ภายในเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"temperature": "25.2"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        

 1. เซนเซอร์ภายนอกเครื่องซักผ้า
    - topic:v1cdti/app/get/1212312121/model-01/sn-001
    - payload
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}
        - {"name": "value"}



