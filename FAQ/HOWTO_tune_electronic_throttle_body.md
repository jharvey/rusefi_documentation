
### Step 1. Set bias curve.


1.1 Calibrate throttle position sensor in your electronic throttle body.

Zero position usually requires you to push throttle closed. Full throttle would definitely require you to push throttle open.

Default position is usually somewhere around 4-8%.

1.1 Bias curve.

The goal is that at position X, the bias will hold it there on it's own.

We are interested in positions like 0, between-0-and-default, default, a bit open, a bit more open, 50% open, wide open, 

Set P=I=D=0. Set curve to all zeros.

Now use offset to manually control duty cycle. Try different values and see which offset sets throttle to closed, which offset
starts to open throttle, which offset is enough to open throttle completely.
  

