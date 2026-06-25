# Case Studies

These examples are anonymized. Names, systems, and internal implementation details have been generalized while preserving the type of work, the value delivered, and my contribution.

## 1. Market Research Assistant

### Context

Business users needed a faster way to explore research and brand-tracking information. The data was useful, but the workflow required knowing the right terminology, metrics, filters, periods, and comparison logic before asking the right question.

### Product Idea

The app turned market-research questions into structured analysis flows. Instead of asking users to manually navigate datasets, the ChatGPT App could help interpret business intent, apply the right filters, and return analysis in a language that matched the way stakeholders discussed brands, markets, segments, and trends.

### Example Capabilities

- Discover available markets, brands, metrics, segments, and periods.
- Analyze brand funnel metrics and identify drop-offs.
- Compare brands, markets, and audience segments.
- Review trend performance over quarters or year-over-year windows.
- Surface imagery or perception attributes that over-index or under-index.
- Explain data availability, caveats, and sample-size limitations.

### Value

The app reduced the distance between business questions and data-backed answers. It made research data easier to use for non-technical stakeholders and helped standardize how recurring brand-tracking questions were answered.

### My Contribution

I participated in the app from definition to iteration:

- Gathered user needs and clarified which research questions were most valuable.
- Helped translate business terminology into app behavior and expected outputs.
- Reviewed test conversations to identify missing context, confusing answers, or edge cases.
- Worked with the technical team to refine tool behavior and response expectations.
- Participated in feedback loops with stakeholders to make the app more useful in real analysis workflows.

## 2. Service Operations Assistant

### Context

Users needed a more natural way to search and understand operational service information. The challenge was not just retrieving records, but helping users ask better questions, find relevant context, and interpret what the records meant.

### Product Idea

The app connected ChatGPT to a service-management environment through a controlled connector. It allowed users to search for relevant portfolio or service information, retrieve context, and analyze records conversationally.

### Example Capabilities

- Test whether the connector and permissions are working.
- Search operational records using business-friendly questions.
- Retrieve context around relevant records.
- Analyze record portfolios, patterns, or grouped results.
- Support follow-up questions without forcing users to restart the workflow.

### Value

The app helped turn operational information into a more accessible support experience. Users could move from a question to relevant context more quickly, while the technical implementation kept the interaction within a controlled connector pattern.

### My Contribution

I focused on making the app fit user expectations:

- Worked with users to understand their recurring service questions and pain points.
- Helped define what useful search and analysis outputs should look like.
- Validated whether responses were understandable for non-technical users.
- Coordinated feedback with the technical team when users needed different context, filters, or phrasing.
- Supported iterative testing so the app could move closer to real operational usage.

## 3. Reusable In-Chat Feedback Widget

### Context

Once users start using internal AI apps, they need an easy way to report when something is wrong, unclear, incomplete, or missing. Relying only on meetings or informal messages makes feedback hard to track and hard to connect to the exact conversation where the issue occurred.

### Product Idea

The feedback experience was designed as a reusable in-chat widget that could appear when a user needed to report an issue or suggest an improvement. The widget could collect a visible user comment while preserving structured hidden context such as the category, expected behavior, actual behavior, related records, and chat context.

### Example Feedback Categories

- Data quality issue
- Scope or interpretation issue
- Formatting or response-style issue
- Feature request
- Other improvement idea

### Value

The feedback widget created a bridge between adoption and continuous improvement. Instead of treating user feedback as separate from the app experience, it made feedback part of the workflow itself.

### My Contribution

I proposed the feedback mechanism as a reusable skill/widget pattern across apps. My focus was to make feedback actionable for both users and the technical team:

- Lower the friction for users to report problems inside the chat.
- Capture enough structured context for the team to reproduce and understand the issue.
- Make the pattern reusable so future apps could share the same feedback flow.
- Connect feedback directly to product iteration and app improvement.
