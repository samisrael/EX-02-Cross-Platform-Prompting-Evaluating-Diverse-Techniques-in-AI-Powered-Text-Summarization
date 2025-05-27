# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

- **Accuracy**  
- **Coherence**  
- **Simplicity**  
- **Speed**  
- **User experience**  

---

## Algorithm

1. **Select AI platforms**: ChatGPT, Gemini, Claude, Copilot  
2. **Prepare the article**: A 500-word technical write-up titled *“The Basics of Blockchain Technology”*  
3. **Design prompts**:
   - **Zero-shot**: “Summarize this article.”
   - **Few-shot**: Provide 2 examples of technical-to-simple summaries followed by the article.
   - **Chain-of-thought**: Guide the AI step-by-step (e.g., "First, identify the main concept, then key components, then summarize in simple terms.")
   - **Role-based**: “You are a professor explaining this to undergrads. Summarize the article.”
4. **Run each prompt across all platforms.**
5. **Evaluate each result** based on the following criteria:
   - **Accuracy** (how well the summary reflects the core content)
   - **Coherence** (logical flow and structure)
   - **Simplicity** (easy to understand for undergraduates)
   - **Speed** (response time)
   - **User experience** (interface, formatting, usability)
6. **Score each combination** on a scale of 1–5 for each criterion.
7. **Record observations** in a result table.

---

## Result

| Platform | Prompt Type       | Accuracy | Coherence | Simplicity | Speed | User Experience | Total Score (out of 25) |
|----------|-------------------|----------|-----------|------------|-------|------------------|--------------------------|
| ChatGPT  | Zero-shot         | 4        | 4         | 4          | 5     | 5                | 22                       |
| ChatGPT  | Few-shot          | 5        | 5         | 5          | 4     | 5                | 24                       |
| ChatGPT  | Chain-of-thought  | 5        | 5         | 4          | 4     | 5                | 23                       |
| ChatGPT  | Role-based        | 5        | 4         | 5          | 4     | 5                | 23                       |
| Gemini   | Zero-shot         | 3        | 3         | 4          | 5     | 4                | 19                       |
| Gemini   | Few-shot          | 4        | 4         | 4          | 4     | 4                | 20                       |
| Gemini   | Chain-of-thought  | 4        | 4         | 4          | 4     | 4                | 20                       |
| Gemini   | Role-based        | 4        | 3         | 5          | 4     | 4                | 20                       |
| Claude   | Zero-shot         | 4        | 4         | 5          | 4     | 4                | 21                       |
| Claude   | Few-shot          | 5        | 5         | 5          | 4     | 5                | 24                       |
| Claude   | Chain-of-thought  | 5        | 5         | 4          | 4     | 5                | 23                       |
| Claude   | Role-based        | 5        | 4         | 5          | 4     | 5                | 23                       |
| Copilot  | Zero-shot         | 3        | 3         | 3          | 4     | 3                | 16                       |
| Copilot  | Few-shot          | 4        | 4         | 4          | 4     | 4                | 20                       |
| Copilot  | Chain-of-thought  | 4        | 3         | 4          | 4     | 4                | 19                       |
| Copilot  | Role-based        | 4        | 3         | 4          | 4     | 4                | 19                       |

**Conclusion**:  
Few-shot prompting on ChatGPT and Claude yielded the most balanced and high-quality summaries, especially in terms of accuracy, coherence, and simplicity. Zero-shot and chain-of-thought strategies performed well but were slightly less consistent across platforms. Copilot showed limitations in coherence and user experience, while Gemini provided solid but not standout performance.

---

