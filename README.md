### Hello, I am Romain 👋
#### Research Engineer @ Datadog (ex-[Adaptive ML](https://adaptive-ml.com)).

🎓 _Graduated with a dual degree_:\
**M.S.** in Computer Science and Engineering @ __Seoul National University__ (서울대학교).\
**M.Eng.** in Engineering and AI @ __IMT Mines Alès__.

🔬 _Research Interests_:  
LLMs, generally.

🏛️ _Previously at_: Language and Data Intelligence Lab ([ldi.snu.ac.kr](https://ldi.snu.ac.kr)) under Prof. Hwang (황 교수님).  

🌍 Based in **France** 🇫🇷

[![Website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Brave&logoColor=white&link=https://rstr.fr/)](https://rstr.fr/)
[![Linkedin: romain-storaï](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/romain-storaï/)](https://www.linkedin.com/in/romain-storaï/)
![Stars](https://img.shields.io/github/stars/romsto)

#### `$ cat romain.py`
```python
from entities.earth import Human


class Romain(Human):
    def __init__(self):
        super().__init__(name="Romain")
        self.role = "Research Engineer"
        self.education = [
            "M.S. @ Seoul National University 🇰🇷",
            "M.Eng. @ IMT Mines Alès 🇫🇷"
        ]
        self.attribute = Curious(level=math.inf)
        self.location = "France"  # South Korea
 
    def mode(self):
        return "🔬 Research | 🛠️ Engineering"  # Swiss Army knife mode activated

    def get_contact(self):
        return "romain.storai62+github@gmail.com"
```
