# Type of prompts
- **Zero Shot Prompting** 
  - Prompts where no examples are given.
  - Pre-existing knowledge and training data are leverage point in it.
  - Fast and effective but can be biased
  - Best practice is to give clear and direct prompts.
  - Without exmaples model might misinterpret complex or nuances prompts.
- **Few Shot Prompting**
  - Prompts where some examples are presented.
  - The given examples are used as vectors for semantic search.
  - Overfitting is a challenge.
  - Best practice would be finetuning and monitoring
  - It allows model to generalise variations using multiple related exmaples.
- **One Shot Prompting**
  - Prompt where one single example is provided
  - It includes task instruction, one example and new input.
  - Sentiment analysis is an example
  - Best practice is to choose a represenative example.

# Chain of thought prompting
The technique that allows AI models to articulate their reasoning step by step as they solve a problem or answer some question is chain of thought prompting.

## Importance of chain of thought prompting
- It helps in improved problem solving
- Gives better transparency
- has enhanced accuracy
- Helpful in complex NLP tasks

# Zero shot CoT prompting
Zero shot CoT prompting helps in generalising unseen tasks with faster adaptation and increased flexibility.
  It is helpful in : 
  - Math problems
  - Natural language understanding
  - Decision Making
  - Scientific research

# Contextual Prompting
The technique where you give AI model with relevant backgroud information, specific instruction, tone and objectives in the prompt.
Layering context means feeding the AI detailed info progressively to enhance clarity and relevance.
## Steps for contextual prompting
- **Context defined** - Provide a summary of all the historical events leading to French Revolution
- **Tone specified** - Present the information in a formal and academic tone
- **Add specific instructions** - Focus on the economic factors and key figures involved
- **State the purpose** - The goal is to understand the causes of the French Revolution
- **Submit the prompt**
- **Review and refine**
Example : *Explain the process of photosynthesis using a simple and educational tone suitable for school children. Focus on the role of sunlight and chlorophyll. The goal is to help students understand how plants make food.*

# Role Based Prompting
Technique where you give explicit instructions to the AI model to assume a specific role, persona, or character in the responses.
## Steps of Role based prompting
- Role Selection
- Role Introduction
- Context Provision
- Task Presentation
- Response Generation
- Iteration and refinement
## Examples 
- You are a math tutor explaining algebra to a 10-year-old. Make it simple and engaging.
- Imagine you are a financial advisor. Explain mutual funds to a beginner.
## Best practices
- Define the role clearly
- Provinding contexts
- Adding Constraints
- Iterate and refine
- Avoiding sterotypes

# ReAct prompting
Reasoning + Acting prompting is a technique that helps AI models in solving problems.
It helps in thinking 
- Thinking through the problem (reasoning)
- Taking actions through the acting (acting)
Traditional models both are seperate so combining them bring the ability of AI to real time thinking and taking action.
The output comes out to be with more reason.

# Self consistency prompting
This teachnique asks AI to come up with multiple answers and then pick the best one. This helps in increasing it's performance, accuracy and reliability.
  This method generates multiple asnwers and select the one with most consistenfcy amongst all.
## Benefits of Self consistency prompting
- Better Accuracy of answers
- Reduced bias into the reasoning
- It is more reliable 
- It is more proficeint in complex tasks
- It has more roubstness in the uncertain situations
## Application of prompting
- Maths Problems
- Commonsense questions
- Logical Reasoning
- Scientific research
- Natural Language Understanding.

# Retrieval Augmented Prompting
It is the technique that allows Ai models to increase the output capability by accesing external information. This makes responses more accurate and relevant when tasks need up to date specialisation information. It works by : 
- Retrieving External Information
- Combining that data with internal reasoning
It is extensively used in Healthcare, Legal Research, Customer Support and Education.
## Benefits of Retrieval Augmented Prompting
- Accessing the Real time info
- Enhanced knowledge base
- Icreased accuracy in responses
- Flexibility in problem solving
## Challenges to RAP
- Data Reliability 
- Computational Overload
- Dependence on External Source

# Tree of Thought Prompting
Technique for LLMs that structires reasoning process as a branching tree, enabling the model to explore, evaluate and refine multiple path in parallel.
## Core principles of ToT prompting
- Branching Reasoning Structure
- Exploration and Backtracking
- Evaluation and Pruning
## Applications of Tot Prompting
- Mathematical reasoning and puzzles
- Creative writing and planning
- Strategic decision making

# Prompt Injection in LLM
The technique of adding input in the prompt to produce harmful or unintentded outputs.

## Types of Prompt Injections
- **Direct** - Attackers are themselves adding malicious prompt.
- **Indirect** - Attackers are manipulating the external context to interpret malicious prompt thereafter
- **Social Engineering** - Attackers manipulate users into adding malicious prompts
- **Contextual** - Attackers influence the context early in the conversation. 

# Debiasing
The technique to ensure that the data in the output is not unethically biased.
- Exemplar - giving equal examples
- Instruction - giving explicit guidance
- Prefix  - giving the unbiased instruction in prefix
- Role - Giving the unbiased role
- Self refinement - self review and debiasing
- DebiasPi - Interference time debiasing method