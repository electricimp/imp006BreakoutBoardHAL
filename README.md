# imp006 Breakout Board Hardware Abstraction Layer

Use the imp006BreakoutBoard table to access the hardware pins, I&sup2;C sensor addresses, I&sup2;C and UART bus objects.

## imp006BreakoutBoard

* Coming soon

## Example

```squirrel
imp006BreakoutBoard.SENSOR_I2C.configure(CLOCK_SPEED_400_KHZ);
tempHumid <- HTS221(imp006BreakoutBoard.SENSOR_I2C, imp006BreakoutBoard.TEMP_HUMID_I2C_ADDR);
```

## License

The imp006 Breakout Board Hardware Abstraction Layer is licensed under the [MIT License](/LICENSE).
