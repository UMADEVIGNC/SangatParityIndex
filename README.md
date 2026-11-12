# Sangat Parity Index (SPI)

An open-source, interactive diagnostic research tool operationalizing 15th-century Sikh egalitarian philosophy into a quantitative metric for evaluating institutional gender parity.

Developed for submission to the **Guru Shiksha (11th Edition) Competition**.

---

## 1. Mathematical Formulation

The **Sangat Parity Index (SPPI)** is defined as a tripartite composite index:

$$\text{SPPI} = \frac{1}{3}\mathcal{S}_{\text{gov}} + \frac{1}{3}\mathcal{P}_{\text{dist}} + \frac{1}{3}\mathcal{K}_{\text{econ}}$$

Where:
- **$\mathcal{S}_{\text{gov}}$ (Sangat Governance Parity):** Measures deliberative consensus voice ($V_d$) and board representation ($L_p$). Grounded in *Asa Ki Var* (Ang 473).
- **$\mathcal{P}_{\text{dist}}$ (Pangat Distributive Equity):** Evaluates non-discriminatory commons/STEM access ($C_a$) and elimination of bodily taboos ($W_b$). Grounded in the deconstruction of *Sutak* (Ang 472).
- **$\mathcal{K}_{\text{econ}}$ (Kirat-Vand Economic Autonomy):** Measures asset/equity entitlement ($A_p$) and the economic valuation of unpaid domestic care ($U_c$). Grounded in *Kirat Karo & Vand Chhako*.

---

## 2. GitHub Pages Deployment (2-Step Setup)

1. **Create Repository:** Create a new GitHub repository named `sppi-gender-parity`.
2. **Push Files:** Commit `index.html` and `README.md` to the `main` branch.
3. **Enable GitHub Pages:**
   - Go to **Settings** &rarr; **Pages**.
   - Under **Build and deployment**, select **Source: Deploy from a branch**.
   - Select branch: `main` and folder: `/ (root)`.
   - Click **Save**.
4. Your interactive tool will be live at:
   `https://<your-username>.github.io/sppi-gender-parity/`

---

## 3. Academic Citation

```bibtex
@misc{sppi2026,
  author = {Dr.K.Umadevi, Guru Nanak College},
  title = {Sangat  Parity Index (SPI): An Operational Metric for Institutional Gender Equity Inspired by Guru Nanak's Philosophy},
  year = {2026},
  howpublished = {Interactive Research Artifact on GitHub Pages},
  note = {Version 1.0}
}
```
