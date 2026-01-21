# Interactive Continuity Recall Feature

## Overview
The **Interactive Continuity Recall** feature enables AI to remember human decisions in context by comparing new decisions against similar past decisions and intelligently updating recommendations based on changed circumstances.

## How It Works

### Step 1: Initial Decision Input
When you start creating a new decision, the system automatically:
- Detects if you have similar past decisions
- Shows a notification when matches are found
- Offers to open the "Continuity Recall Mode"

### Step 2: Continuity Recall Mode

Once activated, the system displays:

#### 📌 Your Previous Decision
- **Date**: When you made the decision
- **Goal**: Your original intention
- **Your Choice**: What you decided
- **Previous Constraints**: Time, cost, risk, emotional factors
- **Reasoning**: Why you made that choice
- **Notes**: Any thoughts you recorded then

#### ⚡ What's Changed?
Interactive checkboxes let you specify:
1. **Goal Changed**: If your intention/goal has shifted
2. **Constraints Changed**: If your limitations/circumstances differ

### Step 3: Dynamic Recomputation

**If No Changes:**
- AI confirms your original choice still applies
- Suggests following the same path or exploring alternatives
- Shows why the previous decision remains optimal

**If Changes Detected:**
- You update your new goal and constraints
- System displays a **Change Summary** showing old vs new values
- AI **Recomputes Judgment** based on new situation
- Shows if recommendation changed and why

#### Comparison Scenarios:

**Same Recommendation:**
```
✅ Same Recommendation: Science
Your updated situation still aligns with choosing Science
```

**Changed Recommendation:**
```
⚠️ Recommendation Changed!
Previous Choice: Vocational
Updated Choice: Science
Old Reasoning: Quick entry into workforce
New Reasoning: Long-term career growth due to extended timeline
```

### Step 4: Save Updated Decision

The system allows you to:
- **Link to Previous Decision**: Automatically creates connection between old and new decisions
- **Add Notes**: Document how your situation evolved
- **Consent & Save**: Explicitly authorize the new decision entry

## Key Benefits

### 1. **Continuity**
- AI understands the full context of past decisions
- Recommendations consider historical patterns
- Avoids suggesting choices that previously didn't work

### 2. **Intelligence**
- System detects when circumstances change
- Recomputes optimal choices based on new constraints
- Explains why recommendations change

### 3. **Learning**
- Identifies when assumptions were wrong
- Shows how goals evolve over time
- Patterns emerge from linked decisions

### 4. **User Control**
- Users decide if situation has changed
- No assumptions made about constraints
- Explicit consent required to save

## Use Cases

### Career Planning
```
Past Decision (2023):
- Goal: Get stable job quickly
- Constraint: Time (< 1 month)
- Choice: Vocational training

Updated Situation (2025):
- Goal: Long-term career growth
- Constraint: Time (> 6 months available)
- New Choice: Science/Engineering (recomputed)
- AI explains: "Your extended timeline now makes Science viable"
```

### Financial Decisions
```
Past Decision:
- Goal: Quick savings
- Constraint: Cost (Low budget)
- Choice: Save in regular account

Updated:
- Goal: Same (Quick savings)
- Constraint: Cost (Budget improved)
- New Choice: Investment portfolio (recomputed)
- AI shows: "Your improved financial situation enables better returns"
```

### Life Choices
```
Past Decision:
- Goal: Minimize stress
- Constraint: Emotion (High stress)
- Choice: Stay in current job

Updated:
- Goal: Career advancement
- Constraint: Emotion (Low stress now)
- New Choice: Take new opportunity (recomputed)
- AI explains: "Reduced stress threshold makes growth opportunity viable"
```

## Technical Details

### Similar Decision Detection
Matches decisions if:
- Description contains similar keywords
- Goal aligns with past goals
- Decision domain is the same

### Change Comparison
Tracks changes in:
- **Time Constraint**: < 1 month → > 6 months
- **Cost Constraint**: Low budget → High budget
- **Risk Tolerance**: Avoid risk → Willing to take risks
- **Emotional Factors**: High stress → Low stress

### Linked Decisions
- Creates relationship between old and new decisions
- Enables decision timeline view
- Shows decision evolution over time
- Helps identify long-term patterns

## Privacy & Ethics

✅ **User-Controlled**
- Users explicitly choose to enter continuity mode
- Changes must be confirmed by user
- Consent required before saving

✅ **Transparent**
- All reasoning shown to user
- Comparison visible between old and new
- Change summary clearly displayed

✅ **Editable**
- Can modify decision before saving
- Can link or unlink decisions
- Can add contextual notes

## Data Structure

### Decision Storage
```json
{
  "decision_id": "uuid",
  "timestamp": "2025-01-08T10:30:00",
  "title": "Career Path Choice",
  "description": "Choosing between education paths",
  "goal": "Long-term career growth",
  "constraints": {
    "time": "High (> 6 months)",
    "cost": "Medium ($1000-$10000)",
    "risk": "Medium (moderate risk)",
    "emotion": "Low stress"
  },
  "alternatives": ["Science", "Commerce", "Vocational"],
  "judgment": "Science",
  "reasoning": "Aligns with long-term goals and acceptable timeline",
  "notes": "Extended time available changed from previous decision",
  "related_decisions": ["previous-decision-uuid"],
  "privacy_level": "private"
}
```

## Future Enhancements

1. **Pattern Recognition**
   - Identify recurring decision patterns
   - Suggest when decisions may need revisiting
   - Track success rates of past recommendations

2. **Temporal Analysis**
   - Show decision evolution over time
   - Identify constraint trends
   - Predict future constraint changes

3. **Collaborative Learning**
   - Aggregate patterns (with consent)
   - Learn from similar user scenarios
   - Provide benchmarking insights

4. **Advanced Matching**
   - Semantic similarity detection
   - Fuzzy matching for similar goals
   - Multi-factor decision trees

## Best Practices

1. **Be Specific**: Provide detailed descriptions of changes
2. **Document Context**: Add notes explaining what evolved
3. **Link Decisions**: Establish connections for pattern recognition
4. **Review Regularly**: Check old decisions when facing new choices
5. **Consent**: Always review and consent before saving

## FAQ

**Q: Will my old decisions be updated?**
A: No. Your past decisions remain unchanged. Continuity Recall creates a new linked entry.

**Q: Can I change my mind after saving?**
A: Yes. You can edit or delete any decision from the Memory Timeline page.

**Q: How does AI know if constraints changed?**
A: You tell it! The system asks explicitly about changes and you confirm.

**Q: Will the system remind me to review past decisions?**
A: Currently it triggers automatically when similar decisions are detected. Future versions may add proactive reminders.

**Q: How are decisions linked?**
A: Through the `related_decisions` field that stores IDs of connected decisions.
