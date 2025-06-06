# Trading Strategy Documentation

## Strategy Parameters

| Parameter | Value | Description |
|-----------|-------|-------------|
| Lookback Period | 20 bars | Number of bars to look back for high/low calculation |
| Drop Percentage | 10% | Percentage drop from high to trigger entry |
| Minimum Bars Between Trades | 3 | Minimum bars required between consecutive trades |
| Take Profit | 20% | Target profit percentage from entry |
| Time Filter | 30 days | Only trades within the last 30 days |
| Position Size | 100% | Percentage of equity per trade |

## Entry Conditions

1. Price drops 10% from the 20-bar high
2. Trade occurs within last 30 days
3. Minimum 3 bars since last trade
4. No existing position

## Exit Conditions

1. Take profit at 20% above entry price
2. No stop loss (can be added if needed)

## Trade Management

| Aspect | Setting | Purpose |
|--------|---------|---------|
| Position Sizing | 100% equity | Maximum capital utilization |
| Trade Frequency | Every 3+ bars | Prevents overtrading |
| Time Window | 30 days | Current market conditions only |
| Lookback | 20 bars | Short-term price action |

## Visual Indicators

| Indicator | Color | Purpose |
|-----------|-------|---------|
| Drop Level | Red | Entry trigger level |
| High Level | Green | 20-bar high |
| Low Level | Blue | 20-bar low |
| High Bar | Green Triangle | Marks highest bar |
| Low Bar | Blue Triangle | Marks lowest bar |

## Strategy Logic

1. Calculate highest price over last 20 bars
2. Calculate drop level (10% below high)
3. Enter when price closes below drop level
4. Take profit at 20% above entry
5. Wait minimum 3 bars before next trade
6. Only trade within last 30 days

## Risk Management

- Position sizing: 100% of equity per trade
- Minimum bars between trades: 3
- Current market focus: 30-day window
- Take profit: 20% fixed target

## Notes

- Strategy is designed for current market conditions
- Uses short-term price action (20 bars)
- Takes advantage of 10% pullbacks
- Aims for 20% profit targets
- No stop loss implemented (can be added)
- Trades only in last 30 days for current trend

