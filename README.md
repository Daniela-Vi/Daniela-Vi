![data]([ruta/a/la/imagen.jpg](https://img.freepik.com/vector-gratis/analisis-rendimiento-empresarial-graficos_53876-59914.jpg?t=st=1730672555~exp=1730676155~hmac=dbbf08cd638044ab1fd7e9bcd60d7b7b8db048586db271106e5c639aceef49e4&w=740))

!/usr/bin/python
-*- coding: utf-8 -*-

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
