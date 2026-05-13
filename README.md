# 🎬 Amazon Prime Video: Content Strategy & Market Analysis

## 📌 Project Overview
This project performs a comprehensive end-to-end Exploratory Data Analysis (EDA) on the Amazon Prime Video library, consisting of **9,668 titles**. The analysis moves beyond basic visualization to uncover deep business patterns in content acquisition, audience targeting, and regional growth.

---

## 📂 Project Structure

| Folder/File | Description |
| :--- | :--- |
| **data/** | Raw OTT Dataset (CSV) |
| **notebooks/** | Structured Analysis Colab Notebook |
| **outputs/** | Generated Analysis Charts (PNG) |
| **README.md** | Professional Documentation |

---

## 📊 Dataset Used

| Dataset | Source | Records |
| :--- | :--- | :--- |
| Amazon Prime Video Titles | Kaggle / Prime Video | 9,668 rows, 12 features |

### **Key Features Analyzed:**

| Feature | Description |
| :--- | :--- |
| **Type** | Classification of content (Movie vs TV Show) |
| **Release Year** | Original year of release |
| **Rating** | Target audience age group (13+, 18+, etc.) |
| **Duration** | Runtime in minutes or season count |
| **Listed In** | Genre categories |

---

## 🔍 Key EDA Findings

### 1. Movie Dominance vs. TV Series
Amazon Prime is heavily **Movie-centric (80.82%)**. While this makes it a top destination for cinema lovers, it faces a **higher churn risk** compared to platforms with a higher percentage of episodic TV shows that drive daily user habits.

### 2. The "90-Minute" Sweet Spot
The average movie runtime on the platform is **91.31 minutes**. This indicates a strategy focused on "high-engagement, low-time-commitment" content, which is ideal for casual viewers.

### 3. Audience Targeting (The 13+ Factor)
The most frequent rating on the platform is **13+**, followed by **18+**. This confirms that Amazon is targeting the **Young Adult & Teen** segments.

### 4. Legacy Content & Library Depth
A significant portion of the library consists of "Old Gold" (legacy titles). While new releases create hype, the deep back-catalog is what keeps the platform's volume high and provides value for a wide age range of subscribers.

### 5. Geographical Content Hubs
After cleaning the data, the United States and India emerge as the top content contributors. This highlights Amazon's focus on Western cinema and the rapidly growing Indian digital market.

---

## 🚀 Business Recommendations

### 🟢 Subscriber Retention
Increase TV Show Acquisitions: To improve daily active users (DAU), Amazon should pivot towards more multi-season episodic content.

Invest in Renewals: Focus on renewing successful "Season 1" shows to build long-term franchises.

### 🔵 Market Expansion
Hyper-Local Content: Acquire more local-language content in underserved regions (LatAm, SE Asia) where growth is peaking.

Monthly "Tentpole" Drops: Spread big-budget releases across the "low-upload" months identified in the Monthly Trends analysis.

### 🟠 User Experience
Niche Genre Promotion: Promote high-quality niche genres (Documentaries, International) that currently have low volume but high average ratings.

---

## 🛠️ Tools Used

| Tool | Purpose |
| :--- | :--- |
| **Python** | Core data processing and cleaning |
| **Pandas** | Data manipulation and feature engineering |
| **Matplotlib** | Static data visualizations |
| **Seaborn** | Advanced statistical charts |
| **Google Colab** | Cloud development environment |

---

## 💡 Key Takeaways
- Movies are the anchor, but TV shows are the "hook" for retention.

- 91 minutes is the ideal duration for high-engagement cinematic content.

- United States and India are the primary growth engines for Prime Video content.

- Infrastructure in data cleaning (handling 'Unknown' values) is crucial for accurate business reporting.

---

## 📁 Author

**Ishika Khapekar** 
