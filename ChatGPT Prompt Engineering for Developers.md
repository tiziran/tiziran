

# ChatGPT

* introduction 
	* two model
		* based llm
			* predict next word, based on text training data
		* instruction tuned llm
			* tries to follow instructions
			* fine-tune on instructions and good attempts at following those instructions
			* RLHF: reinforcement learning with human feedback
	* principles
		* 1: write clear and specific instructions
		* 2: give the model time to think
* guidelines
	* two model
		* based llm
			* predict next word, based on text training data
		* instruction tuned llm
			* tries to follow instructions
	* fine-tune on instructions and good attempts at following those instructions
		* RLHF: reinforcement learning with human feedback
	* principles
		* 1: write clear and specific instructions
			* Tactic 1: Use delimiters
				* Triple quotes: “””
				* Triple backticks: ``` ``` ```
				* Triple dashes: - - -
				* Angle brackets:  <>
				* XML tags: <tag› ‹/tag›
			* Tactic 2: ask for structured output HtML, JSON
			* Tactic 3: check whether conditions are satisfied check assumptions required to do the task
			* Tactic 4: few-shot prompting
			* give successful examples of completing tasks, then ask model to perform the task
		* 2: give the model time to think
			* Tactic1: specify the steps to complete a task
			step1:…
			step2:…
			…
			stepN:…			
			* Tactic2: instruct the model to work out its own solution before rushing to a conclusion 
	* model limitations
		* hallucination
		* reducing hallucinations: fist find relevant information, then answer question.
* iterative 
	* idea; implementation(code/data)[prompt];experimental result; error analysis
	* prompt guidelines
		* be clear and specific
		* analyze why result does not give desired output
		* refine the idea and the prompt
		* repeat
	* iterative process
		* try something
		* analyze where the result does not give what you want 
		* clarify instructions, give more time to think
		* refine prompts with a batch of examples
* summarizing
	* Identify the following items from the review text: 
		- Sentiment (positive or negative)
		- Is the reviewer expressing anger? (true or false)
		- Item purchased by reviewer
		- Company that made the item
* inferring
	* Determine whether each item in the following list of topics is a topic in the text below, which is delimited with triple backticks.
* transforming
	* proofread and correct this review. Make it more compelling. Ensure it follows APA style guide and targets an advanced reader. Output in markdown format.
* expanding 
	* You are a customer service AI assistant.
	* temperature
		* a. temperature=0 ; for tasks that require reliability, predictability
		* b. temperature=0.3 ; for tasks that require variety
		* b. temperature=0.7 ; for tasks that require high variety
* chatbot
	* messages	
		1. system	
		2. user	
		3. assistant
* conclusion
	* Principles
		- ﻿﻿Write clear and specific instructions
		- ﻿﻿Give the model time to "think"
	- ﻿﻿Iterative prompt development
	- ﻿﻿Capabilities: Summarizing, Inferring, Transforming, Expanding
	- build a chatbot