# New Query Feature - Multi-Question Session Guide

## Overview
The **New Query** feature allows users to ask multiple questions in sequence while maintaining continuity with previous decisions. When you ask a question you've asked before, the AI automatically reminds you of your previous choice and recomputes recommendations based on your current situation.

## How to Use

### Step 1: Save Your Decision
After completing the decision form and AI analysis:
1. Check the **✅ I consent to save this decision context** checkbox
2. Click **💾 Save Decision**

### Step 2: Success Screen with Options
You'll see a success message with three buttons:

```
✅ Decision saved successfully!

[❓ Ask Another Question] [📊 View Timeline] [Save Success Info]
```

### Step 3: Ask Another Question
Click **❓ Ask Another Question** to:
- Clear the current decision form
- Keep all previous decisions in memory
- Start a fresh decision query

### Step 4: Similar Decision Detection
If your new question is similar to a previous one:

```
🔍 We found 3 similar decision(s) you made before!

[Most Recent: 2025-01-05] [Previous Choice: Science] [Total Similar: 3]

[📖 Open Continuity Recall]
```

The system shows:
- **Most Recent Date**: When you last faced this decision
- **Previous Choice**: What you decided before
- **Total Similar**: Number of times you've faced this decision

## Continuity Recall Workflow

### Step 1: View Your Decision History
Click **📖 Open Continuity Recall** to see:

#### 📅 Your Similar Decision History
Shows all similar decisions in reverse chronological order:
```
⭐ MOST RECENT: 2025-01-05 - Science (expandable)
#2: 2024-12-20 - Science (expandable)
#3: 2024-10-10 - Vocational (expandable)
```

Each entry shows the date, choice, and full details when expanded.

#### ⭐ Most Recent Similar Decision
Expanded by default, showing:
- **Date**: When you made it
- **Goal**: Your intention at the time
- **Your Choice**: What you selected
- **Previous Constraints**: Time, cost, risk, emotion
- **Why you chose it**: The reasoning
- **Your notes**: Any context you recorded

### Step 2: What's Changed?
Two interactive checkboxes:

1. **Your goal or intention has changed**
   - Check if your objective has shifted
   - Update your new goal if checked

2. **Your constraints have changed**
   - Check if time, budget, risk tolerance, or stress changed
   - Update individual constraints if checked

#### If No Changes:
```
✅ Your situation hasn't changed!

1. Follow the same path (Recommended)
2. Explore new options if circumstances suggest it
3. Add notes about why you're revisiting this decision
```

#### If Changes Detected:
```
💡 Please update your current situation so I can recalculate the best path forward.

[Updated Goal field]
[Time Constraint dropdown]
[Cost Constraint dropdown]
[Risk Tolerance dropdown]
[Emotion/Stress dropdown]

📊 Changes Detected:
- Time: Low (< 1 month) → High (> 6 months)
- Cost: Low ($1000) → Medium ($1000-$10000)
```

### Step 3: AI Judgment - Current State Analysis
The system recomputes recommendations based on your current situation:

#### Same Recommendation:
```
✅ Same Recommendation: Science

💬 Your current situation still aligns with your previous decision.
   Science remains the optimal choice.

[Why it's still the best option - expandable]
   Reasoning: Long-term career growth aligns with extended timeline
```

#### Changed Recommendation:
```
⚠️ Recommendation Has Changed!

🔄 Your situation has evolved. Consider: Engineering

[Previous Choice Box]         [New Recommendation Box]
Science                       Engineering
Why then: Quick return        Why now: Better salary potential
on investment                 with extended timeline

[Why not other options - expandable]
- Commerce: Less aligned with your current constraints
- Vocational: Short-term focus vs your long-term goals
```

### Step 4: Save This Query
At the bottom of the Recall Mode:

**Option to Link Decisions:**
```
[🔗 Link to Previous Decision]
```
This automatically creates a connection between your new decision and the previous one.

**Personal Notes:**
```
Personal Notes:
"What changed or why are you revisiting this decision?"
```

**Save Actions:**
```
[✅ Checkbox: I consent to save]
[💾 Save & Link]  [❌ Exit & Start Fresh]
```

## Workflow Examples

### Example 1: Same Situation
**Previous Decision (2025-01-05):**
- Goal: Get stable job quickly
- Time: Low (< 1 month)
- Choice: Vocational training

