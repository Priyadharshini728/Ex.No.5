

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: 
To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 


# AI Tools Required:

* [ChatGPT](https://chatgpt.com?utm_source=chatgpt.com) by [OpenAI](https://openai.com?utm_source=chatgpt.com)

---

# Explanation: 
```
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

```
## Define the Two Prompt Types

### 1. Naïve Prompt

A naïve prompt is broad, unstructured, or unclear. It provides minimal instruction to the AI model and may generate generic responses.

**Example:**
“Write a story.”

### 2. Basic Prompt

A basic prompt is clear, detailed, and structured. It provides proper instructions, context, and expected output format to guide the AI model.

**Example:**
“Write a 200-word story about a robot who learns emotions after meeting a lonely child. Include a beginning, conflict, and conclusion.”

---

# Test Scenarios Used

1. Creative Story Generation
2. Factual Question Answering
3. Summarization Task
4. Advice and Recommendation Task

---

# Comparative Evaluation Table

| Scenario       | Prompt Type      | Quality | Accuracy | Depth |
| -------------- | ---------------- | ------- | -------- | ----- |
| Creative Story | Basic            | 2/5     | 2/5      | 2/5   |
| Creative Story | Zero-Shot        | 3/5     | 3/5      | 3/5   |
| Creative Story | Few-Shot         | 4/5     | 4/5      | 4/5   |
| Creative Story | Chain-of-Thought | 5/5     | 4/5      | 5/5   |
| Factual Q&A    | Basic            | 2/5     | 3/5      | 2/5   |
| Factual Q&A    | Zero-Shot        | 3/5     | 4/5      | 3/5   |
| Factual Q&A    | Few-Shot         | 4/5     | 4/5      | 4/5   |
| Factual Q&A    | Chain-of-Thought | 5/5     | 5/5      | 5/5   |
| Summarization  | Basic            | 2/5     | 2/5      | 2/5   |
| Summarization  | Zero-Shot        | 3/5     | 3/5      | 3/5   |
| Summarization  | Few-Shot         | 4/5     | 4/5      | 4/5   |
| Summarization  | Chain-of-Thought | 4/5     | 5/5      | 5/5   |
| Recommendation | Basic            | 2/5     | 2/5      | 2/5   |
| Recommendation | Zero-Shot        | 3/5     | 3/5      | 3/5   |
| Recommendation | Few-Shot         | 4/5     | 4/5      | 4/5   |
| Recommendation | Chain-of-Thought | 5/5     | 5/5      | 5/5   |

---

# Analysis of Responses

The experiment showed that prompt structure significantly affects the quality of AI-generated responses.

## Basic Prompt

* Produced simple and acceptable responses.
* Lacked depth and detailed reasoning.
* Suitable for straightforward tasks.

## Zero-Shot Prompt

* Improved clarity and factual correctness.
* Role-based instructions enhanced performance.
* Useful for general explanatory tasks.

## Few-Shot Prompt

* Improved formatting and consistency.
* Examples guided the AI toward the expected output style.
* Produced more structured and accurate responses.

## Chain-of-Thought Prompt

* Generated the most detailed and coherent responses.
* Encouraged step-by-step reasoning.
* Performed best in reasoning-heavy and complex tasks.

---

# Key Findings

1. Structured prompts consistently produced better responses than naïve prompts.
2. Chain-of-Thought prompting achieved the highest depth and reasoning quality.
3. Few-Shot prompting was effective for format-sensitive tasks such as summarization and creative writing.
4. Zero-Shot prompting improved accuracy when clear instructions and roles were provided.
5. Basic prompts worked adequately for simple factual questions but were less effective for complex tasks.

---

# Summary of Findings

The experiment demonstrated that prompt clarity is one of the most important factors affecting AI response quality. As prompt structure increased from basic prompting to chain-of-thought prompting, the responses became more accurate, detailed, and contextually relevant.

For simple tasks, basic prompts were sufficient. However, for analytical, reasoning-based, and creative tasks, advanced prompting techniques such as Few-Shot and Chain-of-Thought produced significantly superior outputs.

The study confirms that effective prompt engineering improves AI performance and helps generate high-quality responses from ChatGPT.

---




# OUTPUT:

[Comparative-Analysis-of-Prompting-Patterns.pdf.pdf](https://github.com/user-attachments/files/27769878/Comparative-Analysis-of-Prompting-Patterns.pdf.pdf)


# RESULT:
The prompt for the above said problem executed successfully
