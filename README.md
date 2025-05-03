<details>
<summary>LICENSE</summary>

MIT License

Copyright (c) 2025 Perpetual Velocity

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

</details>

# Perpetual Velocity Dashboard 📊

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.10+-red.svg)](https://streamlit.io)
[![Plotly](https://img.shields.io/badge/Plotly-5.3+-orange.svg)](https://plotly.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Overview 📋

Perpetual Velocity is a dynamic business metrics dashboard that helps companies visualize and track their key performance indicators across multiple dimensions. Built with Streamlit and Plotly, it provides intuitive visualizations including bubble charts, line graphs, radar plots, and more to help business leaders understand their company's performance at a glance.

![Perpetual Velocity Dashboard](https://github.com/Siddhant231xyz/Perpetual_Velocity/raw/main/screenshots/dashboard.png)

## Features ✨

- 📈 **Health Score Tracking**
  - Monitor your company's overall health with a composite score
  - Track score changes over time with interactive timeline

- 🎯 **Quadrant Analysis**
  - Visualize company position in four performance quadrants
  - Identify if your business is Scaling, Potential, Struggling, or Declining

- 💰 **Metric Clusters**
  - Financial metrics (Revenue Growth, MRR, Burn Rate)
  - Customer metrics (Retention Rate, Churn Rate)
  - Operational metrics (Efficiency, Product Adoption, User Engagement)
  - Risk analysis (Regulatory, Market, Financial, Operational)

- 🔍 **Advanced Analytics**
  - Feature importance analysis using Random Forest
  - Correlation matrix for numeric metrics
  - Simple MRR forecasting

- 📊 **Data Flexibility**
  - Use your own data via CSV/XLSX upload
  - Generate synthetic data for demonstration purposes

## Quick Start 🚀

### Prerequisites

- Python 3.7+
- pip

### Local Installation

1. Clone the repository:

```bash
git clone https://github.com/username/perpetual-velocity.git
cd perpetual-velocity
```

2. Set up virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

### Usage

1. Start the application:

```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Either:
   - Click "Generate demo data" to use synthetic data
   - Upload your own CSV or Excel file with the required columns

## Data Format 📋

If uploading your own data, ensure it includes these key columns:

| Column | Description |
|--------|-------------|
| `Month` | Time period indicator (integer) |
| `HealthScore` | Overall company health metric |
| `MRR_kUSD` | Monthly Recurring Revenue in thousands of USD |
| `MarketInfluence` | Metric combining MRR and growth |
| `Quadrant` | Classification (1-4) representing company status |
| `RevenueGrowthRate_%` | Percentage growth in revenue |
| `BurnRate_kUSD` | Cash burn rate in thousands of USD |
| `CustomerRetentionRate_%` | Percentage of customers retained |
| `ChurnRate_%` | Percentage of customers lost |
| `OperationalEfficiency_%` | Operational efficiency score |
| `ProductAdoptionRate_%` | Rate of product adoption |
| `UserEngagement_%` | User engagement metric |
| `EmployeeProductivity` | Productivity score |
| `DiversityInclusion_%` | Diversity and inclusion metric |
| `RegulatoryComplianceRisk_%` | Regulatory risk assessment |
| `MarketCompetitiveTrends_%` | Market trend assessment |
| `CashFlowStability` | Cash flow stability metric |

## Project Structure 🏗️

```
perpetual-velocity/
├── app.py                 # Main Streamlit application
├── requirements.txt       # Project dependencies
├── README.md              # Project documentation
├── LICENSE                # MIT License
├── screenshots/           # Example screenshots
│   └── dashboard.png      # Dashboard preview image
```

## Contributing 🤝

We welcome contributions! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Roadmap 🛣️

- [ ] Add more advanced predictive analytics
- [ ] Implement goal tracking
- [ ] Add custom metric creation
- [ ] Create exportable reports
- [ ] Add user authentication
- [ ] Support real-time data integration
- [ ] Add industry benchmarking

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Streamlit team for the amazing framework
- Plotly for the interactive visualizations
- Scikit-learn for the analytics capabilities
- All our contributors and supporters

---

<div align="center">
Made with ❤️ by the Perpetual Velocity Team
</div>
