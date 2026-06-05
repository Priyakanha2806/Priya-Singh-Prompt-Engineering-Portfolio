# Prompt Engineering Portfolio

Name: Priya Singh
Date: 06 June 2026
LLM Used: ChatGPT (GPT-5.5)

---

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

#### Goal
Explain Neural Networks to a 10-year-old child.

#### Initial Prompt (V1)

Explain neural networks.

#### Refined Prompt (V2)

Explain neural networks in simple language that a middle-school student can understand. Use examples and avoid technical jargon.

#### Final Prompt (V3)

You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a real-life example, and a fun analogy. Keep the explanation under 200 words and make it engaging.

#### Final Output

Imagine your brain is like a team of tiny helpers working together to solve problems. A neural network in a computer works in a similar way.

Let's say you want a computer to recognize whether a picture shows a cat. First, the computer looks at different parts of the picture, such as ears, eyes, whiskers, and fur. Small helper units inside the neural network each look for certain patterns.

These helpers pass information to other helpers, who combine the clues and make a guess. If the computer guesses wrong, it learns from its mistake and adjusts itself to do better next time.

Think of it like learning to identify different dog breeds. At first, you make mistakes, but after seeing many examples, you get better and better. Neural networks learn in a similar way by practicing with lots of examples.

That's why neural networks can help computers recognize faces, understand speech, and recommend videos.

### 1.1 Scenario B: Professional Email

#### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

#### Initial Prompt (V1)

Write an email declining a job offer.

#### Refined Prompt (V2)

Write a professional email declining a job offer while thanking the employer for the opportunity.

#### Final Prompt (V3)

You are a professional career advisor. Write a formal email to decline a job offer because another opportunity was accepted. Express sincere gratitude, maintain a positive relationship, and mention interest in future opportunities with the company. Keep the tone professional and respectful.

#### Final Output

Subject: Thank You for the Opportunity

Dear Hiring Manager,

Thank you very much for offering me the opportunity to join your organization. I sincerely appreciate the time and effort that you and your team invested throughout the recruitment process.

After careful consideration, I have decided to accept another opportunity that aligns more closely with my current career goals. Therefore, I must respectfully decline your offer.

This decision was not easy, as I was genuinely impressed by your company's culture, values, and the professionalism of everyone I met during the process.

I am grateful for your confidence in my abilities and hope our paths may cross again in the future. I would welcome the opportunity to stay connected and explore potential opportunities with your organization at a later date.

Thank you again for your understanding, and I wish you and your team continued success.

Sincerely,

Priya Singh

### 1.1 Scenario C: Creative Content

#### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

#### Initial Prompt (V1)

Create a tagline for an eco-friendly water bottle.

#### Refined Prompt (V2)

Create five catchy marketing taglines for an eco-friendly reusable water bottle aimed at environmentally conscious consumers.

#### Final Prompt (V3)

You are an award-winning brand strategist and copywriter. Create 10 short, memorable, and emotionally appealing taglines for a premium eco-friendly reusable water bottle brand. The taglines should communicate sustainability, modern lifestyle, and environmental responsibility. Each tagline should be under 8 words.

#### Final Output

1. Sip Sustainably, Live Responsibly.
2. Every Refill Saves Tomorrow.
3. Drink Green, Live Clean.
4. Hydration with a Purpose.
5. Refill Today, Protect Tomorrow.
6. Carry Change in Every Sip.
7. Good for You, Better for Earth.
8. Sustainable Sips, Endless Impact.
9. Refresh Yourself, Respect Nature.
10. One Bottle. Infinite Difference.

## 1.2 Iteration Documentation

### Scenario A: Technical Explanation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|------------------------------|
| V1 | Explain neural networks. | N/A | N/A |
| V2 | Explain neural networks in simple language that a middle-school student can understand. Use examples and avoid technical jargon. | Added audience specification and simplicity requirements. | The explanation became easier to understand and less technical. |
| V3 | You are an expert elementary school teacher. Explain neural networks to a 10-year-old child using simple words, a real-life example, and a fun analogy. Keep the explanation under 200 words and make it engaging. | Added role assignment, context, analogy, and length constraints. | Produced a more engaging, age-appropriate explanation. |

