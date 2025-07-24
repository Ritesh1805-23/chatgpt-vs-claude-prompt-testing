# chatgpt-vs-claude-prompt-testing
A comparative analysis of ChatGPT and Claude 3 on reasoning, summarization, and logic prompts.

# 🔍 Prompt Quality Testing: ChatGPT vs Claude

This project evaluates prompt responses across 5 core task types to assess output quality between **OpenAI’s ChatGPT** and **Anthropic’s Claude**.

---

## ✅ Test Categories

1. **Reasoning**  
2. **Summarization**  
3. **Information Extraction**  
4. **Formatting**  
5. **Logical Flow**

Each prompt was run on both models. Responses were analyzed and scored across:
- **Accuracy**
- **Clarity**
- **Structure**
- **Edge Case Handling**

---

## 📊 Final Verdict

| Task Type      | Claude Score | ChatGPT Score | Winner   |
|----------------|--------------|----------------|----------|
| Reasoning      | 10/10        | 10/10          | Tie      |
| Summarization  | 10/10        | 10/10          | Tie      |
| Extraction     | 10/10        | 10/10          | Tie      |
| Formatting     | 10/10        | 10/10          | Tie      |
| Logic          | 10/10        | 10/10          | Tie      |

Both models performed at the highest level of consistency and correctness for this test suite.

---

## 📁 Folder Structure

```bash
├── prompts/
│   ├── 01_reasoning.md
│   ├── 02_summarization.md
│   ├── 03_extraction.md
│   ├── 04_formatting.md
│   └── 05_logic.md
├── responses/
│   ├── chatgpt/
│   │   └── reasoning.txt (etc.)
│   └── claude/
│       └── reasoning.txt (etc.)
├── analysis/
│   └── comparison-notes.md
├── README.md

