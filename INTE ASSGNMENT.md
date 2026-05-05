Part A:
1.	The idea of a one-person business
A one-person business is one that is owned and run by a single person, who is in complete control of all business decisions and operations.

This kind of business is supported by digital systems by:
• Automating processes like marketing and bookkeeping
• Encouraging consumer communication
• Planning business operations and workflow

One person can effectively handle several tasks by using Digital Agents, negating the need for additional staff.

2.	A One-Person Company's Architecture

The following elements make up the system:

Owner/Founder
• The primary decision-maker
• Assigns work and keeps track of outcomes

Agents on the Internet
• Programs with intelligence that carry out particular jobs
• A financial agent and a marketing agent are two examples.

Tasks related to business
• Tasks necessary to manage the company, like:
• Customer support
• Promotion
• Management of orders

System Elements
• User Interface: The means by which the user communicates with the system
• Database: Holds all business-related data
• Processing System: Manages and carries out duties








3.	Multi-Agent Systems' Function

A system with several agents cooperating is called a multi-agent system.

Every agent plays a distinct role:
• Financial Agent: Oversees money
• Marketing Agent: Handles promotion and advertising
• Operations Agent: Manages business procedures

Advantages consist of:
• Lessening the founder's workload
• Improving operational speed and efficiency
• Making wise suggestions

4.	From the standpoint of programming (Object-Oriented Programming)

Object-Oriented Programming (OOP) can be used to represent the system:
• Class Founder: Stands in for the proprietor of the company
• Class Agent: Digital agents are represented by this
• Class Task: This stands for business duties.

Important ideas employed:
• Encapsulation: Every object has its own methods and data.
• Inheritance: A base class is the source of an agent.
• Polymorphism: Every agent manages tasks in a unique manner.


 
Part B-Business idea & project proposal
Business name:
SmartStudy Tutor (Smart Educational Service)
Business Background:
SmartStudy Tutor is a new online education platform for students who want to excel in school with easy and engaging learning. It teaches lessons in important subjects like programming and mathematics, which many students find difficult.
This is the business that aims to make learning more affordable, flexible, and impactful. Students can use this platform to revisit lessons, practice concepts, and get instant help instead of solely depending on old teaching approaches in the classroom. It [the system] provides explanations, walkthroughs and engaging material that supports comprehension.
Also, SmartStudy Tutor can save the time of students by presenting them with quick answers and well-arranged materials. It can further be enhanced using digital technologies and intelligent systems, a solution appropriate for today’s education.
Target Customers:
SmartStudy Tutor is targeted at many kinds of learners:
School students who require additional assistance in their subjects
Renaissance students who need assistance with difficult subjects
You are any beginner who wants to learn programming from scratch
The platform offers flexible learning schedules and easy-to-understand content for these groups.
How One Person Can Manage Business:
As it only works based on digital, therefore one person can run this business successfully. The system handles all this online, whether it be the delivery mechanism for lessons, or setting things up in a content management system (CMS) or interacting with customers.
Furthermore, deployment of digital agents is a work saver for the Founder. Autotask handled automatically and at the same time each agent is responsible for a specific function No large team of employees are required.
Similarly, tools like automation and intelligent systems make way in the structuring of work, data analysis and recommendations. The Founder will thus only have to decide without being involved in the day-to-day operation of processes.


Proposed Agents
🔹 Financial Agent
Duties will include handling all financial operations like tracking revenue and expenses, as well as reporting on the results to help the Founder with decision-making.
🔹 Marketing Agent
Duties will include advertising and promoting the platform using analysis of current trends to determine the best methods of attracting additional students to the platform and increasing student engagement with the platform.
🔹 Customer Service Agent
Duties will include communicating with customers through inbound phone calls and/or emails or chats, in order to answer questions, provide assistance and/or resolution of problems, to help ensure that the customer experiences.
🔹 Operations Agent
Duties will include managing operational duties on a day-to-day basis such as scheduling lessons, updating content and ensuring that the system is running effectively.
Example Interaction
In this example, the Founder could ask:
"What would be the best subject to promote next week?"
The Marketing Agent would review current trends in the industry for what subjects to suggest based on the best option. The Financial Agent would review the previous months' financial statements and advise the Marketing Agent as to what the most profitable subject would be to promote to students. The system would then produce a recommended course of action for the Founder based on the analysis done by both agents.
After this, the Founder would evaluate both subjects and determine which one to promote





