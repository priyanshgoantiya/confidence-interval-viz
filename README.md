# confidence-interval-viz
Deployed-https://vqpmrhmqzpu6y5twsbinnm.streamlit.app/
## 🧪 Confidence Interval Simulation

This interactive simulation helps visualize how different types of confidence intervals behave over multiple random samples from a normal distribution.

You can explore:
- **Z-distribution using population standard deviation (σ)** — when population standard deviation is known.
- **Z-distribution using sample standard deviation (s)** — less common, but for comparison.
- **t-distribution using sample standard deviation (s)** — used when population standard deviation is unknown and sample size is small.

### 🔍 How it works:
- We simulate repeated sampling from a normal distribution.
- For each sample, we compute a confidence interval for the mean.
- If the interval captures the **true population mean**, it’s shown in **blue**; otherwise in **orange**.
- The red horizontal line represents the **true population mean**.

This tool demonstrates how often confidence intervals actually capture the population mean depending on:
- **Sample size**
- **Confidence level**
- **Distribution used (Z vs. T)**

Use the sliders in the sidebar to tweak parameters and understand how uncertainty and variability influence confidence intervals.
