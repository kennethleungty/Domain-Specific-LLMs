# Domain Specific LLMs
### Comprehensive Compilation of Customized LLMs for Specific Domains and Industries

## Context
- Large language models (LLMs) have revolutionized the landscape of natural language processing, showing unparalleled prowess in a wide array of tasks, from simple text generation to complex problem-solving. 
- As the potential of LLMs continues to unfold, there's an increasing demand to tailor these models for specific domains and industries, ensuring that their vast knowledge base is attuned to specialized requirements. 
- This repo aims to create a database of domain-specific LLMs optimized for different sectors, ranging from healthcare and legal to finance and entertainment. 
- It seeks to bridge the gap between generic LLMs and niche applications, showcasing tools that truly understand and cater to the unique linguistic nuances and knowledge demands of different industries.
<br><br>

[![Contributions Welcome!](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=for-the-badge)](./CONTRIBUTING.md)

___

## Contents
1. [Biology](#biology)
2. [Finance](#finance)
3. [Healthcare](#healthcare)
4. [Information Technology](#it)
5. [Telecommunications](#telco)


___
<a name="biology"></a>
## Biology
| Name | Type | Description | Demo | Paper | Repo | Site |
| --- | --- | --- | --- | --- | --- | --- |
| ProtGPT2 | Pre-trained | LLM (with 738 million parameters) specifically for protein engineering and design by being trained on the protein space that generates de novo protein sequences following principles of natural ones. | [:link:](https://huggingface.co/nferruz/ProtGPT2) | - | - | [:link:](https://www.nature.com/articles/s41467-022-32007-7) |

___
<a name="finance"></a>
## Finance
| Name | Type | Description | Demo | Paper | Repo | Site |
| --- | --- | --- | --- | --- | --- | --- |
| BloombergGPT | Pre-trained | 50-billion parameter LLM trained on a wide range of financial data (363 billion token dataset) | - | [:link:](https://arxiv.org/abs/2303.17564) | - | - |
| FinChat | ? | Generative AI tool for investment research, helping to greatly reduce time requirements for data aggregation, visualization and summaries. | [:link:](https://www.youtube.com/watch?v=jPP-oYhQ3S0&ab_channel=BradenDennis) | -  | - | [:link:](https://finchat.io/) |
| FinGPT | Fine-tuned | Series of LLMs fine-tuned on base models (e.g., Llama-2) with open finance data | - | [:link:](https://arxiv.org/abs/2306.06031)  | [:link:](https://github.com/AI4Finance-Foundation/FinGPT) | [:link:](https://website.com) |
| FinMA | Fine-tuned | Financial LLM from fine-tuning LLaMa with finance-based instruction data with 136K data samples| [:link:](https://huggingface.co/ChanceFocus/finma-7b-nlp) | [:link:](https://arxiv.org/abs/2306.05443)  | [:link:](https://github.com/chancefocus/PIXIU) | - |
| Ask FT | ? | LLM tool that allows users to ask any question and receive a response using Financial Times (FT) content published over the last two decades. | [:link:](https://www.youtube.com/watch?v=T08mJT190bM) | [:link:](https://aboutus.ft.com/press_release/financial-times-launches-first-generative-ai-tool) | - | - |

___
<a name="healthcare"></a>
## Healthcare
| Name | Type | Description | Repo | Paper | Demo | Site |
| --- | --- | --- | --- | --- | --- | --- |
| Med-PaLM | Fine-tuned | Google's LLM (fine-tuned using PaLM as base model) designed to provide high quality answers to medical questions. | - | [:link:](https://www.nature.com/articles/s41586-023-06291-2)  | - | [:link:](https://sites.research.google/med-palm/) |
| Med-PaLM 2 | Fine-tuned | Enhanced version of Med-PaLM released on March 2023 by Google with improved performance | [:link:](https://www.youtube.com/watch?v=3Ud-BMOCkDI&ab_channel=Google) | [:link:](https://arxiv.org/pdf/2305.09617.pdf)  | [:link:](https://repo.com) | [:link:](https://cloud.google.com/blog/topics/healthcare-life-sciences/sharing-google-med-palm-2-medical-large-language-model) |
| PharmacyGPT | In-context Learning | GPT-4 model coupled with in-context learning (dynamic prompting approach) involving domain-specific data | - | [:link:](https://arxiv.org/abs/2307.10432)  | - | - |
| RUSSELL-GPT | Fine-tuned | LLM developed by National University Health System in Singapore to enhance clinicians' productivity (e.g., medical Q&A, case note summarization) | - | - | - | [:link:](https://www.nuhsplus.edu.sg/article/ai-healthcare-in-nuhs-receives-boost-from-supercomputer) |
| PH-LLM | Fine-tuned | The Personal Health Large Language Model (PH-LLM) is a fine-tuned version of Gemini, designed to generate insights and recommendations to improve personal health behaviors related to sleep and fitness patterns. | - | [🔗](https://arxiv.org/abs/2406.06474) | - | [:link:](https://research.google/blog/advancing-personal-health-and-wellness-insights-with-ai/) |


___
<a name="it"></a>
## Information Technology (IT)
| Name | Type | Description | Repo | Paper | Demo | Site |
| --- | --- | --- | --- | --- | --- | --- |
| OWL | Fine-tuned | A large language model for IT operations fine-tuned based on a custom Owl-Instruct dataset with a wide range of IT-related information | - | [:link:](https://arxiv.org/abs/2309.09298) | - | - |


___
<a name="telco"></a>
## Telecommunications
| Name | Type | Description | Repo | Paper | Demo | Site |
| --- | --- | --- | --- | --- | --- | --- |
| TelecomGPT: A Framework to Build Telecom-Specfic Large Language Models | Fine-tuned | Telecom-specific LLM which can be used for multiple downstream tasks in telecom domain | - | [:link:]([https://paper.com](https://arxiv.org/abs/2407.09424))  | - | - | 


<!-- Copy the following string to create a new entry! -->
<!-- | Name of LLM | Model Type (e.g., Fine-tuned) | Brief info | [:link:](https://demo.com) | [:link:](https://paper.com)  | [:link:](https://repo.com) | [:link:](https://website.com) | -->

___

## To Do
- [ ] Include examples from the range of other domains/industries listed in [Contributing](./CONTRIBUTING.md)
- [ ] Include non-LLM GenAI examples (expand scope of repo)
