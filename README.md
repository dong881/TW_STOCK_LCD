# TW_STOCK_LCD
Get Taiwan stock on 1602 LCD

# Requirements
- Python 3
- lxml
- requests
- Install GitHub lib
```bash
python -m pip install --user twstock
sudo pip install RPLCD
```

# [Lines and Connections]

| Raspberry Pi Pin | LCD1602 I2C Pin |
|------------------|------------------|
| Pin 4 (+5V)      | VCC              |
| Pin 6 (GND)      | GND              |
| Pin 3            | SDA              |
| Pin 5            | SCL              |

![image](https://github.com/dong881/TW_STOCK_LCD/assets/52557611/de4a6b98-cde0-4732-8c53-d63c415c0bf7)
![image](https://github.com/dong881/TW_STOCK_LCD/assets/52557611/349ef730-69e6-4928-8d00-4238b0307019)

# Reference
https://github.com/mlouielu/twstock
https://github.com/dbrgn/RPLCD
