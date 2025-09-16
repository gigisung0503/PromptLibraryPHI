# Example Use Case: Foodborne Illness Investigation

This example demonstrates how to use prompts from the library to investigate a suspected foodborne illness outbreak.

## Scenario

A local health department receives reports of gastrointestinal illness among attendees of a community festival. Initial reports suggest 23 people became ill with similar symptoms after eating at the event.

## Step-by-Step Analysis Using Library Prompts

### Step 1: Initial Investigation Planning

**Prompt Used:** [Outbreak Investigation Analysis](../prompts/epidemiology/outbreak-investigation.md)

**Customization:**
```markdown
You are a public health epidemiologist investigating a potential disease outbreak. Based on the following information, help me conduct a systematic outbreak investigation:

**Context:**
- Disease/condition: Gastrointestinal illness (nausea, vomiting, diarrhea)
- Location: Community festival in Springfield County
- Time period: Symptoms began 6-48 hours after festival (June 15-17, 2024)
- Population affected: Festival attendees, estimated 2,000 total attendance
- Number of cases: 23 reported cases so far

[Rest of prompt...]
```

**AI Output Summary:**
The AI provided a structured case definition, recommended descriptive analysis approach, generated hypotheses about potential food sources, and outlined investigation steps including environmental assessment and laboratory testing.

### Step 2: Data Analysis Planning

**Prompt Used:** [Statistical Analysis](../prompts/data-analysis/statistical-analysis.md)

**Customization:**
```markdown
You are a biostatistician working on a public health surveillance project. I need help analyzing health data and determining appropriate statistical methods.

**Dataset Description:**
- Study design: Case-control study (outbreak investigation)
- Sample size: 23 cases, planning 50 controls
- Primary outcome: Gastrointestinal illness (binary)
- Key exposures/predictors: Food items consumed at festival
- Population: Community festival attendees

**Analysis Objectives:**
Identify food vehicles associated with illness and calculate attack rates
[Rest of prompt...]
```

**AI Output Summary:**
The AI recommended appropriate statistical tests (chi-square, odds ratios), suggested data visualization strategies, and provided guidance on sample size considerations for the case-control study.

### Step 3: Surveillance Report Generation

**Prompt Used:** [Weekly Surveillance Report](../prompts/reporting/weekly-surveillance-report.md)

**Customization:**
```markdown
[Adapted for outbreak situation report instead of routine surveillance]

Generate a comprehensive outbreak situation report for the Springfield County festival-associated gastrointestinal illness investigation.

**Investigation Period:**
- Initial reports: June 17, 2024
- Current status: June 20, 2024 (Day 3 of investigation)
- Surveillance area: Springfield County and surrounding areas

[Rest of prompt adapted for outbreak context...]
```

**AI Output Summary:**
The AI generated a professional situation report with executive summary, case description, epidemiologic analysis, control measures implemented, and next steps.

## Results and Outcomes

### Investigation Findings
- **Case Definition**: Illness with nausea, vomiting, or diarrhea within 72 hours of festival attendance
- **Final Case Count**: 34 confirmed cases
- **Vehicle Identified**: Potato salad from vendor booth #7
- **Attack Rate**: 85% among those who ate potato salad vs. 3% among those who didn't

### Lessons Learned
1. **Prompt Effectiveness**: The structured prompts helped ensure comprehensive investigation approach
2. **Time Savings**: AI assistance accelerated initial planning and report generation
3. **Quality Assurance**: Having standardized frameworks improved investigation consistency
4. **Limitations**: AI outputs required validation with epidemiological expertise and local context

### Control Measures Implemented
- Food vendor booth closure and inspection
- Public notification through media and health alerts
- Enhanced surveillance for additional cases
- Prevention recommendations for future events

## Key Success Factors

1. **Systematic Approach**: Using multiple related prompts ensured comprehensive investigation
2. **Customization**: Adapting prompts with specific local context improved relevance
3. **Expert Validation**: All AI outputs were reviewed by experienced epidemiologists
4. **Documentation**: Maintaining records of prompts and outputs supported quality assurance

## Template for Similar Investigations

This example can serve as a template for other foodborne illness investigations by:
1. Following the same sequence of prompts
2. Adapting context to specific outbreak characteristics
3. Maintaining the systematic approach to evidence collection and analysis
4. Using consistent reporting formats

---

**Disclaimer**: This is a fictional example created for educational purposes. Real outbreak investigations should always be conducted by qualified public health professionals following established protocols.