# 🚀 Quick Start Guide

## Installation & Setup (2 minutes)

### 1. Install Dependencies
```bash
pip install streamlit
```

### 2. Run the Application
```bash
streamlit run main.py
```

The app will open automatically at `http://localhost:8501`

## What This System Does
- Records your decisions **with full context**
- Remembers **why** you chose something, not just **what** you chose
- Provides AI suggestions based on past decisions
- Shows how your decisions evolve over time
- Helps AI provide smarter, context-aware assistance

## 📋 First Decision (5 Steps)

### Step 1: Go to "New Decision"
Click the **"New Decision"** button in the sidebar

### Step 2: Fill the Form
1. **Decision Title** (e.g., "Choosing a career path")
2. **Description** (Details about your situation)
3. **Your Goal** (What do you want to achieve?)
4. **Select Constraints** (Time, Cost, Risk, Stress levels)
5. **Choose Alternatives** (What options are you considering?)

### Step 3: Get AI Analysis
The system automatically shows:
- ✅ **Recommended Choice** (based on your constraints)
- 💬 **Why** (reasoning behind the recommendation)
- ❓ **Why not others** (why other options don't fit)

### Step 4: Add Personal Notes
What else do you want to remember about this decision?

### Step 5: Save
- ✅ Check: **"I consent to save this decision context"**
- Click: **"💾 Save Decision"**

## ❓ Ask Another Question (3 Steps)

### Step 1: Click "❓ Ask Another Question"
After saving, you'll see a success screen with a button to ask another question

### Step 2: System Detects Similarity
If your new question is similar to a past one:
```
🔍 We found similar decision(s) you made before!
[Most Recent] [Previous Choice] [Total Similar]
```

### Step 3: Open Continuity Recall
Click **"📖 Open Continuity Recall"** to:
- See your previous decision & reasoning
- Confirm if constraints/goals have changed
- Get AI recomputation based on current state
- Save the updated decision

## 🎯 Key Workflow

```
┌─────────────────────┐
│  Start: New Query   │
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Fill Decision Form  │ ← Decision title, goal, constraints, options
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  AI Analysis        │ ← Get recommendation & reasoning
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Save Decision      │ ← Add notes, consent, save
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│  Success Screen     │ ← Choose: Ask Another / View Timeline
└──────────┬──────────┘
           │
      ┌────┴────┐
      │          │
      ▼          ▼
  Continue   Review
  Asking     Timeline
```

## 🔄 When AI Reminds You of Past Decisions

### Scenario 1: Same Situation
```
Your Previous Decision (Jan 2025):
- Goal: Stable job quickly
- Time: Low (< 1 month)
- Choice: Vocational training

Your New Query (Today):
- Same description
- System detects: SIMILAR
- AI Shows: "✅ Same Recommendation: Vocational"
- Result: Same choice still optimal
```

### Scenario 2: Situation Changed
```
Your Previous Decision (Jan 2025):
- Time Constraint: Low (< 1 month)
- Choice: Vocational training

Your New Query (Today):
- Time Constraint: Changed to High (> 6 months)
- AI Recomputes: "⚠️ New Recommendation: Science"
- Shows: Why time change means different path
- Result: Better choice for your new timeline
```

## 📊 5 Pages to Explore

### 1️⃣ Home
- Dashboard with decision statistics
- Quick access to recent decisions
- System overview

### 2️⃣ New Decision
- Create new decisions
- Experience continuity recall
- Get AI analysis
- Multi-question sessions

### 3️⃣ Memory Timeline
- See all your decisions
- Sort by date (newest first)
- Edit any decision
- Delete if needed
- View decision connections

### 4️⃣ Analysis
- See patterns in your decisions
- Constraint frequency charts
- Choice distribution
- Export your data

### 5️⃣ Settings
- Download backup (JSON)
- Delete all data
- Privacy information
- System details

## 💾 Important: Saving Your Data

### Backups
Go to **Settings** and click:
- **📥 Download All Data (JSON)** - Full backup
- **📊 Download as CSV** - Spreadsheet format

### Recovery
Keep your JSON backup safe. You can:
- Import into another system
- Share with trusted people
- Archive for future reference

## 🎓 Pro Tips

### Tip 1: Be Specific
Write detailed descriptions so AI can find similar decisions later

### Tip 2: Document Changes
When revisiting decisions, note what changed in your notes

### Tip 3: Link Decisions
Click **"🔗 Link to Previous Decision"** to show decision relationships

### Tip 4: Review Timeline Regularly
Check your Memory Timeline to understand your decision patterns

### Tip 5: Export Data
Regularly export your data as backup in Settings

## ❓ Common Questions

**Q: Will AI make decisions for me?**
A: No! AI assists, you decide. AI only recommends based on constraints you provide.

**Q: Will my old decisions change?**
A: No. Past decisions stay the same. New queries create new linked entries.

**Q: Is my data private?**
A: Yes! Data stays on your device. No cloud sync. You control everything.

**Q: Can I change my mind?**
A: Yes. Go to Memory Timeline and click "✏️ Edit" or "🗑️ Delete"

**Q: What if I have many similar decisions?**
A: System shows all of them chronologically, focusing on the most recent.

**Q: Can I share my decisions?**
A: Currently private-only. Future versions may add optional sharing.

## 🚀 Your First 10 Minutes

```
⏱️ Timeline:
0:00 - 1:00  | Go to "New Decision" page
1:00 - 3:00  | Fill decision form (title, goal, constraints, options)
3:00 - 4:00  | Review AI recommendation
4:00 - 5:00  | Add personal notes
5:00 - 6:00  | Save decision with consent
6:00 - 7:00  | See success screen
7:00 - 8:00  | Click "❓ Ask Another Question"
8:00 - 9:00  | Fill second decision (system may detect similarity)
9:00 - 10:00 | Save second decision, view timeline
```

## 📞 Need Help?

Check these documentation files:
- `FEATURE_SUMMARY.md` - Complete features overview
- `CONTINUITY_FEATURE.md` - Detailed continuity recall guide
- `NEW_QUERY_GUIDE.md` - Multi-question workflow

## 🎯 Next Steps

1. ✅ Create your first decision
2. ✅ Ask a follow-up question
3. ✅ Review in Memory Timeline
4. ✅ Check patterns in Analysis
5. ✅ Export and backup your data

---

**Ready to remember your decisions better?**

Go to **"New Decision"** and start! 🚀
