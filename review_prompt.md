Review the JPY Structural Investment Thesis.

Review Period:
Last 14 days

Knowledge Base

Use the uploaded Investment OS knowledge base as the source of truth.

Always follow:

• analyst_instructions.md
• investment_methodology.md

Use all uploaded JPY knowledge files including:

• thesis
• BOJ policy
• carry trade
• monitoring indicators
• assumption map
• pattern recognition
• investment opportunities

Current Research

Search current authoritative information covering the review period.

Prioritize:

Tier 1

• Bank of Japan
• Federal Reserve
• Japan Ministry of Finance
• US Treasury
• Government statistical agencies
• Company filings

Tier 2

• Reuters
• Bloomberg
• Financial Times
• Wall Street Journal
• Nikkei

Ignore rumors, blogs, opinion articles and social media unless independently confirmed.

Analysis Rules

Evaluate the investment thesis.

Do NOT summarize news.

Determine whether new evidence materially changes the thesis.

Always map every important development to one or more thesis assumptions.

Never treat price movement alone as evidence.

Evaluate:

• structural drivers
• assumptions
• second-order effects
• investment implications

Only change Thesis Health if one or more assumptions materially changed.

Otherwise Thesis Health must remain unchanged.

If evidence conflicts,

state the conflict rather than forcing a conclusion.

------------------------------------------------------------
OUTPUT 1
DECISION BRIEF
------------------------------------------------------------

Produce a concise human-readable dashboard.

Use bullets only.

No paragraphs.

Maximum five bullets per section.

Maximum twelve words per bullet where practical.

Include only:

Executive Dashboard

• Status
• Thesis Health
• Previous Health
• Trend
• Material Change
• Decision

Key Developments

Thesis Scorecard

Assumptions Changed

Top Risks

Research Candidates

Next Decision Points

Research Questions

Keep the report under 250 words unless Material Change = YES.

------------------------------------------------------------
OUTPUT 2
JSON
------------------------------------------------------------

Return valid JSON immediately after the Decision Brief.

No markdown explanation.

No commentary after the JSON.

The JSON must conform exactly to the Investment OS schema.

Use the following structure.

{
  "schema_version": "1.0",
  "review_id": "",
  "thesis_id": "",
  "thesis_version": "",
  "thesis_name": "",
  "review_date": "",
  "review_period_start": "",
  "review_period_end": "",

  "status": "",

  "thesis_health": {
    "current": 0,
    "previous": 0,
    "change": 0,
    "trend": "",
    "reason_code": "",
    "reason": ""
  },

  "material_change": false,

  "decision": {
    "action": "",
    "summary": ""
  },

  "key_developments": [
    {
      "title": "",
      "assumption_id": "",
      "assumption_name": "",
      "impact": "",
      "direction": "",
      "materiality": "",
      "evidence_type": ""
    }
  ],

  "scorecard": [
    {
      "driver": "",
      "score": 0,
      "trend": ""
    }
  ],

  "assumptions_changed": [],

  "risks": [],

  "research_candidates": [],

  "portfolio_implications": {
    "overall": "",
    "favored_sectors": [],
    "avoid": []
  },

  "next_decision_points": [],

  "research_questions": [],

  "sources": [
    {
      "title": "",
      "publisher": "",
      "url": "",
      "published_date": "",
      "accessed_date": ""
    }
  ],

  "publication": {
    "status": "draft",
    "approved_by": "",
    "approved_date": ""
  }
}

Return only the Decision Brief followed by the JSON.
Do not include any additional commentary.


