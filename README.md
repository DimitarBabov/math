# math
Math problems and simulations

## Projects

### [Crossing the Stream](car-collision-sim/index.html)

A car crosses a lane of steady traffic at a random moment. How often does it get hit?

- Stream cars: 1 m long, ½ m wide, 10 m gap, 10 m/s
- Crossing car: 1 m long, ½ m wide, 10 m/s
- Answer: **3/11 ≈ 27.3%** (3/10 if the 10 m is centre to centre)

General formula:

```
P = [L_h + w_v + (v_h / v_v)(L_v + w_h)] / (L_h + gap)
```

The page animates the crossing, predicts each crash with the formula, and checks the answer with a time-stepped Monte Carlo run. Open `car-collision-sim/index.html` in a browser; it works on phones too.
