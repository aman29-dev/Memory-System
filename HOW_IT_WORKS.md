# 📖 HOW IT WORKS: Complete User Guide

**Step-by-Step Walkthrough of All Features**

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [Recording Decisions](#recording-decisions)
3. [Viewing Your Timeline](#viewing-your-timeline)
4. [Getting AI Suggestions](#getting-ai-suggestions)
5. [Advanced Features](#advanced-features)
6. [Understanding the AI](#understanding-the-ai)
7. [Best Practices](#best-practices)
8. [FAQ](#faq)

---

## Getting Started

### Installation (First Time Only)

```bash
# Step 1: Navigate to project directory
cd chai-streamlit

# Step 2: Create virtual environment (Python 3.8+)
python -m venv .venv

# Step 3: Activate virtual environment
# On Windows:
.\.venv\Scripts\activate
# On Mac/Linux:
source .venv/bin/activate

# Step 4: Install dependencies
pip install -r requirements.txt

# Step 5: Launch the app
streamlit run main.py
```

**What happens next:**
- Browser opens to `http://localhost:8504`
- You see the home page with welcome message
- You're ready to record your first decision!

### Home Page Overview

```
┌────────────────────────────────────────┐
│  🧠 Human-AI Memory Continuity System  │
├────────────────────────────────────────┤
│  📊 METRICS:                           │
│  • Total Decisions: 0                  │
│  • Private Decisions: 0                │
│  • Shareable Decisions: 0              │
│  • Memory Integrity: 100%              │
├────────────────────────────────────────┤
│  🔘 QUICK ACTIONS:                     │
│  [ 📝 Record New ]                     │
│  [ 📚 View Timeline ]                  │
│  [ 🤖 Get AI Insights ]                │
│  [ 📊 View Analytics ]                 │
├────────────────────────────────────────┤
│  📌 Recent Decisions: (None yet)       │
└────────────────────────────────────────┘
```

---

## Recording Decisions

### When to Record a Decision

Record a decision when you:
- ✅ Make an important life choice
- ✅ Choose between alternatives
- ✅ Face significant constraints
- ✅ Want to remember your reasoning
- ✅ Need AI to learn your patterns

**Examples:**
- "Choosing which job offer to accept"
- "Deciding to learn Python"
- "Picking tech stack for new project"
- "Career path decision"

### Step 1: Navigate to Record

Click **"📝 Record Decision"** from home page or sidebar

### Step 2: Fill Decision Summary

```
┌─ Decision Title ─────────────────────────────┐
│ "Choose a language to learn"                 │
└──────────────────────────────────────────────┘

┌─ Decision Description ───────────────────────┐
│ "I want to learn a programming language for  │
│  developing my technical skills"             │
└──────────────────────────────────────────────┘
```

**Tips:**
- Be specific in title (not just "Job decision")
- Describe WHAT decision you're making
- 2-3 sentences is plenty

### Step 3: Define Your Goal

```
┌─ Your Goal or Intention ─────────────────────┐
│ "To get a job and improve my career         │
│  prospects by learning in-demand skills"     │
└──────────────────────────────────────────────┘
```

**Why this matters for AI:**
- Goal helps AI understand your priorities
- AI will find similar goals in past decisions
- Used to explain why you chose something

### Step 4: Add Constraints (2-5 typical)

```
┌─ Constraint 1 ──────────────────────────────┐
│ Category:    Time                            │
│ Description: Only 2 months to learn          │
│ Severity:    ○ Low  ○ Medium ● High         │
└──────────────────────────────────────────────┘

┌─ Constraint 2 ──────────────────────────────┐
│ Category:    Cost                            │
│ Description: Budget: $0 (free learning)      │
│ Severity:    ● Low  ○ Medium ○ High         │
└──────────────────────────────────────────────┘
```

**What are Constraints?**
- Limitations on your decision
- Things that reduce your options
- Examples: Time, Money, Skills, Resources, Risk, Emotional factors

**Why constraints matter:**
- AI learns what barriers you typically face
- Helps predict similar situations
- Shows your decision-making style

### Step 5: Document Alternatives

For each alternative you considered:

```
┌─ Alternative 1: Java ────────────────────────┐
│ Pros:                                         │
│  ✓ High demand in market                     │
│  ✓ Strong ecosystem                          │
│                                              │
│ Cons:                                         │
│  ✗ Steep learning curve                      │
│  ✗ More complex than Python                  │
│                                              │
│ Why Rejected:                                │
│ "Too complex for beginner, not enough time"  │
└──────────────────────────────────────────────┘

┌─ Alternative 2: Go ──────────────────────────┐
│ Pros:                                         │
│  ✓ Modern language                           │
│  ✓ Good for system design                    │
│                                              │
│ Cons:                                         │
│  ✗ Smaller community than Python             │
│  ✗ Not beginner-friendly                     │
│                                              │
│ Why Rejected:                                │
│ "Community support for beginners is limited" │
└──────────────────────────────────────────────┘
```

**Why document alternatives?**
- Shows you thought through options
- AI learns your evaluation criteria
- Helps explain past decisions
- Shows decision rigor

### Step 6: State Your Final Choice & Reasoning

```
┌─ What did you choose? ───────────────────────┐
│ "Learn Python"                               │
└──────────────────────────────────────────────┘

┌─ Why did you choose this? ───────────────────┐
│ "Python is easy to learn, has great         │
│  documentation, and I can become job-ready  │
│  in 2 months. Cost is free (tutorials       │
│  online). It's the best balance of all       │
│  constraints."                               │
└──────────────────────────────────────────────┘

┌─ Expected Outcome (optional) ────────────────┐
│ "Become a Python job-ready programmer in     │
│  2 months with solid fundamentals"           │
└──────────────────────────────────────────────┘
```

**Reasoning Guidelines:**
- Explain WHY this choice over alternatives
- Mention how you balanced constraints
- Be honest about reasoning
- Future AI will learn from this

### Step 7: Set Privacy & Consent

```
┌─ Privacy Level ──────────────────────────────┐
│ ○ 🔒 Private (Only visible to you)           │
│ ● 🔓 Shareable (Can be shared with AI)       │
│                                              │
│ What this means:                             │
│ • Private: Only you see. AI cannot access    │
│ • Shareable: AI can use for suggestions      │
│              but won't share with anyone else│
└──────────────────────────────────────────────┘

┌─ Consent ────────────────────────────────────┐
│ ☑ I understand the privacy terms and        │
│   consent to this decision being recorded    │
└──────────────────────────────────────────────┘
```

**Privacy Levels Explained:**

🔒 **PRIVATE**
- When: Personal decisions you want to keep secret
- Who sees: Only you
- AI access: NO - AI cannot learn from this
- Use case: Sensitive personal/financial decisions

🔓 **SHAREABLE**
- When: Decisions you're comfortable AI learning from
- Who sees: Still only stored locally, no sharing
- AI access: YES - AI can use this for suggestions
- Use case: Career, learning, general decisions

### Step 8: Add Tags (Optional but recommended)

```
☑ Career
☐ Project
☑ Technical
☐ Financial
☐ Personal
☑ Academic
☐ Health
☐ Lifestyle
```

**Why tags matter:**
- Helps organize decisions
- AI uses tags for matching
- Makes searching easier
- Shows your decision categories

### Step 9: Submit

Click **"💾 Save Decision"**

**What happens:**
```
✅ Decision recorded successfully! (ID: dec_xxx...)
   🎉 [Balloons animation]

Timeline updates with your new decision
Memory store saves to human_ai_memory.json
```

---

## Viewing Your Timeline

### Access Timeline

Click **"📚 View Timeline"** from home or sidebar

### Timeline Interface

```
┌──────────────────────────────────────────────┐
│ 📚 Decision Timeline                         │
├──────────────────────────────────────────────┤
│ 🔍 Search: [                              ] │
│ Privacy:  [All ▼]  Tag: [All ▼]             │
├──────────────────────────────────────────────┤
│ Showing 1 decision(s)                        │
├──────────────────────────────────────────────┤
│ ┌─ 🔓 Choose a language to learn ──────────┐│
│ │ 📅 2026-01-09 10:28                       ││
│ │ 🎯 Goal: To get a job                     ││
│ │ ✅ Choice: i will learn python            ││
│ │ 🏷️ Personal, Academic                     ││
│ │                                            ││
│ │ Constraints: 1 | Alternatives: 1          ││
│ │                                            ││
│ │ [ 👁️ View ]  [ ✏️ Edit ]  [ 🗑️ Delete ] ││
│ └──────────────────────────────────────────┘│
└──────────────────────────────────────────────┘
```

### Using Filters

**Search Box:**
```
Search by:
• Title (e.g., "Python")
• Goal (e.g., "job")
• Tags (e.g., "Career")
```

**Privacy Filter:**
```
Filter by:
• All (default)
• 🔒 Private only
• 🔓 Shareable only
```

**Tag Filter:**
```
Filter by category:
• All (default)
• Career
• Project
• Technical
• Personal
• Academic
```

### Viewing a Single Decision

Click **"👁️ View"** button

#### Detailed View Layout

```
┌─────────────────────────────────────────────┐
│  🔓 Choose a language to learn              │
├─────────────────────────────────────────────┤
│ Created: 2026-01-09 | Status: Pending       │
│ Privacy: Shareable | Related: 0             │
├─────────────────────────────────────────────┤
│
│ 📖 Overview Tab
│ ├─ Decision Description
│ ├─ Goal
│ ├─ Final Choice
│ └─ Reasoning
│
│ 📊 Analysis Tab
│ ├─ ⚠️ Constraints Faced
│ ├─ 🔄 Alternatives Considered
│ └─ 🤖 AI Decision Analysis
│
│ 🔗 Related Tab
│ ├─ Link with another decision
│ └─ View related decisions
│
│ 💭 Reflection Tab
│ ├─ How did this turn out?
│ └─ Update status
│
│ ⚙️ Actions Tab
│ ├─ ✏️ Edit Decision
│ └─ 🗑️ Delete Decision
│
└─────────────────────────────────────────────┘
```

#### Each Tab Explained

**Overview Tab:**
- 📋 Summary: Description, goal, choice
- 🎯 Reasoning: Why you chose this
- 📊 Expected: What you hoped would happen

**Analysis Tab:**
- ⚠️ Constraints: What limited your options
- 🔄 Alternatives: What else you considered
- 🤖 AI Analysis: AI explanation of decision

**Related Tab:**
- 🔗 Link decisions: Connect related choices
- 📚 See relationships: How decisions relate

**Reflection Tab:**
- 💭 How it turned out: Add outcome reflection
- 📊 Status: Mark as Pending/In Progress/Completed

**Actions Tab:**
- ✏️ Edit: Update decision details
- 🗑️ Delete: Remove decision (with confirmation)

---

## Getting AI Suggestions

### Access AI Insights

Click **"🤖 Get AI Insights"** from home or sidebar

### AI Insights Dashboard

Three tabs: Patterns, Distribution, Suggestions

#### Tab 1: Constraint Patterns

```
┌─────────────────────────────────────────┐
│ 📊 Recurring Constraint Patterns         │
├─────────────────────────────────────────┤
│                                          │
│ Time (Medium): ████████ 5 occurrences   │
│ Cost (High):   ████ 3 occurrences       │
│ Risk (Low):    ██ 2 occurrences         │
│                                          │
│ 💡 AI Insights:                          │
│ Your decisions are shaped by recurring  │
│ constraints. This means:                │
│ • You have consistent priorities        │
│ • Future decisions can learn from       │
│   past trade-offs                       │
│ • Consider building processes to        │
│   address these constraints earlier     │
└─────────────────────────────────────────┘
```

**What this shows:**
- What barriers you typically face
- Which constraints affect you most
- Patterns in your decision-making
- What to plan for proactively

#### Tab 2: Decision Distribution

```
┌─────────────────────────────────────────┐
│ 📈 Decision Distribution                 │
├─────────────────────────────────────────┤
│                                          │
│ Career:     ████ 4 decisions            │
│ Technical:  ██ 2 decisions              │
│ Personal:   ███ 3 decisions             │
│                                          │
│ Quick Stats:                            │
│ • Total Decisions: 9                    │
│ • Avg Constraints/Decision: 2.3         │
│ • Memory Preservation: 100%             │
│                                          │
└─────────────────────────────────────────┘
```

**What this shows:**
- Breakdown of decisions by category
- Your decision frequency
- Average complexity (constraints)
- Complete memory status

#### Tab 3: Get Suggestion

**The Main Feature - How to Use:**

```
Step 1: Describe Your Situation
┌──────────────────────────────────────────────┐
│ What goal or situation are you considering?  │
│                                              │
│ [                                           ]│
│                                              │
│ Example: Choosing between staying in        │
│ current job vs accepting a new offer        │
│                                              │
│ [ 💡 Get AI Suggestion ]                    │
└──────────────────────────────────────────────┘

Step 2: AI Analyzes & Responds
```

### Understanding AI Responses

#### Response Type 1: HIGH MATCH Found

```
✅ AI RECOMMENDATION:
Found Similar Past Decisions!

Based on your 1 past decision, your 
situation is SIMILAR to decisions 
you've made before.

Your Pattern: You've made decisions 
about Personal, Academic.
Your approach typically focuses on 
Time (Medium).

Key Learnings:
1. Previous approach: I will learn python
2. Key constraint: Time (Medium)
3. Your reasoning: Learn something for 
   job readiness

Recommendation: Review the similar 
decisions below. Notice how you've 
handled similar constraints before...

═══════════════════════════════════════

⚠️ CONSTRAINTS FROM YOUR HISTORY:
📌 Time (Medium) (faced 1x)

═══════════════════════════════════════

📚 SIMILAR PAST DECISIONS:

🎯 HIGH MATCH
1. Choose a language to learn
   Goal: To get a job
   ✅ Choice: i will learn python
   💡 Reasoning: Python is easy to learn...
   ⚠️ Constraints: Time: Only 2 months...

═══════════════════════════════════════

💭 PATTERN INSIGHTS:
✓ You have enough decision history. 
  Patterns are emerging.
✓ You tend to face similar constraints - 
  be proactive about them
✓ Link related decisions to understand 
  your evolution
```

**What to do with this:**
1. Read the similar past decision
2. Notice how you handled constraints
3. See your reasoning framework
4. Apply same framework to new situation
5. Make informed choice

#### Response Type 2: NO MATCH Found

```
ℹ️ AI RECOMMENDATION:
No Directly Similar Past Decisions

Your current situation doesn't closely 
match your past decisions, but you can 
still learn from them!

What I can tell you:
- You've made 9 decisions before
- You often face: Time (Medium)

My Suggestions:
1. Review your decision framework - Look 
   at any past decision to see how you've 
   approached constraints
2. Think about your patterns - What factors 
   do you usually prioritize?
3. Document this new decision - Add it to 
   your memory so future decisions can 
   learn from it
4. Trust your judgment - You've made good 
   decisions before; apply that same 
   thinking here

This new decision will help me provide 
better suggestions next time!

═══════════════════════════════════════

⚠️ CONSTRAINTS FROM YOUR HISTORY:
📌 Time (Medium) (faced 5x)
📌 Cost (High) (faced 3x)
📌 Risk (Low) (faced 2x)

═══════════════════════════════════════

💭 PATTERN INSIGHTS:
✓ You have enough decision history. 
  Patterns are emerging.
```

**What to do with this:**
1. Review general past decisions
2. See what constraints you typically face
3. Make decision using your own patterns
4. Record this new decision
5. Help AI learn for next time

#### Response Type 3: NO DECISIONS Yet

```
📝 NO DECISION HISTORY YET

You haven't recorded any decisions yet. 
To get AI suggestions, start by:

1. Record your current situation as a 
   new decision
2. Document the details:
   - Your goal and what you're trying 
     to achieve
   - Constraints you face (time, cost, 
     resources, etc.)
   - Alternatives you're considering
   - Why you choose one option over others

3. Record similar decisions in the future 
   - The more decisions you log, the 
     better my suggestions become!

Start by recording your first decision →
Go back and use "Record Decision" option.
```

---

## Advanced Features

### Feature 1: Linking Decisions

**Why link decisions?**
- See how decisions relate over time
- Track evolution of thinking
- Build decision chains
- Understand dependencies

**How to link:**

```
On a decision detail page:
├─ Go to "🔗 Related" tab
├─ Click "Link with another decision"
├─ Select decision to link with
└─ Click "🔗 Create Link"

Result:
├─ Both decisions show as related
├─ Can navigate between them
└─ Helps AI understand context
```

**Example Chain:**
```
Decision 1: "Choose technology for learning"
    ↓ (leads to)
Decision 2: "Apply for first developer job"
    ↓ (leads to)
Decision 3: "Accept job offer"
    ↓ (leads to)
Decision 4: "Decide whether to specialize"
```

### Feature 2: Reflection & Outcome Tracking

**When to add reflection:**
- After decision outcome is known
- When you learn something
- When things go differently than expected

**How to add reflection:**

```
On decision detail page:
├─ Go to "💭 Reflection" tab
├─ Describe how it turned out
├─ Update outcome status:
│  └─ Pending Review
│  └─ In Progress
│  └─ Completed
│  └─ Reviewing
└─ Click "💾 Save Reflection"
```

**What to write:**
```
"Turned out great! Learned Python in 
6 weeks instead of 2 months. The free 
resources were abundant. Would do the 
same thing again. This time constraint 
(Medium) was actually generous."
```

### Feature 3: Decision Editing

**When to edit:**
- You realize you missed something
- You want to add more detail
- You need to update status

**How to edit:**

```
Timeline view:
└─ Click "✏️ Edit" button

Or from detail view:
└─ Go to "⚙️ Actions" tab
   └─ Click "✏️ Edit Decision"

Edit page allows:
├─ Title, description, goal
├─ Final choice, reasoning
├─ Expected outcome
├─ Privacy level
└─ Tags
```

**What you CAN'T edit:**
- Created date (keeps history)
- Constraints/alternatives (shows original thinking)

### Feature 4: Analytics Dashboard

**Access:**
```
Click "📊 View Analytics" from home
```

**Metrics shown:**
```
📊 SUMMARY STATS
├─ Total Decisions: N
├─ Avg Constraints per Decision: X.X
└─ Avg Alternatives per Decision: Y.Y

📅 TIMELINE
├─ First decision: YYYY-MM-DD
├─ Latest decision: YYYY-MM-DD
└─ Days of history: N

🏷️ CATEGORY BREAKDOWN
├─ Career: N decisions
├─ Technical: N decisions
├─ Personal: N decisions
└─ [Other categories]

🔒 PRIVACY DISTRIBUTION
├─ Private: N decisions
├─ Shareable: N decisions
└─ Shared percentage: X%
```

---

## Understanding the AI

### How AI Scoring Works

**Simple Example:**

```
Your Query: "Need to choose a tech stack"

System evaluates EACH past decision:

Decision: "Choose technology for learning"
├─ Full goal match? 
│  "technology" in both → +100
├─ Word overlap?
│  "choose" matches → +15
├─ Tag overlap?
│  No matching tags → +0
├─ Description keywords?
│  Not present → +0
└─ TOTAL SCORE: 115 → 🎯 HIGH MATCH (>50)

Decision: "Choose where to move"
├─ Full goal match? No → +0
├─ Word overlap?
│  "choose" matches → +15
├─ Tag overlap? No → +0
├─ Description keywords? No → +0
└─ TOTAL SCORE: 15 → 📌 RELATED (<50)

Decision: "Plan vacation"
├─ Full goal match? No → +0
├─ Word overlap? No → +0
├─ Tag overlap? No → +0
├─ Description keywords? No → +0
└─ TOTAL SCORE: 0 → ❌ NO MATCH
```

### Relevance Score Ranges

```
🎯 Score > 50:   HIGH MATCH
   └─ Highly relevant past decision
   └─ Shows prominently
   └─ AI confident in suggestion

📌 Score 10-50:  RELATED EXPERIENCE
   └─ Somewhat relevant
   └─ Still useful insight
   └─ Apply with judgment

❌ Score < 10:   NO MATCH
   └─ Not relevant
   └─ Won't appear
   └─ Prevents noise
```

### What AI Can & Can't Do

#### ✅ AI CAN:
- Find your similar past decisions
- Show you how you've handled constraints
- Explain your reasoning patterns
- Identify recurring barriers
- Suggest frameworks based on past choices

#### ❌ AI CAN'T:
- Make decisions FOR you
- Predict the future with certainty
- Understand context beyond what you document
- Learn from decisions marked "Private"
- Access information you haven't recorded

---

## Best Practices

### Practice 1: Be Detailed

```
❌ Poor: "Got a new job"

✅ Good: "Accepted job offer for Senior 
Developer role at TechCorp. Key 
constraints: 30% pay cut but better 
work-life balance. Alternatives were: 
stay at current job (good pay but 
stressful) or freelance (risky). 
Chose new job because..."
```

**Why:** More detail helps AI match better

### Practice 2: Always Document Reasoning

```
❌ Poor: 
Reasoning: "Seemed good"

✅ Good:
Reasoning: "Python offers:
• Easiest learning curve (2 month constraint)
• Largest beginner community (good support)
• High job market demand (career goal)
• Free resources available (cost constraint)

Other options didn't meet all criteria.
Python is best balance for my situation."
```

**Why:** AI learns your decision framework

### Practice 3: Update Decisions After Outcomes

```
Don't:
├─ Record decision
└─ Never touch it again

Do:
├─ Record decision
├─ Later: Add reflection on how it went
├─ Update outcome status
└─ AI learns from results
```

### Practice 4: Use Tags Consistently

```
Use same tags each time:
✅ "Career" not "career" or "Job"
✅ "Technical" not "Tech" or "Engineering"

Why:
├─ AI matches on tags
├─ Helps you organize better
└─ Makes searching easier
```

### Practice 5: Link Related Decisions

```
Example chain:
Decision 1: "Choose career field"
   ↓ (linked to)
Decision 2: "Choose technology to learn"
   ↓ (linked to)
Decision 3: "Accept job in field"
   ↓ (linked to)
Decision 4: "Decide on specialization"

Benefits:
├─ See decision evolution
├─ Understand dependencies
├─ Build decision narrative
└─ Help AI understand context
```

### Practice 6: Record Constraints Honestly

```
Don't hide constraints:
✅ Include emotional constraints
✅ Include family considerations  
✅ Include personal values
✅ Include uncertain factors

Why:
├─ AI learns your real priorities
├─ Creates realistic suggestions
├─ Explains your pattern
└─ No judgment - it's your system
```

---

## FAQ

### Q1: How do I know if the AI suggestion is good?

**A:** The AI suggests, YOU decide.

The AI is showing you:
1. Similar past decisions you've made
2. How you handled constraints before
3. Patterns in your approach

You should:
1. Review the past decision
2. Notice similarities and differences
3. Use it to inform your thinking
4. Make your own judgment
5. Trust your human judgment above all

**Remember:** AI is not oracle. It's a mirror of your patterns.

### Q2: Can I delete a decision?

**A:** Yes, but be careful!

```
Timeline or Detail page:
└─ 🗑️ Delete button
   └─ Confirmation required
   └─ Cannot be undone
```

**Should you delete?**
- ✅ Yes: Recorded wrong decision by mistake
- ✅ Yes: Personal decision you want removed
- ❌ No: Decision you regret (keep it - for learning)
- ❌ No: Want to start fresh (use new tags instead)

### Q3: What if I have many decisions?

**A:** Use filters and search!

```
Timeline has:
├─ 🔍 Search box
├─ Privacy filter (All/Private/Shareable)
└─ Tag filter
```

**Example searches:**
- "technology" → finds tech decisions
- "job" → finds career decisions
- "constraint" → finds decisions mentioning constraints

### Q4: Is my data safe?

**A:** Yes, three ways:

```
1. LOCAL STORAGE
   └─ Data stored in your computer only
   └─ No upload to cloud
   └─ No third-party access

2. PRIVATE LAYER
   └─ Mark sensitive decisions as Private
   └─ AI cannot access Private decisions
   └─ Only you see them

3. TRANSPARENT FORMAT
   └─ JSON file you can read/edit
   └─ No encryption/obfuscation
   └─ Full visibility
```

### Q5: How do I export my data?

**A:** Your data is already portable!

```
Location: human_ai_memory.json

To back up:
├─ Copy file to external drive
├─ Upload to cloud storage
├─ Share with team

To restore:
├─ Copy file back to project folder
└─ Restart app

To use elsewhere:
├─ JSON format is standard
├─ Any tool can read it
└─ Easy to parse
```

### Q6: What if I want to start over?

**A:** Keep old data, start fresh:

```
Option 1: Archive old data
├─ Rename human_ai_memory.json → human_ai_memory.backup
└─ Fresh app starts with empty database

Option 2: Delete specific decisions
├─ Use UI to delete unwanted decisions
└─ Keep good ones

Option 3: Combine multiple files
├─ More advanced (edit JSON)
└─ Contact support if needed
```

### Q7: How often should I record decisions?

**A:** Quality over quantity!

```
Recording frequency:
├─ Major life decisions: Always record
├─ Career decisions: Always record
├─ Learning decisions: Always record
├─ Daily small decisions: Don't need to
├─ Routine choices: Don't need to

Sweet spot:
├─ 1-3 decisions per week
├─ More detail than frequency
├─ Focus on decisions you want to learn from
```

### Q8: How do I improve AI suggestions?

**A:** Feed it better data!

```
Steps:
1. Record decisions with FULL context
   └─ Don't skip constraint/alternative details

2. Add tags consistently
   └─ Helps AI match your situation types

3. Update reflections when outcomes clear
   └─ AI learns from results

4. Link related decisions
   └─ AI understands chains

5. Record variations
   └─ If you face similar situations, record
      how constraints were different
```

### Q9: Can I share my decisions with AI assistants?

**A:** Only decisions marked SHAREABLE

```
How:
1. Copy decision text
2. Paste into ChatGPT/Claude/etc.
3. Add context: "Here's how I've handled 
   similar situations in the past"

Example:
"Here's how I decided to learn Python:
Goal: Get a job
Constraints: 2 months, no money
Alternatives: Java (too complex), 
Go (small community)
Choice: Python
Reasoning: Best for beginners, big community
Result: Became job-ready in 6 weeks"

AI assistant can now give better advice!
```

### Q10: Is there a mobile app?

**A:** Not yet, but you can access on mobile browser!

```
On phone/tablet:
1. Open browser (Chrome, Safari, etc.)
2. Go to http://localhost:8504
3. Works on same WiFi network
4. Same functionality as desktop

Future:
├─ Mobile app planned
├─ Native iOS/Android
├─ Offline support
└─ Notifications
```

---

## Troubleshooting

### Problem: "Error: selected_decision not in list"

**Solution:**
- App was looking for decision in dropdown
- Fixed in recent update
- Restart the app: `streamlit run main.py`

### Problem: View Detail button doesn't work

**Solution:**
- Sidebar was interfering with navigation
- Fixed in recent update
- Restart app and refresh browser

### Problem: AI suggestions not showing

**Solution:**
- You may not have recorded enough decisions yet
- Minimum relevance score not met
- Try a more specific query
- Record more decisions to build history

### Problem: Data file is corrupted

**Solution:**
```
1. Stop the app (Ctrl+C)
2. Rename human_ai_memory.json to .backup
3. Start fresh or restore backup
4. Restart app
```

### Problem: App runs slow

**Solution:**
```
1. You may have 1000+ decisions
2. This is expected at that scale
3. Future versions will optimize
4. Consider archiving old decisions
```

---

**Made with ❤️ for better decision-making!**

Questions? Check ARCHITECTURE.md for technical details or DEVELOPMENT_GUIDE.md for how the AI works.
