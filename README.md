# Radio Channel Labelling for Interference Mitigation

A notebook-based project that tackles **adjacent / nearby channel interference** by **labeling radio channels** in a way that reduces harmful interactions between closely spaced transmissions.

> Core implementation: `notebooks/01_algo_laxman.ipynb`  
> Full report: `docs/radio_labeling_report.pdf`

---

## What problem does this solve?
In dense radio environments, **uncontrolled simultaneous transmissions** can cause interference—especially when two channels are close enough to interact. This project proposes a labeling strategy to help **separate interfering channels** and improve communication reliability. :contentReference[oaicite:3]{index=3}

---

## Key Features
- Interference-aware channel labeling workflow :contentReference[oaicite:4]{index=4}
- Interactive experimentation via Jupyter Notebook :contentReference[oaicite:5]{index=5}
- Detailed methodology & results documented in the PDF report :contentReference[oaicite:6]{index=6}

---

## Repository Structure
```text
.
├── notebooks/
│   └── 01_algo_laxman.ipynb
├── docs/
│   └── radio_labeling_report.pdf
├── assets/
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md


### Installation Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Amr-Belal-77/Radio-Labelling-For-Radio-Station.git
   cd Radio-Labelling-For-Radio-Station

2. **Install:**
   pip install -r requirements.txt
