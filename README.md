### Hello, I am Romain 👋

🎓 Currently pursuing a **M.S. in Computer Science and Engineering** at __Seoul National University__ (서울대학교)

🔬 Research Interests:
My goal is to improve the efficiency and performance of language models without retraining or fine-tuning.

- LLM Optimization
- Information Retrieval
    
🏛️ Lab: Language and Data Intelligence Laboratory ([ldi.snu.ac.kr](https://ldi.snu.ac.kr))

[![website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Brave&logoColor=white&link=https://rstr.fr/)](https://rstr.fr/)
![](https://visitor-badge.glitch.me/badge?page_id=romsto.romsto)
[![Linkedin: romain-storaï](https://img.shields.io/badge/-Romain-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/romain-storaï/)](https://www.linkedin.com/in/romain-storaï/)

```java
class Romain extends Student {
    
    final String username;
    String location;
    String[] skills;
    
    Romain() {
        username = "Romain";
        //location = "France";
        location = "South Korea";
        skills = {"Large Language Models", "Machine/Deep Learning", "Software Engineering"};
    }
    
    Education[] getEducation() {
        Education[] myEducation = new Education[2];

        myEducation[0] = new EducationBuilder().degree(Degree.MASTER_OF_ENGINEERING)
                                                .university("IMT Mines Alès")
                                                .subjects("Computer Science", "AI", "General Engineering")
                                                .build();

        // Currently attending
        myEducation[1] = new EducationBuilder().degree(Degree.MASTER_OF_SCIENCE)
                                                .university("Seoul National University")
                                                .subjects("AI", "Deep Learning", "Natural Language Processing", "LLM")
                                                .build();

        return myEducation;
    }
    
    String[] getGoals() {
        return {"Feed my curiosity", "Contribute to humanity", "Accelerate & Improve LLMs"};
    }
    
    String getContact() {
        return "romsto@snu.ac.kr";
    }
}
```
