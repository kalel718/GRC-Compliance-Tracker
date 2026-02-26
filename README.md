
<img width="877" height="547" alt="Screen Shot 2026-02-26 at 11 47 25 AM" src="https://github.com/user-attachments/assets/e5b512af-1563-4153-b08f-a92e21d2fa2e" />

📉 GRC Compliance Trend Tracker
Overview
This project is an interactive Time-Series Analysis tool designed for Cybersecurity GRC (Governance, Risk, and Compliance) teams. It tracks an organization's compliance maturity over a 12-month period, providing a visual narrative of how security controls improve through consistent auditing and remediation.

🚀 🔗 View the Live Interactive Chart Here
(Note: Click the link above to hover over data points and see real-time compliance percentages.)
https://kalel718.github.io/GRC-Compliance-Tracker/

💡 The Business Case
In GRC, "Compliance is a journey, not a destination." This dashboard solves several key stakeholder problems:

For CISOs: Demonstrates the ROI of security awareness and training programs.

For Auditors: Provides historical evidence of "Continuous Monitoring," a core requirement for SOC 2 and ISO 27001.

For Managers: Identifies "bottleneck" months where compliance dipped, allowing for root-cause analysis.

🛠️ Technical Stack
Language: Python

Environment: Google Colab (Cloud-based execution for accessibility)

Key Libraries: * Pandas: Used for structuring the 12-month audit data.

Plotly Express: Used to build the interactive, hover-ready line graph.

Deployment: Hosted via GitHub Pages for zero-latency stakeholder access.

📊 Technical Analysis
Maturity Growth: The data shows a 30% increase in compliance over the calendar year, moving from a "reactive" to an "optimized" security state.

Inverse Correlation: As Percent Compliant increases, the number of Open Audit Findings trends downward, indicating a healthier security posture.

📝 How to Reproduce
Open the Compliance_Tracker.ipynb in Google Colab.

Run the script to generate the compliance_trend.html file.

To host your own interactive version, upload the HTML to a GitHub repo and enable GitHub Pages in the settings.
