# Era Payout calculations with different input parameters

Here you can input a `stake-and-treasury.csv` file with different parameters for the era payout calculation. Every row will lead to a new set of simulated output. This is captured in `output.csv` which shows the `stakerReward` and `outRemainder` (treasury inflow) on a yearly basis.

Run with  `cargo test -p polkadot-runtime simulate_v2 -- --nocapture`