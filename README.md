# imp006 Breakout Board Hardware Abstraction Layer 1.0.0

Use the `BreakoutBoard_006` table to access the hardware pins, I&sup2;C sensor addresses, I&sup2;C and UART bus objects.

## BreakoutBoard_006

* LED_RED
* LED_GREEN
* LED_BLUE
* SENSOR_I2C
* TEMP_HUMID_I2C_ADDR
* ACCEL_I2C_ADDR
* BATT_I2C
* BATT_GAUGE_ADDR
* BATT_PMU_ADDR
* BATT_PMU_PIN_IRC
* BATT_PMU_PIN_BOOST
* MODEM_PWR_STATUS
* GROVE_PWR_GATE
* GROVE_DO
* GROVE_D1
* GROVE_A0
* GROVE_A1
* GROVE_I2C
* GROVE_UART
* CLICK_PIN_AN
* CLICK_PIN_RST
* CLICK_PIN_CS
* CLICK_PIN_SCLK
* CLICK_PIN_MISO
* CLICK_PIN_MOSI
* CLICK_PIN_SDA
* CLICK_PIN_SCL
* CLICK_PIN_TX
* CLICK_PIN_RX
* CLICK_PIN_INT
* CLICK_PIN_PWM
* J7_PIN_2
* J7_PIN_3
* J7_PIN_4
* J7_PIN_5
* J7_UART
* J15_PIN_2
* J15_PIN_3
* J15_PIN_4
* J15_PIN_5
* J15_UART
* BLUETOOTH
* WAKE_PIN_1
* WAKE_PIN_2

## Example

```squirrel
BreakoutBoard_006.SENSOR_I2C.configure(CLOCK_SPEED_400_KHZ);
tempHumid <- HTS221(BreakoutBoard_006.SENSOR_I2C, BreakoutBoard_006.TEMP_HUMID_I2C_ADDR);
```

## License

The imp006 Breakout Board Hardware Abstraction Layer is licensed under the [MIT License](/LICENSE).
