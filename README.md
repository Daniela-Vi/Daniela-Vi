## #!/usr/bin/python
# -*- coding: utf-8 -*-


class DataAnalyst:

    def __init__(self):
        self.name = "Daniela"
        self.role = "Data Analyst"
        self.skills = [
            "Python", 
            "SQL", 
            "MySQL", 
            "Tableau", 
            "Power BI"
        ]
        self.expertise = [
            "Data Cleaning", 
            "ETL Processes", 
            "Business Analysis"
        ]
        self.focus = "Continuous improvement and innovation to optimize processes and generate key insights."

    def say_hi(self):
        print("Hi there 👋")
        print(f"I'm {self.name}, a {self.role} with a strong foundation in {', '.join(self.skills)}.")
        print("With experience in " + ", ".join(self.expertise) + ", I'm passionate about " + self.focus)
        print("\nFeel free to reach out if you'd like to collaborate on data-driven projects!")


me = DataAnalyst()
me.say_hi()
