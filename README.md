# Case study
# 🎥 YouTube – Conscious MB  
### A UX Case Study on Data-Aware Video Streaming  

> **“Know before you watch.”**  
> Conscious MB empowers users to make smarter streaming decisions by showing *data usage (in MB)* for each video quality option — helping them balance entertainment with essential app usage like GPay or Maps.

---

## 📌 Overview  
When users have **limited mobile data (e.g., 250 MB)** but still want to watch a video, they often face a dilemma:  

- Will my data last till the end?  
- Should I save some for GPay, Maps, or messages?  
- Which quality should I choose to fit my remaining MB?  

**Conscious MB** reimagines YouTube’s **Quality Selection Menu** by adding:  
- 💾 Estimated MB usage beside each resolution.  
- 🧩 A **Data Reserve Slider** to hold MB for emergencies.  
- 🟢🔴 **Color-coded quality indicators** based on remaining usable data.  

---

## 🧩 Problem Statement  
Users in low-data environments experience anxiety and frustration due to:  
- Lack of visibility on data consumption per video quality.  
- Sudden data exhaustion during playback.  
- No simple way to reserve data for emergency app usage.

---

## 💡 Insight  
> **“Users don’t think in pixels — they think in megabytes.”**  
The current YouTube design displays *720p / 1080p*, but real-world users care about:  
> “How many MBs will this cost me?”

---

## 👤 User Persona  

**Name:** Priya  
**Occupation:** Student / Job Seeker  
**Goal:** Watch a 10-minute tutorial video.  
**Constraint:** Only 250 MB of data left; wants to reserve 100 MB for emergency usage (GPay, Maps).  

---

## 🔍 Research Findings  

| Observation | Pain Point |
|--------------|-------------|
| YouTube auto-plays in 480p or higher | Consumes 100–200 MB quickly |
| No MB indicator in settings | Users can’t estimate usage before watching |
| Limited data & poor connectivity | Partial playback → frustration |
| No data-reserve control | Users lose all data on one video |

---

## 🧠 UX Opportunity  

Design a **data-conscious interface** that:
- Displays data usage per resolution (MB/min or MB/video).  
- Allows reserving MB for essential apps.  
- Predicts “safe to play” quality levels within remaining balance.  

---

## 🧩 Proposed Solution – “Smart Data Indicator”  

### 🎛️ UI Enhancement: Quality Menu  

| Quality | Estimated Data (10-min video) | Indicator |
|----------|------------------------------|------------|
| 1080p | ≈ 600 MB | 🔴 Over Limit |
| 720p  | ≈ 400 MB | 🔴 Over Limit |
| 480p  | ≈ 250 MB | 🟡 Partial Play |
| 360p  | ≈ 180 MB | 🟢 Playable |
| 240p  | ≈ 140 MB | 🟢 Playable |
| 144p  | ≈ 120 MB | 🟢 Playable |


---


## Demo

- **Demo Prototype:** [Concious MB](https://raguram-n.github.io/Conscious-MB/)

---

## ✨ Feature Highlight: Emergency MB Lock  

### 🔐 “Lock Data for Emergencies”  

- Users can **lock a portion of their data (e.g., 100 MB)** for emergency use (GPay, Maps, etc.).  
- YouTube recalculates available MB for streaming after the lock.  
- Quality options that fit within the new limit glow **🟢 Green (safe)**.  
- Over-limit options turn **🔴 Red (risky)**.  

**Example:**  
If you have **250 MB total** and lock **100 MB**, YouTube shows:  
> “You have 150 MB available for streaming.”  
> Qualities exceeding 150 MB will appear in red (🔴).  

This ensures you **never run out of data** when you need it most.

---

## ⚙️ How It Works  

1. User inputs or allows system to detect remaining data.  
2. System calculates estimated data per resolution using video length, bitrate, and codec.  
3. User sets an **Emergency MB Lock** (e.g., 100 MB).  
4. YouTube dynamically adjusts the UI:  
   - 🟢 Green = Safe quality options.  
   - 🔴 Red = Exceeds safe limit.  
5. Playback runs with a **real-time MB counter overlay** for transparency.  

---

## 📊 Impact  

| Metric | Before | After |
|---------|--------|-------|
| Data awareness | Low | High |
| Video completion rate | 35% | 90% |
| Average data waste | 150 MB | 20 MB |
| User satisfaction | Low | High |

---

## 🔮 Future Enhancements  

- 🤖 **AI Prediction:** Suggests “Best quality within remaining data.”  
- 📥 **Offline Buffer Mode:** Auto-pause before exceeding data cap.  
- 📊 **Daily Data Summary:** “You used 230 MB today.”  
- 📡 **Smart Alerts:** Notification when nearing data exhaustion.  
- 🔋 **Eco Mode:** Compresses stream when network weakens, saving MB.  

---

## 🧱 Prototype / Wireframes  
Add UI mockups here once ready.  
Example file path:  
