# essay-evaluate
This notebook presents an automated essay grading system implemented using LangGraph and an LLM model. The system evaluates essays based on four key criteria: relevance, grammar, structure, and depth of analysis.
Motivation:
Automated essay grading systems can significantly streamline the assessment process in educational settings, providing consistent and objective evaluations. This implementation aims to demonstrate how large language models and graph-based workflows can be combined to create a sophisticated grading system.

 Key Components:
1. State Graph: Defines the workflow of the grading process
2. LLM Model: Provides the underlying language understanding and analysis
3. Grading Functions: Separate functions for each evaluation criterion
4. Conditional Logic: Determines the flow of the grading process based on interim scores

 Method:
The system follows a step-by-step approach to grade essays:

1. Content Relevance: Assesses how well the essay addresses the given topic
2. Grammar Check: Evaluates the essay's language usage and grammatical correctness
3. Structure Analysis: Examines the organization and flow of ideas in the essay
4. Depth of Analysis: Gauges the level of critical thinking and insight presented

Each step is conditionally executed based on the scores from previous steps, allowing for early termination of low-quality essays. The final score is a weighted average of all individual component scores.

 Conclusion:
This notebook demonstrates a flexible and extensible approach to automated essay grading. By leveraging the power of large language models and a graph-based workflow, it offers a nuanced evaluation of essays that considers multiple aspects of writing quality. 