111,587.10	111,586.25	
−0.85
USD
Commission for: Close short position for symbol COMEX:GC1! at price 3350.1 for 1 units. Position AVG Price was 3374.800000, currency: USD, rate: 1.000000, point value: 100.000000
109,117.10	111,587.10	
+2,470.00
USD
Close short position for symbol COMEX:GC1! at price 3350.1 for 1 units. Position AVG Price was 3374.800000, currency: USD, rate: 1.000000, point value: 100.000000
109,118.80	109,117.10	
−1.70
USD
Commission for: Close short position for symbol COMEX_MINI:MGC1! at price 3351.4 for 2 units. Position AVG Price was 3375.000000, currency: USD, rate: 1.000000, point value: 10.000000
108,646.80	109,118.80	
+472.00
USD
Close short position for symbol COMEX_MINI:MGC1! at price 3351.4 for 2 units. Position AVG Price was 3375.000000, currency: USD, rate: 1.000000, point value: 10.000000
108,647.65	108,646.80	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:ES1! at price 5973.75 for 1 units. Position AVG Price was 5955.000000, currency: USD, rate: 1.000000, point value: 50.000000
107,710.15	108,647.65	
+937.50
USD
Close long position for symbol CME_MINI:ES1! at price 5973.75 for 1 units. Position AVG Price was 5955.000000, currency: USD, rate: 1.000000, point value: 50.000000
107,711.00	107,710.15	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:ES1! at price 5955.00 for 1 units
107,711.85	107,711.00	
−0.85
USD
Commission for: Close long position for symbol CBOT_MINI:YM1! at price 42477 for 1 units. Position AVG Price was 42480.000000, currency: USD, rate: 1.000000, point value: 5.000000
107,726.85	107,711.85	
−15.00
USD
Close long position for symbol CBOT_MINI:YM1! at price 42477 for 1 units. Position AVG Price was 42480.000000, currency: USD, rate: 1.000000, point value: 5.000000
107,727.70	107,726.85	
−0.85
USD
Commission for: Enter position for symbol CBOT_MINI:YM1! at price 42480.00 for 1 units
107,728.55	107,727.70	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:MNQ1! at price 21858.25 for 1 units. Position AVG Price was 21747.750000, currency: USD, rate: 1.000000, point value: 2.000000
107,507.55	107,728.55	
+221.00
USD
Close long position for symbol CME_MINI:MNQ1! at price 21858.25 for 1 units. Position AVG Price was 21747.750000, currency: USD, rate: 1.000000, point value: 2.000000
107,508.40	107,507.55	
−0.85
USD
Commission for: Close long position for symbol CBOT_MINI:MYM1! at price 42727 for 1 units. Position AVG Price was 42469.000000, currency: USD, rate: 1.000000, point value: 0.500000
107,379.40	107,508.40	
+129.00
USD
Close long position for symbol CBOT_MINI:MYM1! at price 42727 for 1 units. Position AVG Price was 42469.000000, currency: USD, rate: 1.000000, point value: 0.500000
107,380.25	107,379.40	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:ES1! at price 5993.75 for 1 units. Position AVG Price was 5975.250000, currency: USD, rate: 1.000000, point value: 50.000000
106,455.25	107,380.25	
+925.00
USD
Close long position for symbol CME_MINI:ES1! at price 5993.75 for 1 units. Position AVG Price was 5975.250000, currency: USD, rate: 1.000000, point value: 50.000000
106,456.10	106,455.25	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:ES1! at price 5975.25 for 1 units
106,456.95	106,456.10	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:MNQ1! at price 21747.75 for 1 units
106,457.80	106,456.95	
−0.85
USD
Commission for: Enter position for symbol CBOT_MINI:MYM1! at price 42469 for 1 units
106,458.65	106,457.80	
−0.85
USD
Commission for: Close long position for symbol CBOT_MINI:MYM1! at price 42471 for 1 units. Position AVG Price was 42480.000000, currency: USD, rate: 1.000000, point value: 0.500000
106,463.15	106,458.65	
−4.50
USD
Close long position for symbol CBOT_MINI:MYM1! at price 42471 for 1 units. Position AVG Price was 42480.000000, currency: USD, rate: 1.000000, point value: 0.500000
106,464.00	106,463.15	
−0.85
USD
Commission for: Enter position for symbol CBOT_MINI:MYM1! at price 42480.00 for 1 units
106,464.85	106,464.00	
−0.85
USD
Commission for: Close short position for symbol CME_MINI:MNQ1! at price 21754.50 for 1 units. Position AVG Price was 21786.250000, currency: USD, rate: 1.000000, point value: 2.000000
106,401.35	106,464.85	
+63.50
USD
Close short position for symbol CME_MINI:MNQ1! at price 21754.50 for 1 units. Position AVG Price was 21786.250000, currency: USD, rate: 1.000000, point value: 2.000000
106,402.20	106,401.35	
−0.85
USD
Commission for: Close short position for symbol CME_MINI:ES1! at price 5982.50 for 1 units. Position AVG Price was 5989.250000, currency: USD, rate: 1.000000, point value: 50.000000
106,064.70	106,402.20	
+337.50
USD
Close short position for symbol CME_MINI:ES1! at price 5982.50 for 1 units. Position AVG Price was 5989.250000, currency: USD, rate: 1.000000, point value: 50.000000
106,065.55	106,064.70	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:ES1! at price 5989.25 for 1 units
106,066.40	106,065.55	
−0.85
USD
Commission for: Close long position for symbol NYMEX:CL1! at price 62.92 for 1 units. Position AVG Price was 62.710000, currency: USD, rate: 1.000000, point value: 1000.000000
105,856.40	106,066.40	
+210.00
USD
Close long position for symbol NYMEX:CL1! at price 62.92 for 1 units. Position AVG Price was 62.710000, currency: USD, rate: 1.000000, point value: 1000.000000
105,857.25	105,856.40	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:MNQ1! at price 21786.25 for 1 units
105,861.50	105,857.25	
−4.25
USD
Commission for: Enter position for symbol CME:MBT1! at price 105835 for 5 units
105,862.35	105,861.50	
−0.85
USD
Commission for: Enter position for symbol NYMEX:CL1! at price 62.71 for 1 units
106,053.60	105,862.35	
−191.25
USD
Commission for: Enter position for symbol CME:MET1! at price 2658.5 for 225 units
106,057.85	106,053.60	
−4.25
USD
Commission for: Close long position for symbol CME:MBT1! at price 105975 for 5 units. Position AVG Price was 105350.000000, currency: USD, rate: 1.000000, point value: 0.100000
105,745.35	106,057.85	
+312.50
USD
Close long position for symbol CME:MBT1! at price 105975 for 5 units. Position AVG Price was 105350.000000, currency: USD, rate: 1.000000, point value: 0.100000
105,746.20	105,745.35	
−0.85
USD
Commission for: Close short position for symbol NYMEX:CL1! at price 62.39 for 1 units. Position AVG Price was 63.420000, currency: USD, rate: 1.000000, point value: 1000.000000
104,716.20	105,746.20	
+1,030.00
USD
Close short position for symbol NYMEX:CL1! at price 62.39 for 1 units. Position AVG Price was 63.420000, currency: USD, rate: 1.000000, point value: 1000.000000
104,724.70	104,716.20	
−8.50
USD
Commission for: Close short position for symbol NYMEX:MCL1! at price 62.61 for 10 units. Position AVG Price was 63.360000, currency: USD, rate: 1.000000, point value: 100.000000
103,974.70	104,724.70	
+750.00
USD
Close short position for symbol NYMEX:MCL1! at price 62.61 for 10 units. Position AVG Price was 63.360000, currency: USD, rate: 1.000000, point value: 100.000000
103,978.95	103,974.70	
−4.25
USD
Commission for: Enter position for symbol CME:MBT1! at price 105350 for 5 units
103,979.80	103,978.95	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:MNQ1! at price 21716.00 for 1 units. Position AVG Price was 21742.250000, currency: USD, rate: 1.000000, point value: 2.000000
104,032.30	103,979.80	
−52.50
USD
Close long position for symbol CME_MINI:MNQ1! at price 21716.00 for 1 units. Position AVG Price was 21742.250000, currency: USD, rate: 1.000000, point value: 2.000000
104,033.15	104,032.30	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:ES1! at price 5994.00 for 1 units. Position AVG Price was 5987.750000, currency: USD, rate: 1.000000, point value: 50.000000
103,720.65	104,033.15	
+312.50
USD
Close long position for symbol CME_MINI:ES1! at price 5994.00 for 1 units. Position AVG Price was 5987.750000, currency: USD, rate: 1.000000, point value: 50.000000
103,724.90	103,720.65	
−4.25
USD
Commission for: Close short position for symbol CME:MBT1! at price 106785 for 5 units. Position AVG Price was 106880.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,677.40	103,724.90	
+47.50
USD
Close short position for symbol CME:MBT1! at price 106785 for 5 units. Position AVG Price was 106880.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,681.65	103,677.40	
−4.25
USD
Commission for: Enter position for symbol CME:MBT1! at price 106880 for 5 units
103,690.15	103,681.65	
−8.50
USD
Commission for: Enter position for symbol NYMEX:MCL1! at price 63.36 for 10 units
103,691.00	103,690.15	
−0.85
USD
Commission for: Enter position for symbol NYMEX:CL1! at price 63.42 for 1 units
103,695.25	103,691.00	
−4.25
USD
Commission for: Close long position for symbol CME:MBT1! at price 106950 for 5 units. Position AVG Price was 106620.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,530.25	103,695.25	
+165.00
USD
Close long position for symbol CME:MBT1! at price 106950 for 5 units. Position AVG Price was 106620.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,721.50	103,530.25	
−191.25
USD
Commission for: Close long position for symbol CME:MET1! at price 2636.5 for 225 units. Position AVG Price was 2635.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,687.75	103,721.50	
+33.75
USD
Close long position for symbol CME:MET1! at price 2636.5 for 225 units. Position AVG Price was 2635.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,688.60	103,687.75	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:MNQ1! at price 21742.25 for 1 units
103,879.85	103,688.60	
−191.25
USD
Commission for: Enter position for symbol CME:MET1! at price 2635.0 for 225 units
103,880.70	103,879.85	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:ES1! at price 5987.75 for 1 units
103,884.95	103,880.70	
−4.25
USD
Commission for: Enter position for symbol CME:MBT1! at price 106620 for 5 units
103,885.80	103,884.95	
−0.85
USD
Commission for: Enter position for symbol COMEX:GC1! at price 3374.8 for 1 units
103,887.50	103,885.80	
−1.70
USD
Commission for: Enter position for symbol COMEX_MINI:MGC1! at price 3375.0 for 2 units
103,889.20	103,887.50	
−1.70
USD
Commission for: Close long position for symbol COMEX_MINI:MGC1! at price 3409.5 for 2 units. Position AVG Price was 3395.900000, currency: USD, rate: 1.000000, point value: 10.000000
103,617.20	103,889.20	
+272.00
USD
Close long position for symbol COMEX_MINI:MGC1! at price 3409.5 for 2 units. Position AVG Price was 3395.900000, currency: USD, rate: 1.000000, point value: 10.000000
103,621.45	103,617.20	
−4.25
USD
Commission for: Close long position for symbol CME:MBT1! at price 105735 for 5 units. Position AVG Price was 104725.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,116.45	103,621.45	
+505.00
USD
Close long position for symbol CME:MBT1! at price 105735 for 5 units. Position AVG Price was 104725.000000, currency: USD, rate: 1.000000, point value: 0.100000
103,307.70	103,116.45	
−191.25
USD
Commission for: Close long position for symbol CME:MET1! at price 2584.0 for 225 units. Position AVG Price was 2561.000000, currency: USD, rate: 1.000000, point value: 0.100000
102,790.20	103,307.70	
+517.50
USD
Close long position for symbol CME:MET1! at price 2584.0 for 225 units. Position AVG Price was 2561.000000, currency: USD, rate: 1.000000, point value: 0.100000
102,791.05	102,790.20	
−0.85
USD
Commission for: Close long position for symbol COMEX:GC1! at price 3409.5 for 1 units. Position AVG Price was 3396.900000, currency: USD, rate: 1.000000, point value: 100.000000
101,531.05	102,791.05	
+1,260.00
USD
Close long position for symbol COMEX:GC1! at price 3409.5 for 1 units. Position AVG Price was 3396.900000, currency: USD, rate: 1.000000, point value: 100.000000
101,531.90	101,531.05	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:ES1! at price 5945.50 for 1 units. Position AVG Price was 5915.500000, currency: USD, rate: 1.000000, point value: 50.000000
100,031.90	101,531.90	
+1,500.00
USD
Close long position for symbol CME_MINI:ES1! at price 5945.50 for 1 units. Position AVG Price was 5915.500000, currency: USD, rate: 1.000000, point value: 50.000000
100,032.75	100,031.90	
−0.85
USD
Commission for: Close long position for symbol CME_MINI:MNQ1! at price 21535.75 for 1 units. Position AVG Price was 21419.500000, currency: USD, rate: 1.000000, point value: 2.000000
99,800.25	100,032.75	
+232.50
USD
Close long position for symbol CME_MINI:MNQ1! at price 21535.75 for 1 units. Position AVG Price was 21419.500000, currency: USD, rate: 1.000000, point value: 2.000000
99,801.10	99,800.25	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:MNQ1! at price 21419.50 for 1 units
99,802.80	99,801.10	
−1.70
USD
Commission for: Enter position for symbol COMEX_MINI:MGC1! at price 3395.90 for 2 units
99,803.65	99,802.80	
−0.85
USD
Commission for: Enter position for symbol COMEX:GC1! at price 3396.90 for 1 units
99,994.90	99,803.65	
−191.25
USD
Commission for: Enter position for symbol CME:MET1! at price 2561.00 for 225 units
99,995.75	99,994.90	
−0.85
USD
Commission for: Enter position for symbol CME_MINI:ES1! at price 5915.50 for 1 units
100,000.00	99,995.75	
−4.25
USD
Commission for: Enter position for symbol CME:MBT1! at price 104725.00 for 5 units
