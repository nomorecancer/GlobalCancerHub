# NoMoreCancer (GlobalCancerHub) 🎗️
**Real-time Global Cancer Treatment Aggregator**

NoMoreCancer is an open-source, non-profit platform designed to bridge the gap between cutting-edge oncology research and patients in need. We aggregate verified data from top-tier oncology centers, daily research updates from FDA/EMA/PubMed, and simplify complex medical breakthroughs using AI.

---

## 🌍 The Problem
When facing a cancer diagnosis, patients and families often find themselves lost in a sea of outdated articles, conflicting forum advice, and regional data silos. Modern oncology moves faster than most platforms can keep up with — breakthroughs in immunotherapy, target therapy, and clinical trials happen weekly, but they are scattered across thousands of sources.

## 💡 Our Solution
**NoMoreCancer** acts as a "Single Source of Truth" by:
1. **Automated Clinic Verification:** Using Python-based crawlers to track the world's top 250+ oncology centers (Newsweek World's Best Hospitals) and verifying their services via direct LLM-powered outreach.
2. **Dynamic News Hub:** Aggregating clinical trial results and drug approvals from FDA, EMA, and PubMed in real-time.
3. **Multi-Language Accessibility:** Supporting 11 languages to ensure that life-saving information is accessible regardless of geography.
4. **Patient-First Summaries:** Using AI to translate scientific jargon into "What this means for the patient" insights.

---

## 🛠 Tech Stack
- **Frontend:** Vanilla JS, HTML5, CSS3 (Modern mesh-gradient UI).
- **Database-as-a-Service:** [Supabase](https://supabase.com/) (PostgreSQL with Row-Level Security).
- **Backend:** Python (Parsers: `httpx`, `BeautifulSoup`, `feedparser`).
- **Automation:** GitHub Actions (Scheduled data updates).
- **Localization:** i18next logic for 11 languages.

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+
- A Supabase account

### Backend Setup
1. Clone the repository.
2. Navigate to `/backend`:
   ```bash
   pip install -r requirements.txt
