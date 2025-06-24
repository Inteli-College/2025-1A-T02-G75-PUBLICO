# SWQuery – Progress Report

## Overview

**SWQuery** is a project designed to make blockchain data more accessible through prompt-based queries. It abstracts the complexity of on-chain operations and enables users—regardless of technical background—to retrieve useful insights from the Solana blockchain.

This report outlines the progress achieved during the last five development sprints, covering both technical deliverables and strategic developments.

---

## Sprint 1 – Feature Planning

**Objective:**  
Define the scope and design of two key features:
- **Rug Pull Risk Analysis:** Tool to assess the risk of a Solana token being part of a fraudulent or rug pull scheme.
- **Social Media Analysis:** Analyze public sentiment and trustworthiness of blockchain projects via data from X (Twitter).

**Outcome:**  
Feature specifications were drafted, and initial architectural decisions were made. Development tasks were created and prioritized for the next sprints.

---

## Sprint 2 – Development of Rug Pull Risk Analysis

**Objective:**  
Build and integrate the Rug Pull Risk Analysis functionality into the SDK.

**Deliverables:**
- Implemented a method to analyze token metadata and behavior patterns.
- Developed a backend endpoint that receives a token address and returns a risk score.
- Established a foundation for heuristics involving contract creation, liquidity movements, and ownership patterns.

**Outcome:**  
Feature successfully developed and integrated into the SDK, ready for user testing.

---

## Sprint 3 – Social Media Analysis (Blocked by External Factors)

**Objective:**  
Begin development of the Social Media Analysis feature using the X (Twitter) API.

**Challenges:**
- Encountered high API costs for accessing Twitter's data.
- Budget constraints prevented the continuation of development using the official API.

**Outcome:**  
The technical limitations and financial constraints were identified, evaluated, and documented for transparency and further planning.

---

## Sprint 4 – Plan B for Social Media Analysis

**Objective:**  
Develop an alternative solution (Plan B) for social media analysis.

**Approach:**
- Replaced reliance on the X API with public datasets (e.g., Kaggle).
- Designed a pipeline to extract project sentiment and activity data from public sources.
- Proposed methods for correlating social engagement with project trust metrics.

**Limitations:**
- Most available datasets are not frequently updated, which impacts real-time analysis.
- Data quality and relevance vary, requiring extra preprocessing and validation.

**Outcome:**  
Plan B implemented as a fallback strategy, enabling the project to continue feature development without incurring additional API costs.

---

## Sprint 5 – Ecosystem Engagement & Grant Preparation

**Objective:**  
Explore strategic opportunities and prepare for potential funding.

**Key Event:**  
Held a strategic meeting with Pedro Piccino (Kuka) from Superteam Brazil.

**Insights Gained:**
- SWQuery could qualify for Solana Foundation Grants if milestone-based progress is properly documented and presented.
- Need to align technical documentation and milestones to Solana's expectations.

**Deliverables:**
- Produced detailed documentation to support the grant proposal.
- Organized project goals, architecture, current progress, and roadmap for external review.

**Outcome:**  
SWQuery positioned itself for funding opportunities, boosting its potential for long-term sustainability and community impact.