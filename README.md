<!-- ================= HEADER (animated typing line below) ================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:001F3F,100:004080&height=220&section=header&text=Omar%20Toufelaz&fontColor=ffffff&fontSize=55&desc=%20&descAlignY=65" alt="banner"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2500&pause=700&color=FFFFFF&center=true&vCenter=true&width=760&lines=ENPC+%7C+Applied+Math+%26+CS;Quant+Research+%7C+AI+%2F+ML+Research;Python+%7C+C%2B%2B+%7C+PyTorch+%7C+scikit-learn" alt="typing animation"/>
</p>

<!-- ================= CONTACT ================= -->
<p align="center">
  <a href="mailto:omar.toufelaz@enpc.fr"><img src="https://img.shields.io/badge/Email-omar.toufelaz%40enpc.fr-0078D4?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/omar-toufelaz/"><img src="https://img.shields.io/badge/LinkedIn-Omar%20Toufelaz-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <img src="https://komarev.com/ghpvc/?username=Omartfz&style=for-the-badge&color=004080&label=Profile+Views" alt="profile views"/>
</p>

---

## About Me

2nd-year **engineering student in Applied Mathematics & Computer Science** at **École Nationale des Ponts et Chaussées (ENPC)**  
Interested in **Quant Research** and **AI / Machine Learning Research** .

- 📍 Paris, France  
- 🧠 Focus: **Machine Learning**, **Statistics & Probability**, **Optimization**, **Software Engineering**, **Quant Finance**

---

## Technical Skills

| Category | Description |
|-----------|-------------|
| **Programming** | **Python**, **C++**, **SQL** |
| **ML / DL** | Coursework in **Machine Learning**, **Deep Learning**, **Computer Vision** and **Statistics**. Comfortable building end-to-end experiments in Python using **pandas**, **PyTorch**, and **scikit-learn**. |
| **Quant / Markets** | **Statistics & Probability**, **Stochastic Calculus & Financial Mathematics**. |
| **Tools** | Git, LaTeX |

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,latex&perline=5" height="48" alt="skills"/>
</p>

---

## Education

**École Nationale des Ponts et Chaussées (ENPC)**  
Major: *Applied Mathematics & Computer Science*

**Main coursework:**  
Machine Learning, Deep Learning, Advanced Programming (Python, C++), Stochastic calculus & Financial Mathematics, Statistics & Probability, Convex Optimization, Computer Vision

---

## Experience

**Quantitative Analyst Intern** — *Jul. 2026 – Dec. 2026*  
*Crédit Agricole CIB (CACIB), Global Markets* · New York, NY  
- Built Monte Carlo simulations and numerical methods to model cash flows for ABS/MBS securitization structures
- Developed loss models and statistical risk exposure quantification for internal credit rating processes using Python
- Collaborated with structurers and risk managers to deliver quantitative outputs on live securitization deals

**Deep Learning Reconstruction & Forecasting of Meteorological Fields** — *Jan. 2026 – Jun. 2026*  
*Research project supervised at CEREA – École des Ponts / EDF R&D*  
- Designed U-Net++ (PyTorch) for sparse-to-dense atmospheric reconstruction; 0.278 NRMSE, −21% vs. CNN
- Implemented push-forward (teacher forcing) for stable 7-day autoregressive weather forecasting
- Built a stochastic interpolant (Schrödinger Bridge) for probabilistic forecasting; −34.8% NRMSE vs. persistence

---

## Activities

**Vice President – TEDx Initiative** — *May 2025 – May 2026*  
*La Tribune des Ponts et Chaussées* · Paris, France  
- Collaborated with a team to organize multi-disciplinary conferences, coordinating logistics, speaker outreach, and communication strategies to bring thought-provoking talks to the engineering student community.

**Vice President, Ponts AI** — *Jun. 2025 – Jun.2026*  
*École des Ponts Artificial Intelligence Club* · Paris, France  
- Active member of the École des Ponts Artificial Intelligence club, participating in technical workshops, coding challenges, and discussions on the latest advances in AI and machine learning.

---

Featured Projects

<table>
<tr>
<td>
🌦️ Deep Learning Reconstruction & Forecasting of Meteorological Fields · GitHub →

Two-stage deep learning pipeline for reconstructing dense atmospheric fields from sparse sensor observations (~10% of grid points) and performing 24h forecasting.

Built a U-Net++ with CBAM attention (StrongUNet) achieving NRMSE 0.278 and ACC 0.871 on ERA5 reanalysis data, outperforming the CNN baseline (Fukami et al., 2021). Implemented probabilistic forecasting via Schrödinger Bridge. Supervised by Sibo Cheng (CEREA – École des Ponts / EDF R&D).

ModelNRMSEvs. CNN baselineStrongUNet (U-Net++ / CBAM)0.278−21%Schrödinger Bridge (probabilistic)—−34.8% vs. persistence

Stack: Python · PyTorch · ERA5 · WeatherBench2

</td>
</tr>
</table>
<table>
<tr>
<td>
📊 Hull & White Stochastic Volatility Model · GitHub →

Full reproduction of Hull & White (1987) — option pricing under stochastic volatility.

Implements Monte Carlo simulation (with antithetic variates) and the analytical series expansion (Eq. 9) for European option pricing when variance follows a geometric Brownian motion. Studies the volatility smile and the impact of vol-of-vol (ξ), correlation (ρ), and maturity (T) on pricing bias.

Key results: reproduces all tables and figures from the paper — bias structure, implied vol smiles/skews, and the Jensen's inequality effect on B-S mispricing.

Stack: Python · NumPy · SciPy · Matplotlib

</td>
</tr>
</table>
<table>
<tr>
<td>
📈 Path-Dependent Volatility Forecasting · GitHub →

Modular Python toolkit implementing the path-dependent volatility model from Guyon & Lekeufack (2023) for VIX forecasting.

Captures the persistent memory structure of implied volatility using Time-Shifted Power-Law (TSPL) kernels, reproducing and extending paper results across multiple indices (S&P 500, NDX, DJI).

ModelRMSER²TSPL (optimized)2.820.87HAR4.340.70Realized Vol (30d)5.300.56


Train: 2000–2018 · Test: 2019–2025 · Benchmark: S&P 500 / VIX



Stack: Python · scipy.optimize · pandas · yfinance · matplotlib

</td>
</tr>
</table>
<table>
<tr>
<td>
🎮 Multiplayer Trading Game · GitHub →

Real-time multiplayer trading simulation built as a software engineering project.

Players join live lobbies to buy and sell virtual assets (oil, gold, electronics) while observing market fluctuations in real time. The system simulates volatility, price movement, and competition between players, offering a simplified yet realistic introduction to trading mechanics.

Stack: Python · JavaScript · WebSockets . HTML/CSS



</td>
</tr>
</table>

## Let's Connect

📩 Email: **omar.toufelaz@enpc.fr**  
💼 LinkedIn: **[linkedin.com/in/omar-toufelaz](https://www.linkedin.com/in/omar-toufelaz/)**  

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:004080,100:001F3F&height=120&section=footer" />
</p>
