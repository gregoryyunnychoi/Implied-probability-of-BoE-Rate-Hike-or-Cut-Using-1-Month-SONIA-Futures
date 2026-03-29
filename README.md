## Implied probability of BoE Rate Hike or Cut Using 1-Month SONIA Futures

This project is inspired by the CME's [FedWatch Tool](https://www.cmegroup.com/articles/2023/understanding-the-cme-group-fedwatch-tool-methodology.html), which infers the probability of US Federal Reserve rate changes from Fed Funds futures. The CME FedWatch Tool uses the next full non‑FOMC month as an “anchor” to propagate implied EFFR levels backward and forward. While there is no direct UK equivalent, the closest instrument is the 1‑Month SONIA Index Future. However, this contract is far less liquid than the 3‑Month SONIA Future, which can introduce discrepancies. In practice, the market’s preferred instrument for gauging expectations of MPC rate decisions is the OIS swap curve.

You can find the .xlsx model that detail the calculation named BoEwatch-calculation-examples.xlsx

### Implied rate hike probability as of 24 March 2026

As of **24 March 2026**, the market-implied probabilities of Bank of England (BoE) rate hike at the April's Monetary Policy Committee (MPC) meetings on 30th April 2026, are as follows:

- **66% probability** of 1 25bps rate hike when using the **May 2026** SONIA futures contract as the anchor.

These probabilities suggest that the market expects **66% of 1 hike** in rate for April. The context here is Iran-US/Israel War 2026.

<img width="752" height="451" alt="image" src="https://github.com/user-attachments/assets/cfba71da-9094-4a3f-aac1-cf51518c1cec" />

## 1-Month SONIA Futures implied rate path

We also provide the piece of code (under [text](<API_Sonia_future_price_data.py>)) used to reconstruct the chart of future implied rates, illustrating the extent to which the MPC’s potential rate hikes or cuts are currently priced in.

Below is the one‑year forward implied rate as of 18 March 2026, a point at which the Iran–US/Israel conflict heightened market concerns about a renewed bout of supply‑driven inflation in the UK. At that time, markets were pricing in a wooping 4 rate hikes by the end of 2026. In my view, this reaction was significantly overdone at the time of writing, creating an opportunity to go long the December 3‑month SONIA future. 

<img width="2234" height="1259" alt="image" src="https://github.com/user-attachments/assets/50667de9-0f13-4616-9ecf-bf1af97ced1c" />
