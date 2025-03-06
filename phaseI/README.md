# Phase I: Analyzing Users, Competitors, and Initial Designs

## Executive Summary
#### Overall Objective 
We set out to design a heart disease risk predictor that makes it simpler for people to assess their potential risk without needing frequent, in-person medical visits. Our work included researching existing risk estimator tools, conducting heuristic evaluations, and developing personas and scenarios based on real-world contexts.

#### Big-Picture Insights:
- Competitor research revealed that cluttered interfaces, specialized medical jargon, and no guidance on biometrics reduce usability and trust.
- Heuristic evaluations highlighted the need for clear instructions, error prevention, and more intuitive layouts.
- Persona and scenario work showed that seniors, busy professionals, and other user groups require different forms of guidance and reassurance.

#### What We Learned:
- Even strong medical or technical foundations must be communicated in a way that non-experts understand.
-Short definitions and tooltips can bridge the knowledge gap.
-Considering data biases and ensuring the product can be adapted or updated is critical to addressing a wide range of user needs.
- Ongoing user feedback and iterative testing are crucial for refining the design and ensuring it meets the needs of diverse demographics

These findings serve as a guiding framework for subsequent phases, where user insights and competitor benchmarks will continue shaping the design and validation of our heart disease risk predictor.

## Design Artifacts

[Sketches & Diagrams](https://github.com/ChicoState/heartdisease-ux/tree/main/sketches)

[Persons & Scenarios](https://github.com/ChicoState/heartdisease-ux/blob/main/personas/README.md)

## Introduction

In “Phase I: Analyzing Users, Competitors, and Initial Designs,” our team focused on understanding how people assess heart disease risk and how existing tools serve them. We aimed to: 
1. Address the general problem of making heart risk assessment more accessible to users who may avoid routine doctor visits.
2. Develop a framework of user research to ensure that our initial designs match real needs. We employed several research methods to discover new insights.

## Methods

We employed several research methods to discover new insights:
1. Competitive Analysis
    - Explored existing tools like the ASCVD Risk Estimator (American Heart Association) and the Framingham Risk Score. We noted each tool’s features, interface strengths/weaknesses, and pricing.
    - This helped us see where our design could excel, such as offering cleaner UIs or giving personalized guidance.
2. Heuristic Evaluation
    - Used Nielsen’s heuristics (e.g., visibility of system status, error prevention) to systematically evaluate the user experience of competitor tools.
    - Documented usability gaps, including cluttered forms, medical jargon without explanations, and limited error handling.
3. Persona & Scenario Development
    - Constructed three core personas (John, Nancy, Jordan) representing different demographics, skill levels, and health goals.
    - Created short user scenarios to illustrate how each persona interacts with a heart disease risk tool and to identify design priorities (e.g., simplicity, minimal jargon, quick results).

These methods collectively provide a broad yet detailed view of user needs and competitive benchmarks. Anyone replicating this research can follow the same three-step approach, survey competitor tools, apply heuristic principles, and construct relevant user personas and scenarios, to gather comparable insights.

## Findings

From each method, we noted:
1. Competitive Analysis Findings
    - Strengths: Simple parameter inputs, immediate numerical feedback, well-established medical backing.
    - Weaknesses: Cluttered or outdated UIs, no option to track historical results, lack of plain-language explanations for medical terms, and no     -information on how to get biometrics.
    - This implied an opportunity to create a more helpful tool with a more intuitive interface and better user engagement features.
2. Heuristic Evaluation Findings
    - Good Visibility of System Status: Real-time risk updates after form inputs.
    - Challenges with Error Prevention & Clarity: Medical jargon, no tooltips, difficulty resetting or changing data.
    - Improvements Needed: More user guidance, integrated help, better layout for results.
3. Persona & Scenario Insights
    - John (58) values convenience over technical depth; suspicious of “unnecessary” doctor visits.
    - Nancy (78) is motivated but not highly tech-savvy; craves a calm, reassuring experience.
    - Jordan (29) is proactive, data-oriented, but works in high-stress bursts; needs swift insight and reassurance.
    - Collectively, we understood that a broad range of users want a quick, straightforward interface with user-friendly explanations.

## Conclusions

These discoveries translate to concrete design recommendations:
1. Provide a clean layout with large input fields, helpful prompts, and minimal but clear instructions.
2, Introduce brief tooltips or short text to define medical terms.
3. Provide immediate alerts and suggestions if values appear out of realistic ranges.
4. Show how results are calculated or at least provide a short explanation (“Your risk percentage is based on factors X, Y, Z”).
5. Offer a feature to save user data so they can revisit progress over time.

Shaping future work around these principles ensures that we address the range of user needs discovered and creates a foundation for further usability testing.

## Caveats

Here are some some limitations we are aware of:
1. Limited User Pool:
    - Because we did not conduct extensive real-world interviews, much of our current understanding is based on secondary research and assumptions. Additional field studies may uncover new use cases or reveal different user needs.
2. Method Constraints
    - While heuristic evaluations provide a structured way to identify usability issues, they cannot fully replicate real-world contexts. As a result, certain practical or environmental factors may remain unaddressed.
3. Assumptions
    - We plan to include guidance for users on how to obtain relevant health metrics such as blood pressure or cholesterol readings from clinics, at home test kits, perhaps or routine medical checkups. Even so, our design assumes that most users can and will be able to get these measurements, which might not be feasible for everyone.
4. Data Limitations
    - The underlying datasets that inform our tool or model may not fully represent all genders, races, or age groups, potentially leading to uneven accuracy. Addressing these gaps requires broader, more diverse data collection and continuous validation to ensure equitable performance for all user demographics.