**New Query (2025-01-08):**
- Description: "Choosing education path"
- System Detects: Similar to previous decision
- Changes: None
- AI Output: "✅ Same Recommendation: Vocational"
- Result: User can confirm or explore alternatives

### Example 2: Changed Constraints
**Previous Decision (2024-10-10):**
- Goal: Stable job quickly
- Time: Low (< 1 month)
- Cost: Low
- Choice: Vocational

**New Query (2025-01-08):**
- Description: "Choosing education path"
- System Detects: Similar to previous decision
- Changes: Time constraint increased (now have > 6 months)
- AI Output: "⚠️ Recommendation Changed: Science"
- Explanation: "Long-term financial prospects now possible with extended timeline"
- Result: User can choose new path with full context

### Example 3: Multiple Similar Decisions
**History:**
- 2024-08-01: Vocational (time constraint = low)
- 2024-10-10: Commerce (time constraint = medium)
- 2025-01-05: Science (time constraint = high)

**New Query (2025-01-08):**
- System Shows All 3 in timeline
- Most Recent: Science (from 2025-01-05)
- Allows reviewing entire decision evolution
- Shows how constraints progressively changed

## Key Features

### 1. **Automatic Reminders**
- Detects similar decisions automatically
- Shows date of previous choice
- Displays previous reasoning

### 2. **Change Detection**
- Asks explicitly about changes
- Shows old vs new constraints
- Tracks evolution over time

### 3. **Intelligent Recomputation**
- AI judges based on current state
- Explains if recommendation changed
- Shows why old/new choices differ

### 4. **Decision Linking**
- Creates relationships between decisions
- Enables timeline view
- Tracks decision evolution

### 5. **Explicit Control**
- User confirms changes
- Consent required to save
- Can exit and start fresh anytime

## Privacy & Data

✅ **Your Control**
- No automatic assumptions
- Explicit consent required
- Can delete decisions anytime
- Can edit existing decisions

✅ **Transparency**
- All comparisons visible
- All reasoning explained
- Full decision history accessible
- Change summaries provided

✅ **Continuity**
- Decisions linked for context
- Evolution patterns visible
- Decision timeline shows progression
- Related decisions connected

## Best Practices

1. **Be Specific**
   - Provide detailed descriptions
   - Explain your goals clearly
   - Document constraints precisely

2. **Update Consistently**
   - Note changes when they happen
   - Add context about evolution
   - Record why you're revisiting

3. **Review Patterns**
   - Check decision timeline
   - Identify patterns
   - Learn from past choices

4. **Link Related Decisions**
   - Establish connections
   - Enable pattern recognition
   - Show decision evolution

5. **Use Notes Effectively**
   - Document thought processes
   - Explain constraint changes
   - Record unexpected outcomes

## Common Scenarios

### Career Path Evolution
```
Jan 2024: Need job quickly → Vocational
Oct 2024: Have more time → Commerce
Jan 2025: Want career growth → Science
```
System shows full progression and recomputes at each stage.

### Financial Planning
```
Jan 2024: Low budget available
Oct 2024: Budget improved
System recommends different investment strategies
```

### Life Choices
```
Jan 2024: High stress, need stability
Oct 2024: Stress reduced
Jan 2025: Can pursue growth
```
Shows how reduced stress opens new opportunities.

## FAQ

**Q: Will my old decisions change when I ask a new question?**
A: No. Your past decisions remain unchanged. New queries create new entries linked to previous ones.

**Q: Can I ignore similar decision suggestions?**
A: Yes. You can click "❌ Exit & Start Fresh" to start without comparing to previous decisions.

**Q: How does the system know my constraints changed?**
A: You tell it through the checkboxes. The system asks explicitly rather than assuming.

**Q: What if I make a different choice this time?**
A: The system will show both your old and new choices, explaining why the recommendation changed.

**Q: Can I link decisions manually?**
A: Yes, there's a "🔗 Link to Previous Decision" button that lets you establish connections.

**Q: What happens if I have many similar decisions?**
A: The system shows all of them chronologically, highlighting the most recent one for comparison.

**Q: Can I edit decisions after saving them?**
A: Yes, go to "Memory Timeline" page and click "✏️ Edit" on any decision.
