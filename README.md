# Results generated with LLM-KG-Bench version 3

This repo contains [evaluation results](results/) generated with LLM-KG-Bench version 3 for 38 open and proprietary LLMs.
This includes the [configuration](configuration.yml), the [model format preference table](modelPreferences.csv) and the [plots](plots/).

The [raw result files](rawresults/) are passwort protected to reduce the chance of test data leakage into LLM training data. Please do not spread them unencrypted. You can unzip them with `Leave-Finest-Coats-Serena-Cheats-46`

## Model Preference Turtle vs. JSON-LD:

|                                            | RdfConnectionExplainStatic | RdfFriendCount-1 | RdfFriendCount-2 | RdfSyntaxFixList | Sparql2AnswerListOrga | Text2AnswerListOrga |
|--------------------------------------------|----------------------------|------------------|------------------|------------------|-----------------------|---------------------|
| Claude 3.5 Haiku                           | **JSON**                   | **TTL**          | **TTL**          | -                | -                     | -                   |
| Claude 3.5 Sonnet                          | -                          | -                | -                | -                | -                     | -                   |
| Deepseek-Coder-33B                         | -                          | **JSON**         | **JSON**         | **JSON**         | -                     | -                   |
| GPT3.5 2024/01                             | -                          | JSON             | **JSON**         | -                | -                     | **TTL**             |
| GPT4o 2024/11                              | -                          | -                | -                | JSON             | -                     | -                   |
| GPT4o-mini 2024/07                         | -                          | -                | TTL              | -                | -                     | **TTL**             |
| GPTo1-mini 2024/09                         | -                          | -                | -                | -                | -                     | -                   |
| GPTo1-pre 2024/09                          | -                          | -                | -                | -                | -                     | -                   |
| Gemini 1.5 Flash                           | -                          | **TTL**          | -                | -                | -                     | -                   |
| Gemini 1.5 Pro                             | -                          | -                | -                | -                | -                     | -                   |
| Gemini 2.0 Flash Exp                       | -                          | -                | -                | -                | -                     | -                   |
| Llama-3.3-70B                              | -                          | **JSON**         | **JSON**         | **JSON**         | -                     | -                   |
| Meta-Llama-3-70B                           | -                          | **JSON**         | **JSON**         | **JSON**         | -                     | -                   |
| Meta-Llama-3-8B                            | **TTL**                    | -                | -                | -                | -                     | -                   |
| Meta-Llama-3.1-70B                         | -                          | -                | -                | **JSON**         | **TTL**               | -                   |
| Meta-Llama-3.1-8B                          | -                          | **JSON**         | **JSON**         | JSON             | -                     | -                   |
| Meta-Llama-3.2-1B                          | -                          | -                | -                | **JSON**         | -                     | -                   |
| Meta-Llama-3.2-3B                          | **JSON**                   | **TTL**          | **TTL**          | **JSON**         | -                     | -                   |
| OpenCoder-8B                               | -                          | -                | -                | -                | TTL                   | -                   |
| Phi-3-medium-128k                          | **TTL**                    | -                | JSON             | -                | -                     | TTL                 |
| Phi-3-mini-128k                            | -                          | -                | **JSON**         | **JSON**         | -                     | -                   |
| Phi-3-small-128k                           | **JSON**                   | -                | -                | TTL              | -                     | -                   |
| Phi-3.5-mini                               | **TTL**                    | JSON             | -                | **JSON**         | **TTL**               | -                   |
| Qwen2-0.5B                                 | -                          | -                | JSON             | -                | -                     | -                   |
| Qwen2-1.5B                                 | **TTL**                    | **JSON**         | **JSON**         | **JSON**         | -                     | -                   |
| Qwen2-57B-A14B                             | -                          | -                | -                | **JSON**         | TTL                   | **TTL**             |
| Qwen2-72B                                  | -                          | -                | -                | **JSON**         | -                     | -                   |
| Qwen2-7B                                   | **JSON**                   | -                | -                | -                | -                     | TTL                 |
| Qwen2.5-0.5B                               | -                          | -                | -                | -                | -                     | -                   |
| Qwen2.5-1.5B                               | -                          | -                | -                | **JSON**         | -                     | -                   |
| Qwen2.5-14B                                | **TTL**                    | -                | -                | -                | -                     | TTL                 |
| Qwen2.5-32B                                | -                          | **TTL**          | **TTL**          | **JSON**         | **JSON**              | -                   |
| Qwen2.5-3B                                 | **JSON**                   | -                | -                | **JSON**         | -                     | -                   |
| Qwen2.5-72B                                | **JSON**                   | JSON             | **JSON**         | -                | -                     | **TTL**             |
| Qwen2.5-7B                                 | **JSON**                   | -                | -                | -                | **TTL**               | **TTL**             |
| Qwen2.5-Coder-32B                          | -                          | **TTL**          | **TTL**          | -                | -                     | -                   |
| Solar-pro-preview-22B                      | -                          | -                | -                | JSON             | -                     | -                   |
| Phi_3.5_MoE_Instruct                       | -                          | **JSON**         | **JSON**         | **JSON**         | **TTL**               | -                   |
