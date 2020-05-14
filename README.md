# imp006 Breakout Board Hardware Abstraction Layer

Use the `BreakoutBoard_006` table to access the hardware pins, I&sup2;C sensor addresses, I&sup2;C and UART bus objects.

## BreakoutBoard_006

* Coming soon

## Example

```squirrel
BreakoutBoard_006.SENSOR_I2C.configure(CLOCK_SPEED_400_KHZ);
tempHumid <- HTS221(BreakoutBoard_006.SENSOR_I2C, BreakoutBoard_006.TEMP_HUMID_I2C_ADDR);
```

## License

The imp006 Breakout Board Hardware Abstraction Layer is licensed under the [MIT License](/LICENSE).
