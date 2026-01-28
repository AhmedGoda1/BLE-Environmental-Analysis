# BLE-Environmental-Analysis

## Scanning Environments
1. **Classroom (the silent room):** High density, mostly personal wearables and tablets.
2. **Hallway:** Moderate density, mostly stationary beacons and hidden infrastructure.
3. **Saviona Campus Heart:** Low density, high interference from distance and environmental noise.

## Technical Analysis
- **RSSI Logic:** Distance follows the Inverse Square Law; a -10 dBm drop roughly correlates to doubling the distance in open space.
- **Physical Obstructions:** Walls caused drop in the hallway scan compared to line-of-sight.

## Security Discussion
BLE's constant advertising makes "Passive Tracking" a major risk. Even with MAC randomization, unique GATT profiles can sometimes be used to fingerprint specific users.

## Conclusion
BLE is effective for proximity but highly susceptible to environmental interference and privacy leaks.
