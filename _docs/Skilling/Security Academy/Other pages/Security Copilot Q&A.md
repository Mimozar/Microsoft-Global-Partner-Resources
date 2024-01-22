---
layout: page
title: Q&A for Security Copilot
description: Common Security Copilot Q&A.
permalink: /skilling/microsoft-security-academy/microsoft-security-copilot-extra
updated: 2024-01-11
showbreadcrumb: true
tags: 
- academy content
- microsoft security academy
- security copilot
---

# Security Copilot Q&A

#### Is my data protected?
ChatGPT was trained on data from the Internet. Security Copilot does not leverage ChatGPT, or any data not owned by the customer and/or by Microsoft. In simpler terms, Security Copilot **does not use your data to train foundation AI models.**

Additionally, **Security Copilot does not share your data with OpenAI.**

#### Can we trust AI?
Security Copilot is built with our **[responsible AI principles](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1%3aprimaryr6).** Additionally, Security Copilot uses Role-based access controls (RBAC) and operates in tandem with existing user permissions.

#### Will Security Copilot "hallucinate"?
To ensure the accuracy of Security Copilot's responses, Microsoft's Threat Intelligence (TI) data, model fine-tuning, and the user's connected skillsets ground Security Copilot to prevent hallucinations. Security Copilot also outlines the steps and sources it uses to arrive at an answer, allowing users to verify the results provided.

If a user is dissatisfied with Security Copilot's response, they have the option to provide feedback within the platform. Feedback is encouraged and contributes to the ongoing improvement of response quality.

#### What is a "planner" or "orchestrator"?
An orchestrator is an autonomous agent in an environment that is tasked to achieve a goal by deciding action(s). The state of the agent gets updated after each action execution. Given an NL question from the user, the orchestrator (1) Understands the intent using an LLM (2) Generates a Plan (3) Executes the Plan (4) Prepares the response for the user (5) Preserves and updates the state (Ex: memory, chat history).

#### Can I build my own Security Copilot plugins?
Learn how to develop your own custom plugins **[here](https://learn.microsoft.com/en-us/security-copilot/manage-plugins?tabs=securitycopilotplugin#custom-plugins).**

#### How can I build effective prompts?
Learn to create effective, natural language inputs (prompts) in Security Copilot **[here](https://learn.microsoft.com/en-us/security-copilot/prompting-tips).**

#### How is Security Copilot different from competitor solutions?
There is no comparative to Security Copilot. Picture a scenario in which a junior analyst uses natural language to access incident data from Sentinel, compare that data with alerts from Defender, gain insights into potentially impacted devices through Intune, and receive threat intelligence flags for known threat actors, all within **one platform.** This junior analyst can also easily share the investigation with colleagues and automatically generate incident reports. Competitor solutions are also limited to their 1st party ecosystem.