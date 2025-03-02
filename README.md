# 💉 Covid-19 Vaccine Effectiveness Study  

## 📌 Introduction  

This project analyzes the **effectiveness** of several **Covid-19 vaccines** based on **clinical trial data** from the **European Medicines Agency (EMA)**. We evaluate the following vaccines:  

- **Comirnaty**  
- **Nuvaxovid**  
- **Ronapreve**  
- **Xevudy**  
- **Spikevax**  

Our study compares **clinical trial results** to assess vaccine effectiveness in **real-world conditions**, distinguishing it from **efficacy**, which is measured under controlled trial settings.  

---

## 🏥 Understanding Effectiveness  

In medicine:  
- **Effectiveness** measures how well a vaccine works in real-world settings (pragmatic trials).  
- **Efficacy** measures its performance under **ideal, controlled conditions** (clinical trials).  

We compute effectiveness using the following formula:  

\[
\text{Effectiveness} = \frac{\Theta_{\text{Placebo}} - \Theta_{\text{Vaccine}}}{\Theta_{\text{Placebo}}} \times 100
\]

where:  
- **\(\Theta_{\text{Placebo}}\)** = Outcome rate in the placebo group  
- **\(\Theta_{\text{Vaccine}}\)** = Outcome rate in the vaccinated group  

This percentage represents the vaccine's performance in real-world conditions compared to a placebo group.  



