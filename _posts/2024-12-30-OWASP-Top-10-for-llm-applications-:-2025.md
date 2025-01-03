---
layout: post
---
#### LLM1:2025 Prompt Injection/Jailbreaking

#### LLM2:2025 Sensitive Information Disclosure

#### LLM3:2025 Supply Chain

#### LLM4:2025 Data and Model Poisoning

#### LLM5:2025 Improper Output Handling

#### LLM6:2025 Excessive Agency

LLM-based system is often granted a degree of agency by its developer - the ability to call functions or interface with other systems via extensions (sometimes referred to as tools, skills or
plugins by different vendors) to undertake actions in response to a prompt. The decision over which extension to invoke may also be delegated to an LLM 'agent' to dynamically determine based
on input prompt or LLM output. Agent-based systems will typically make repeated calls to an LLM using output from previous invocations to ground and direct subsequent invocations.

Excessive Agency is the vulnerability that enables damaging actions to be performed in response to unexpected, ambiguous or manipulated outputs from an LLM, regardless of what is causing the
LLM to malfunction. Common triggers include:

• hallucination/confabulation caused by poorly-engineered benign prompts, or just a poorly-performing model;

• direct/indirect prompt injection from a malicious user, an earlier invocation of a malicious/compromised extension, or (in multi-agent/collaborative systems) a malicious/compromised peer agent.

The root cause of Excessive Agency is typically one or more of:\
• excessive functionality;\
• excessive permissions;\
• excessive autonomy.

Excessive Agency can lead to a broad range of impacts across the confidentiality, integrity and availability spectrum, and is dependent on which systems an LLM-based app is able to interact
with.

Note: Excessive Agency differs from Insecure Output Handling which is concerned with insufficient scrutiny of LLM outputs.

#### LLM7:2025 System Prompt Leakage

#### LLM8:2025 Vector and Embedding Weakness

In System utilizing Retrieval Augmented Model(RAG) with Large Language Models(LLMs) are more prone to these types of attacks.

Weakness in how vectors and embeddings are generated, stored, or retrieved can be exploited by malicious actions(intentional or unintentional) to inject harful content, manipulate model outputs and access sensitive information.

#### LLM9:2025 Misinformation 

Large Language Models(LLMs) produces false or misleading information that appears credible.

The major cause of misinformation is LLMs Hallucination. Hallucination occur when LLMs try to fill empty gaps in between unknown user input without truly understanding the content. And this is the major source of Misinformation.

Retrieval-Augmented-Generation(RAG) can be used to improve the reliability of the model.

#### LLM10:2025 Unbound Consumption

