# "The *Khvarenah*-Mandate Model: A History of Degradation in Chinese Political Legitimacy Technology (From Huo Guang to Wang Mang)"

**— A Comparative Political Theology Study based on the Functional Equivalence of Zoroastrian *Farr* and Chinese *Tianming***

*Author: Cao, Xiaopin (Independent Researcher, 2025)*

---

## I. Core Model Framework (Five Stages of Evolution)

This paper introduces a structural-functional model using the Zoroastrian concept of ***Khvarenah*** (Farr, or "Divine Glory") as an **ideal type** to analyze the cyclical nature and functional breakdown of the Chinese ***Tianming*** (Mandate of Heaven). The study maps the system's "Legitimacy Technology Degradation" through five stages, marked by the systematic decline in the "Arbitrator Group's" (literati/officialdom) credibility.

| Stage | Timeframe | Arbitrator Credibility | Transfer Mode | Key Events | Auspice Density |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Stage 1: Procedure Initiation** | 134 BCE | High | Calamity + Court Deliberation | Dong Zhongshu's Three Memorials | Low |
| **Stage 2: Procedure vs. Substance** | 74–25 BCE | Mid→Low | Joint Deposition + Abdication | Deposing Liu He → Wang Mang's Usurpation | High |
| **Stage 3: Mechanism Degradation** | 196–306 CE | Low→Bankrupt | Coercion + Violent Abdication | Cao Cao → Cao Mao's Death → Eight Princes Rebellion | Extremely High |
| **Stage 4: Restoration 1.0** | 618–907 CE | Mid | Civil Service Exam + Military Dual Track | Tang Exam Expansion + Hu Generals | Sharp Decline |
| **Stage 5: Restoration 2.0** | 960–1279 CE | High | Literati Co-governance | Song Dynasty Censorial System + Civil Service Exam | Extremely Low |

> **Core Algorithm**:
> $$\text{Mandate Legitimacy} = \text{Procedural Legitimacy (Deliberation/Omens)} \times \text{Substantive Capacity (Military Strength)} \times \text{Arbitrator Credibility (Literati)}$$

---

## II. Key Event Chain and Model Interpretation

| Item | Event | Model Interpretation | Source |
| :--- | :--- | :--- | :--- |
| **1.** | **Deposing Liu He and Establishing Emperor Xuan (74 BCE)** | **Arbitrator Neutrality & Procedural Execution.** The procedure (584 officials' joint action) successfully constrained the monarch, but the dominance of the chief arbitrator (Huo Guang) exposed the risk of **procedural capture by military power**. | *Han Shu* (Biography of Huo Guang) |
| **2.** | **Emperor Xuan's Purge of the Huo Family (68–66 BCE)** | **Counter-Purge by the *Khvarenah* Holder.** The Emperor utilized his supreme legitimacy to dismantle the Arbitrator leader's power monopoly, ensuring the **independence of the Mandate's interpretive authority** from any single family. | *Han Shu* (Biography of Huo Guang, Annals of Emperor Xuan) |
| **3.** | **Wang Mang's Abdication (9–25 CE)** | **Formal Procedural Collapse.** The procedure (Nine Grants/Omens) became entirely forgeable, demonstrating that **formality can be manufactured, but genuine popular will (*Minyi*) is irreversible**. | *Han Shu* (Biography of Wang Mang) |
| **4.** | **Cao Cao's Coercion of the Emperor (196–220 CE)** | **Era of Manufactured Glory.** The role of the **Court Deliberation (Arbitrator)** degraded into a **tool for military strongmen**. | *San Guo Zhi* (Annals of Emperor Wu) |
| **5.** | **Cao Mao's Charge (260 CE)** | **The Emperor's Complete Secularization.** The monarch was essentially stripped of his *Khvarenah* and reduced to a mere mortal. | *Jin Shu* (Annals of Emperor Hui) |
| **6.** | **Eight Princes Rebellion (291–306 CE)** | **Fragmentation of Divine Glory.** Princes frequently deposed emperors, rendering the Court Deliberation meaningless. **Arbitrator Credibility reached zero**. | *Jin Shu* (Treatise of the Five Elements) |
| **7.** | **Five Barbarians Uprising (304–439 CE)** | **Legitimacy Vacuum.** Non-Han groups seized the *Khvarenah* based purely on **military strength and conquest**. | *Jin Shu* |

---

## III. Empirical Verification: Auspice Density (A Credibility Gauge)

The model is empirically supported by the inverse correlation between the **Annual Density of Auspices** and the **Arbitrator Credibility**. High density indicates systemic over-reliance on manufactured signs to compensate for legitimacy deficits.

### 3.1 Historical Distribution of Auspice Density (Empirical Data)

| Dynasty | Time Span | Total Auspices | Annual Density (Items/Year) | Model Prediction |
| :--- | :--- | :--- | :--- | :--- |
| Western Han | 202 BCE – 8 CE (195 yrs) | 127 | 0.65 | Procedure Initiation |
| Eastern Han | 25–220 CE (196 yrs) | 312 | **1.59** | Credit Decline |
| Wei | 220–265 CE (46 yrs) | 89 | **1.93** | Manufactured Glory |
| Western Jin | 265–316 CE (52 yrs) | 156 | **3.00** | **Pre-Credit Bankruptcy Frenzy** |
| Eastern Jin | 317–420 CE (104 yrs) | 94 | 0.90 | Transition Period |
| Tang | 618–907 CE (290 yrs) | 183 | 0.63 | Military Replacement |
| Northern Song | 960–1127 CE (168 yrs) | 41 | **0.24** | **Credit Restructuring Completed** |

> **Data Source**: Treatises of the Five Elements/Auspices in *Han Shu*, *Hou Han Shu*, *Jin Shu*, *Song Shu*, *Jiu Tang Shu*, *Song Shi*, retrieved via China's Basic Classics Database.

---

### 3.2 Auspice Density Distribution Curve (Visualization)

*(Note: The `chartjs` block is executable code for visualization tools, which cannot be natively displayed in standard Markdown rendering but is retained here for data integrity.)*

```chartjs
{
  "type": "line",
  "data": {
    "labels": ["Western Han", "Eastern Han", "Wei", "Western Jin", "Eastern Jin", "Tang", "Northern Song"],
    "datasets": [{
      "label": "Annual Auspice Density (Items/Year)",
      "data": [0.65, 1.59, 1.93, 3.00, 0.90, 0.63, 0.24],
      "borderColor": "#d4380d",
      "backgroundColor": "rgba(244, 63, 0, 0.2)",
      "fill": true,
      "tension": 0.4
    }]
  },
  
  "options": {
    "plugins": {
      "title": { "display": true, "text": "Auspice Density: Inverse Curve of Arbitrator Credibility" },
      "annotation": {
        "annotations": {
          "peak": {
            "type": "label",
            "xValue": "Western Jin",
            "yValue": 3.00,
            "content": ["Credit Bankruptcy", "3.00/yr"],
            "backgroundColor": "rgba(255,0,0,0.8)"
          }
        }
      }
    },
    "scales": {
      "y": { "beginAtZero": true, "title": { "display": true, "text": "Auspice Density (Items/Year)" } },
      "x": { "title": { "display": true, "text": "Dynasty" } }
    }
  }
}