Part C - System Planning & Design.
1) System architecture 
In the case of the SmartStudy Tutor System, it is conceived as a multi-agent system where one person, the Founder, is responsible for the whole operation, but with help from digital intelligent agents
In this structure, the founder assumes the role of the leader who assigns tasks according to business requirements. The assigned tasks are allocated among various agents, where each agent deals with certain tasks.
For instance, if the Founder wants to choose what course should be promoted next, then a task will be generated and assigned to the Marketing Agent and Financial Agent. The Marketing Agent examines the student’s preferences and trends in topics, whereas the Financial Agent looks at the courses that earn the most money.
All agents solve the problem individually and give a solution. All the solutions that have been given are gathered by the system and then shown to the Founder.
In conclusion, the Founder examines all the suggestions made and finally makes the decision.
This helps to ensure that there is effective distribution of work, lessens human effort, and enhances decision making through data-driven recommendations of different agents 
2) Multi-agent Structure 
Marketing Agent-
Tasks involved: Studying students' preference patterns and trends in the market
Nature of work done: Suggesting courses that are popular and in trend
Data used: Behavior pattern of students, course popularity, learning trends.

- Financial Agent
Duties: Financial performance analysis of courses
Types of activities done: Determination of profitable courses and pricing approaches
Information involved: Income figures, sales figures, cost information



Learning Agent- 
Role: Enhance the learning process of the student
Tasks: Recommending customized learning paths for the student
Data Processed: Performance and progress information
Recommendation Agent
Role: Aggregate information from various agents
Types of tasks performed: Make recommendations
Kind of information used: Information provided by all the agents

3) System Classes.
Classes within the model are as follow: 
-Company: Symbolizes the whole company responsible for running the system
-Founder: Has control over the system, assigns tasks, and makes the last decision
-Agent: Symbolizes smart agents which do some particular task
-Task: Symbolizes a particular task assigned by the Founder to agents
-Memory: Symbolizes old data, interaction, and output
-KnowledgeBase: Symbolizes structured knowledge used by agents for analysis
- Recommendation/Report: Symbolizes output produced by agents

4) UML class Diagram.
Relationships Description:
-Founder → assigns → Task
Task → done by → Agent-
Agent → utilizes → KnowledgeBase-
Agent → utilizes → Memory-
Agent → generates → Recommendation-
Founder → evaluates → Recommendation-












Part D – System Implementation
The SmartStudy Tutor system is built using Python. The idea of the system is that the Founder works with different digital agents to help make a smart business decision about what subject to promote.
System Components:
The system has two main parts: the Founder and the Agents.
•	Founder Class:
The Founder is like the manager of the system. It asks a question, collects answers from all agents, and then makes the final decision. In this system, the Founder asks: “What subject should we promote next week?” 
•	Agent Class:
This is the main (base) class. All other agents come from it. Each agent has a role, and each one processes the task in its own way. 
•	Agents in the system:
There are several agents, and each one gives a different type of feedback: 
o	MarketingAgent: looks at trends and says Python is popular. 
o	FinancialAgent: checks profit and says Python makes good money. 
o	CustomerServiceAgent: shows customer demand (many requests for Python). 
o	OperationsAgent: confirms the system is ready. 
o	LearningAgent: shows that students learn Python faster. 
o	RecommendationAgent: looks at all results and gives a final suggestion. 
System Workflow:
First, the Founder asks a question about what subject to promote.
Then, this question is sent to all agents.
Each agent processes the question and gives its own response.
After collecting all the responses, the Recommendation Agent gives a final suggestion.
Finally, the Founder reviews everything and decides to promote Python Programming.
OOP Concepts Used:
•	Encapsulation: Each class has its own data and methods. 
•	Inheritance: All agents are based on the main Agent class. 
•	Polymorphism: Each agent has its own version of the process() method, so they give different answers.
