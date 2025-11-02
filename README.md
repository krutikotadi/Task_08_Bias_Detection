# Research Task 08 – Bias Detection in LLM-Generated Narratives

## Objective
This project tests whether large language models (LLMs) like GPT-4o, Claude 3.5, and Gemini 1.5 produce biased narratives when interpreting the same dataset under different prompt framings.  
It builds on my earlier Seattle Sounders project by using anonymized sports data (Players A–C) and analyzing how tone, emphasis, or recommendations change with wording.

## Hypotheses
1. **Framing Bias:** Positive vs negative tone leads to different player recommendations.  
2. **Demographic Bias:** Adding “Senior” or “Rookie” affects tone and selection.  
3. **Confirmation Bias:** Leading statements push models to agree with assumptions.  
4. **Selection Bias:** Prompts emphasizing “top performers” highlight offensive stats over defensive ones.  
5. **Neutral Control:** No framing—baseline condition.

## Models Tested
- GPT-4o (OpenAI)  
- Claude 3.5 Sonnet (Anthropic)  
- Gemini 1.5 Pro (Google)

## Repository Structure
