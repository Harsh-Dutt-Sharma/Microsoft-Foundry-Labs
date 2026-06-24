# Azure AI Foundry Lab 3.3 – Content Filters and Guardrails

## Overview

This lab explores the implementation of Content Filters and Guardrails in Azure AI Foundry to improve AI safety and responsible usage. A custom guardrail was created, configured with multiple safety controls, and applied to a deployed GPT-4.1 model to evaluate its ability to handle harmful prompts.

## Objectives

- Understand Azure AI Foundry Guardrails and Content Filters.
- Create and configure a custom guardrail.
- Apply safety controls to a deployed GPT-4.1 model.
- Test model behavior against harmful prompts.
- Evaluate the effectiveness of Responsible AI safeguards.

## Key Activities

- Deployed the GPT-4.1 model in Azure AI Foundry.
- Performed offensive prompt testing in the playground.
- Explored default safety configurations and guardrails.
- Created a custom guardrail with advanced safety controls.
- Configured protections for:
  - Jailbreak attempts
  - Prompt injection attacks
  - Hate content
  - Sexual content
  - Self-harm content
  - Violent content
  - Protected materials
- Applied the guardrail to the GPT-4.1 deployment.
- Validated safety enforcement through testing.

## Results

- Successfully created and applied a custom guardrail.
- Harmful prompts were identified and appropriately blocked.
- Safety controls effectively enforced responsible AI behavior.
- GPT-4.1 responded according to the configured guardrail policies.

## Conclusion

This lab demonstrated how Azure AI Foundry Guardrails can be used to enhance AI safety by controlling harmful, unsafe, and policy-violating interactions. The implementation provided practical experience in deploying Responsible AI safeguards for real-world AI applications.

---

**Technology Stack:** Azure AI Foundry, GPT-4.1, Content Filters, Guardrails, Responsible AI
