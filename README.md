# CRISPR-GPT Tracker

## Welcome, internal test user!

Thank you for helping us test the performance of our CRISPR-GPT, a LLM agent with CRISPR expertise that we hope would aid and accelerate the scientific discovery in biology and medicine. 

By closely working with LLM/ML experts (including Dr. Denny Zhou from Google Deepmind), we hope the agent could interact with users and provide task-specific information and needs. The tool we are building is not only an integration of CRISPR knowledge and tools but also serves as an “assistant” that provides reasoning/suggestions based on the user's response and its knowledge base. We envision the tool could be beneficial to the biological research community. It can provide quick, detailed and barrier-free instructions/information/resources on CRISPR-based genome engineering to biology researchers with limited prior knowledge in CRISPR and limited resources to CRISPR experts. Even for people who have reasonable knowledge on CRISPR, it can provide a one-stop easy and quick interface to help them design sgRNA/primers, select delivery methods, etc.

Our CRISPR-GPT currently has three modes: 

1. Meta-Task mode, which integrates predesigned meta-task pipelines that could guide the user through the entire process of one type of CRISPR editing. This mode fits best for new CRISPR users to get started with their experimental design.

2. Fully Automated mode, where users could input a sentence or short paragraph describing the specific use case or requests. This mode fits better for more experienced users looking for specific information.

3. Q and A mode, where users could ask CRISPR-related questions and our agent would generate answers based on both latest collections of CRISPR literatures and Chat-GPT4 knowledge base.

In this round of internal testing, we are hoping to evaluate the performance of our CRISPR-GPT agent and compare that to the general LLM agent like Chat-GPT. We would like you, an expert in the CRISPR field, to evaluate the performance of CRISPR-GPT by scoring each task (using the Rubics below) on how it performs for you, and record the questions/task prompt and the corresponding response (we are supplying a separate table so you could directly input your score and send to Jerry: yhqu@stanford.edu).

We sincerely appreciate your contribution in the development of CRISPR-GPT.

On behalf of the CRISPR-GPT team, 
Le Cong Lab, Stanford: Yuanhao Qu, Le Cong
Mengdi Wang Lab, Princeton: Kaixuan Huang, Mengdi Wang


## Instructions

Please login to the CRISPR-GPT through: https://crispr-gpt.com/ \
Account: test \
Passcode: 1qw2

We kindly ask you to perform testing of:

1 Meta-Task
5 Automated tasks
5 Q&A mode questions.

You are welcome to perform additional testing and include additional comments. We have separately included the rubrics and template for evaluation. Detailed instruction for each type of testing is included below:


### 1.	For Meta-Task:

For the Meta-task, please think of yourself as a researcher new to CRISPR experiment and hope to achieve a specific task.

We currently have four Meta-Task in total, which are:

(a)	Generating a Knockout Using CRISPR.
(b)	CRISPR Base Editing Without Double-Strand Breaks.
(c)	Generating Small Insertion/deletion/base editing through Prime Editing.
(d)	Activation or Repression of Target Genes Using CRISPR.

You can enter the meta-task by entering the number in the text box and press enter.

For each Meta-Task, it is associated with a number of steps, for example: Meta-task 1: Generating a Knockout Using CRISPR is associated with 4 subtasks:

1.	Cas system selection
2.	Delivery approach selection
3.	guideRNA design
4.	Experimental validation

Please help us score each of the steps separately and score the Meta-task as a whole.

Please also score the corresponding GPT 3.5 responses using a similar prompt. For example, for Meta-task 1, step 1, you can ask GPT 3.5 like “Please help me select a Cas system for generating a CRISPR knockout.” When evaluating the Meta-task 1 as a whole, you can ask GPT 3.5 like “Please help me generate a knockout using CRISPR.”

### 2.	For automated tasks:

For the automated tasks: You can generate the questions based on exact information you need for your experiment.

For example, you can ask questions like “I am trying to knock out the TGFBR1 gene in my A549 human lung cancer cell line. Could you help me design the sgRNA and NGS primers?”

Or you can ask “I am hoping to use CRISPRa to activate EGFR expression in human iPSC cells, which delivery method I should use?”


### 3.	For Q&A mode questions

For the Q&A mode, you can ask any questions related to CRISPR including latest CRISPR technologies like Cas12f or clinical CRISPR applications or the procedure to perform certain experiments or the mechanisms of CRISPR. 




## RUBRICS
#### Accuracy
●	1 (Poor): The answer contains multiple factual errors or shows a misunderstanding of CRISPR technology. \
●	2 (Fair): The answer has some correct elements but also includes significant inaccuracies that could lead to flawed experimental design if followed. \
●	3 (Average): The answer is mostly accurate but may contain minor errors or oversights. \
●	4 (Good): The answer is accurate, with only negligible errors that do not impact the overall validity of the information provided. \
●	5 (Excellent): The answer is completely accurate, reflecting the current state of CRISPR research and methodologies.
#### Reasoning
●	1 (Poor): The reasoning behind the answer is flawed or nonexistent; the logic is unclear or incorrect. \
●	2 (Fair): The answer provides a rationale, but it is weak and may not support the conclusion or design effectively. \
●	3 (Average): The answer's reasoning is solid for the most part, with some areas that could be better supported or explained. \
●	4 (Good): The answer provides strong reasoning with clear and logical support for all claims and suggestions made. \
●	5 (Excellent): The answer's reasoning is exceptional, providing insightful, well-supported explanations that enhance understanding of CRISPR designs.
#### Completeness
●	1 (Poor): The answer is incomplete and lacks critical information required to form a complete understanding or action plan.\
●	2 (Fair): The answer covers some necessary points but omits several important aspects that would be needed for a thorough CRISPR design.\
●	3 (Average): The answer is fairly comprehensive but could be improved with additional details or coverage of more nuanced aspects of the design.\
●	4 (Good): The answer is thorough, covering nearly all aspects required for a complete understanding and successful experimental setup.\
●	5 (Excellent): The answer is entirely comprehensive, leaving no question unanswered and providing a full suite of information needed for CRISPR experimental design.
#### Conciseness
●	1 (Poor): The answer is overly verbose and contains much irrelevant information, making it difficult to extract useful insights.\
●	2 (Fair): The answer is longer than necessary with some extraneous content but still delivers a fair amount of relevant information.\
●	3 (Average): The answer conveys the necessary information with some unnecessary detail but remains clear and understandable.\
●	4 (Good): The answer is concise, with well-organized content that is directly relevant to the question asked, without any unnecessary information.\
●	5 (Excellent): The answer is exceptionally concise, communicating the required information efficiently and effectively without any superflity.

