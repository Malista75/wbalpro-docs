# How WbalPro Estimates Running Power Without a Sensor

## No footpod needed

WbalPro calculates your running power using only the sensors already built into your Garmin watch: GPS for speed and distance, barometer for elevation changes, and heart rate monitor for physiological context.

## What goes into the power calculation

Running power in WbalPro is estimated from three components:

1. **Power to run on flat ground** — based on your speed and body mass (set in your Garmin profile)
2. **Power to overcome wind** — based on wind settings you can configure manually in the app
3. **Power to climb or descend** — based on real-time gradient calculated from GPS and barometer

Formula concept: `Total Power = Flat running power + Wind resistance power + Climbing/descending power`

## Accuracy and limitations

- Power estimates are accurate enough for training purposes and race pacing
- GPS accuracy affects power on very short or winding segments
- Barometric altitude is more accurate than GPS altitude for gradient calculation
- Wind estimation requires manual input — WbalPro does not automatically detect wind speed
- The proprietary algorithm WbalPro uses for power estimation contains additional optimizations that are not publicly documented

## Tips for best accuracy

- Ensure your **body weight is up to date** in your Garmin profile
- **Calibrate the barometer** before important workouts if your watch allows it
- Set your wind speed and direction manually before races on windy days
