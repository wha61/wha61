# Hi <img src="handwaving.gif" alt="DEMO" width="40" height="40" />, I'm Wen-Xiang He (Bruce)

*Computing Science Student* @ [Simon Fraser University](https://www.sfu.ca/)

## A little more about me...

```python
#!/usr/bin/python
# -*- coding: utf-8 -*-

class SoftwareDeveloper:

    def __init__(self):
        self.name = "Wenxiang He"
        self.role = ""
        self.skills = {
            "Full Stack Development" : ['HTML5/CSS/JavaScript', 'React', 'Angular', 'Umi', 'C#', 'Node.js', 'Express', 'ASP.NET', 'ABP', 'MySQL', 'SQL Server', 'MongoDB']
            "Android Mobile Development" : ['Java', 'Kotlin', 'Android SDK']
            "language" : ['Python', 'C++', 'C', 'Java', 'JavaScript', 'HTML', 'CSS', 'MySQL', 'SQL Server', 'Kotlin'],
            "framework" : ['React', 'Node.js', 'Angular', 'Bootstrap'],
            "tools" : ['VSCode', 'Visual Studio', 'AndroidStudio', 'Intellij IDEA', 'Git', 'Linux', 'Windows', 'Docker', ]
        }

    def say_hi(self):
        print("Thanks for dropping by, feel free to connect with me!")

    def working_on(self):
        print("Currently working on my project.")

    def introduction(self):
        self.say_hi()
        self.working_on()

me = ()
me.introduction()
