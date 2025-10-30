## ChatGPT Prompt Engineering for Developers

A collection of Jupyter notebooks demonstrating practical prompt engineering patterns with chat-oriented LLMs. Each notebook focuses on a core capability and includes runnable examples.

### Contents
- **1. basic_guidelines.ipynb**: Core prompting principles (clarity, instruction hierarchy, constraints, and iteration).
- **2. iterative_prompt.ipynb**: Iterative refinement workflows (critiquing, self-editing, stepwise improvement of prompts/outputs).
- **3. summarizing.ipynb**: Summarization prompts (bullet, headline, focused, instruction-driven and constraint-aware summaries).
- **4. inferring.ipynb**: Inference tasks (classification, sentiment, topic, intent, and extracting structured fields).
- **5. Transforming.ipynb**: Text transformations (translation, tone/style rewriting, format conversion, regex-like extraction via prompts).
- **6. expanding.ipynb**: Expansion techniques (brainstorming, generating options, elaboration with style/voice controls).
- **7. chatbot.ipynb**: Chat format basics and an OrderBot demo using a system prompt and a small Panel UI to collect and display turns.

### Notable demo: OrderBot (in `chatbot.ipynb`)
- Uses a `system` message to define the role, flow, and menu.
- Collects user input and model replies with `get_completion_from_messages(...)`.
- Renders a minimal UI with `panel` widgets (`TextInput`, `Button`) and displays turns.
- Includes a follow-up prompt to generate a JSON summary of the order.
