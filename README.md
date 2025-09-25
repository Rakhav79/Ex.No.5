

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
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

Step 1: Define Prompt Types

Naïve Prompt → Short, vague, or underspecified. Leaves interpretation up to the AI.

Basic Prompt → Clear, detailed, and structured. Provides specific instructions, context, and desired output format.

Step 2: Test Scenarios

-Creative Story Generation

-Factual Question Answering

-Summarization

-Advice/Recommendations

| **Scenario**          | **Naïve Prompt**                | **Naïve Response**                          | **Basic Response**                                          | **Basic Prompt**                                                                                                                                                                                                                                                                               
| **1. Creative Story** | "Write a story about a dragon." | A short generic story about a dragon       | "Write a 300-word fantasy story about a lonely dragon who    | A detailed, emotional story with dialogue                                                                    fighting a knight.                          secretly wants friendship instead of treasure.                 between dragon and human, exploring loneliness                                                                                                            Include emotional depth, dialogue, and a hopeful ending."      and ending with friendship.
                                                                                                                                                                                                                         
| **2. Factual Q\&A**   | "Who was Albert Einstein?"      | A short paragraph: "He was a famous        | "Give a detailed but concise 3–4 sentence explanation of who |Clear summary: mentions relativity, Nobel Prize                                                              physicist who developed the theory of         AlbertEinstein was, focusing on his key scientific            for photoelectric effect, contributions to                                                                   relativity."                                  contributions, his Nobel Prize, and his impact on             modern physics.
                                                                                                         physics."
																									   
| **3. Summarization**  | "Summarize climate change."     | A vague overview: "Climate change is       | "Summarize climate change in 5 bullet points covering causes |Well structured bullet list: covers greenhouse
                                                            caused by human activity and affects the     impact, evidence, global response and urgency."               gases, extrme weather, scientific evidence,
															planet."                                                                                                   international agreements, urgency.
															
| **4. Advice**         | "Give me tips for studying."    | A generic list:"Make a schedule, take      |"Give 5 specific and practical study strategies for a college |Detailed list:time-blocking with example
                                                           breaks, review notes."                       student preparing for final exams, with examples of how to     schedule, active recall with flashcards,
														                                                apply each."                                                   Pomodoro method with timers, group study
                                                                                                                                                                       with peer teaching using spaced repetition
                                                                                                                                                                       apps.

Step 4: Evaluation
| **Criteria** | **Naïve Prompts**                                                      | **Basic Prompts**                                           |
| ------------ | ---------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Quality**  | Often short, generic, lacking richness.                                | Longer, richer, and tailored to task.                       |
| **Accuracy** | Sometimes oversimplified, misses key details (e.g., Einstein’s Nobel). | More precise and complete because instructions guide focus. |
| **Depth**    | Shallow responses without nuance or structure.                         | More thoughtful, structured, and practical.                 |

-Overall Insights:-

Clarity boosts performance: The more guidance the prompt provides, the better ChatGPT aligns with user expectations.

Naïve prompts suffice for quick/simple answers: When detail isn’t necessary (e.g., a fast Einstein definition), a naïve prompt is “good enough.”

Complex tasks demand structured prompts: Creative writing, summarization, and advice showed the biggest improvements with clear instructions.

Best practice: Use instruction + context + format requirements to maximize ChatGPT’s quality, accuracy, and depth.
Step 5: Analysis

Clarity boosts performance: In every scenario, the basic prompt led to better quality, accuracy, and depth.

Naïve prompts work fine for simple needs: e.g., if someone just wants a quick answer about Einstein, the naïve prompt suffices.

Complexity benefits from structure: Summarization and creative writing especially showed big improvements when prompts were structured.

Instruction granularity matters: Adding format requirements (bullet points, word count, examples) consistently improved usability.

Step 6: Summary & Insights

-Naïve prompts → Fast, but risk generic or shallow responses.

-Basic prompts → Provide richer, more accurate, and contextually relevant outputs.

-Best practice: Use structured prompts with explicit instructions on content, format, and scope.

Tip: Even one extra detail (e.g., “in 5 bullet points”) can significantly improve results.

-Summary of Findings:-

Naïve prompts (short, vague, underspecified) often lead to generic, shallow, or incomplete answers.

Example: “Summarize climate change” → one vague sentence.

Basic prompts (clear, detailed, and structured) consistently produce higher-quality, more accurate, and deeper responses.

Example: “Summarize climate change in 5 bullet points covering causes, impacts, evidence, global response, and urgency” → well-organized, nuanced output.

-Impact by Dimension:

Quality: Improved storytelling, organization, and creativity when more context/structure is provided.

Accuracy: Directs the model to include key facts (e.g., Einstein’s Nobel Prize) that naïve prompts often miss.

Depth: Prompts specifying format (e.g., lists, examples, perspectives) consistently yield richer, more actionable content.

When naïve prompts work:

Simple Q&A or quick facts (e.g., “Who was Albert Einstein?”) where users need brevity.

Situations where users want spontaneous or unpredictable output.

When structured prompts matter most:

Complex tasks (summarization, storytelling, advice).

When accuracy, completeness, and usability are priorities.

💡 Insights for Optimal Prompting

To maximize ChatGPT’s performance:

✅ Be specific about the task – clearly state what you want (e.g., summary, explanation, story, list, comparison).
✅ Provide context – mention the perspective, style, or focus (e.g., “as advice for a college student” or “with emotional depth”).
✅ Set constraints – length, word count, number of bullet points, examples, or format requirements.
✅ Guide tone and purpose – e.g., “hopeful ending,” “professional tone,” “simple language.”
✅ Iterate – refine prompts if results are too broad or shallow.

🎯 Final Takeaway

Prompt clarity is the difference between “okay” and “excellent” outputs.
Naïve prompts are fine for quick answers, but structured, context-rich prompts consistently deliver higher quality, accuracy, and depth—making them the best choice for most real-world tasks.
# OUTPUT

# RESULT: The prompt for the above said problem executed successfully
