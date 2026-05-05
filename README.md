# INTE130-ASSIGNMENT-
class Founder:
    def __init__(self, name):
        self.name = name

    def create_task(self, question):
        print(f"Founder {self.name} asks: {question}")
        return question

    def make_decision(self, recommendations):
        print("\n--- Founder's Final Decision ---")
        for rec in recommendations:
            print(f" Reviewing: {rec}")
        print("\nFinal Decision: Promote 'Python Programming' next week!")


class Agent:
    def __init__(self, role):
        self.role = role

    def process(self, task):
        return f"{self.role}: Task '{task}' processed"


class MarketingAgent(Agent):
    def process(self, task):
        return "Marketing Agent: 'Python' is trending with students"


class FinancialAgent(Agent):
    def process(self, task):
        return "Financial Agent: 'Python' courses have 40% profit margin"


class CustomerServiceAgent(Agent):
    def process(self, task):
        return "Customer Service Agent: 120 requests for 'Python' this week"


class OperationsAgent(Agent):
    def process(self, task):
        return "Operations Agent: System ready for Python content"


class LearningAgent(Agent):
    def process(self, task):
        return "Learning Agent: Students complete Python 2x faster"


class RecommendationAgent(Agent):
    def process(self, task, reports):
        return "Recommendation Agent: Based on all data → promote Python"


boss = Founder("SmartStudy")

marketing = MarketingAgent("Marketing")
financial = FinancialAgent("Financial")
customer = CustomerServiceAgent("Customer Service")
operations = OperationsAgent("Operations")
learning = LearningAgent("Learning")

task = boss.create_task("What subject should we promote next week?")

recommendations = [
    marketing.process(task),
    financial.process(task),
    customer.process(task),
    operations.process(task),
    learning.process(task)
]

rec_agent = RecommendationAgent("Recommendation")
final_rec = rec_agent.process(task, recommendations)

boss.make_decision(recommendations + [final_rec])