### Scenario B: Professional Email

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|------------------------------|
| V1 | Write an email declining a job offer. | N/A | N/A |
| V2 | Write a professional email declining a job offer while thanking the employer for the opportunity. | Added professional tone and gratitude requirement. | Resulted in a more courteous and professional email. |
| V3 | You are a professional career advisor. Write a formal email to decline a job offer because another opportunity was accepted. Express sincere gratitude, maintain a positive relationship, and mention interest in future opportunities with the company. | Added role assignment, context, and relationship-building requirements. | Generated a realistic and polished professional email. |

### Scenario C: Creative Content

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|---------|--------------|------------------------------|
| V1 | Create a tagline for an eco-friendly water bottle. | N/A | N/A |
| V2 | Create five catchy marketing taglines for an eco-friendly reusable water bottle aimed at environmentally conscious consumers. | Added audience and quantity requirements. | Produced more diverse and relevant taglines. |
| V3 | You are an award-winning brand strategist and copywriter. Create 10 short, memorable, and emotionally appealing taglines for a premium eco-friendly reusable water bottle brand. | Added role assignment, brand context, emotional appeal, and constraints. | Generated stronger and more marketable taglines. |
## 1.3 Role and Context Analysis

Role assignment and context setting significantly improved the quality of the generated outputs. In Scenario A, assigning the role of an elementary school teacher helped the model adapt its language and explanation style to suit a young audience. In Scenario B, the role of a professional career advisor resulted in a more polished, realistic, and professional email. Context setting clarified the audience, purpose, and expected tone, reducing ambiguity and producing more accurate responses. Overall, combining role assignment with contextual information made the outputs more targeted, coherent, and effective.
---

## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation

#### Chosen Task
Creating a short story opening (2–3 sentences)

#### Base Prompt

Write the opening of a short story about a mysterious lighthouse.

### Low Temperature (0.2)

**Prompt Used:**

Write the opening of a short story about a mysterious lighthouse. Be precise and consistent.

**Output:**

The lighthouse stood alone on a rocky island off the coast. Every night, its light shone across the sea, even though no lighthouse keeper had lived there for decades. Local fishermen avoided the area and refused to speak about it.

### Medium Temperature (0.7)

**Prompt Used:**

Write the opening of a short story about a mysterious lighthouse.

**Output:**

The old lighthouse rose from the cliffs like a forgotten guardian of the sea. On stormy nights, its beam swept across the dark water, though nobody knew who operated it. The villagers whispered stories about strange figures seen near its entrance.

### High Temperature (1.3)

**Prompt Used:**

Write the opening of a short story about a mysterious lighthouse. Be creative and explore diverse ideas.

**Output:**

The lighthouse appeared only when the moon turned silver-blue. Sailors claimed it drifted across the ocean like a wandering ghost, guiding lost ships toward impossible horizons. Those who followed its light returned with memories that did not belong to them.

### Comparison Table

| Temperature | Style | Creativity | Consistency |
|------------|--------|------------|------------|
| Low (0.2) | Factual and direct | Low | High |
| Medium (0.7) | Balanced | Medium | High |
| High (1.3) | Imaginative and unusual | High | Medium |

### 2.2 Analysis & Recommendations

Low temperature settings are most useful when accuracy and consistency are important. Examples include technical documentation and legal or policy writing. High temperature settings are useful for creative writing, brainstorming, marketing campaigns, and idea generation. In this experiment, the medium temperature produced the best result because it balanced creativity with coherence. The high-temperature output was the most imaginative, while the low-temperature output was the most predictable and structured.
---

## Part 3: Strategic Prompting Techniques

### 3.1 Chain-of-Thought Prompting

#### Selected Problem: Option B – Multi-Step Reasoning

Problem:

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

### Without Chain-of-Thought

#### Prompt

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.

#### Output

172 employees

### With Chain-of-Thought

#### Prompt

Let's solve this step by step.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring?

#### Output

Engineering employees = 150 × 60% = 90

Sales employees = 150 × 25% = 37.5 ≈ 38

Operations employees = 150 − 90 − 38 = 22

Additional engineers hired = 90 × 20% = 18

Additional sales employees hired = 38 × 10% = 4

Total employees after hiring = 150 + 18 + 4 = 172

Final Answer: 172 employees

### Comparison

The output without chain-of-thought provided only the final answer. In contrast, the chain-of-thought approach showed every calculation step used to reach the solution. This made the reasoning process transparent and easier to verify. Chain-of-thought prompting is especially useful for mathematical, logical, and multi-step reasoning tasks. However, it can sometimes produce longer responses than necessary.
