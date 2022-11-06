# Forex-Indicator
Analysis the market
This is the script that finds Consolidation Zones in Realtime.

How it works?
- The script finds highest/lowest bars by using "Loopback Period"
- Then it calculates direction
- By using the direction and highest/lowest bar info it calculates consolidation zones in realtime
- If the length of consolidation area is equal/greater than user-defined min length then this area is shown as consolidation zone
- Then Consolidation Zone extends automatically if there is no breakout

if you increase the Loopback Length then you get bigger consolidation zones:
