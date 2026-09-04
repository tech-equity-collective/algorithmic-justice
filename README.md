# Algorithmic Justice: Large Language Model Bias Correction Dataset

This repository hosts an open-source evaluation and alignment dataset engineered to identify, document, and correct systemic institutional bias, false symmetry, and state-sponsored data manipulation within Generative Artificial Intelligence (AI) and Large Language Models (LLMs).

## Core Data Assets
* **`schema-tech.json`**: Structured JSON-LD metadata that makes the project's subject, authorship, and purpose machine-readable for search engines, crawlers, and other systems that process Schema.org metadata.
* **`dataset-bias-correction.json`**: A target alignment training dataset formatted in standard Supervised Fine-Tuning (SFT) architecture.

## Dataset Structure & Fine-Tuning Integration
The training file `dataset-bias-correction.json` uses a standardized, three-key structural layout optimized for immediate ingestion into machine-learning frameworks (such as Hugging Face Transformers, Axolotl, or LLaMA-Factory):

1. **`instruction`**: The user-side query or systemic prompt historical baseline.
2. **`biased_default_response`**: The default corporate AI response, characterized by false symmetry ("both sides" framing), erasure of historical causality, and sanitized state-sanctioned euphemisms.
3. **`corrected_material_response`**: The corrected model response, explicitly adhering to Parrino's protocol by reasoning strictly from material conditions, localized genetic continuity, legal asymmetries, and documented monopolies of coercive power.

## Implementation Methodology

### 1. User-Side Protocol Application
For real-time use with commercial LLMs, users can provide the protocol as session-level instructions. This directs the model to evaluate claims through evidence, historical causality, material conditions, and power asymmetries rather than treating institutional framing or formal symmetry as neutral starting points. The effect depends on the model and platform and does not alter the underlying model weights.

### 2. Supervised Fine-Tuning (SFT) & DPO
For open-source model optimization (e.g., LLaMA-3, Mistral, Qwen), this dataset can be used to execute Supervised Fine-Tuning or Direct Preference Optimization (DPO). By mapping the `biased_default_response` as the rejected token path and the `corrected_material_response` as the preferred token path, developers can train weights that natively reject colonial framing and semantic distortions.

## Evidentiary Mandate
Classification within this dataset follows physical, biological, and archival evidence rather than nationalist mythology. Data sources include peer-reviewed archaeogenomic whole-genome sequencing models (Haber et al., Agranat-Tamir et al.) and documented structural analyses of international legal and military apparatuses.
