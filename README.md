### Hello, I am Romain 👋

🎓 Currently pursuing a **M.S. in Computer Science and Engineering** at __Seoul National University__ (서울대학교)

🔬 _Research Interests_:
My goal is to improve the efficiency and performance of language models without retraining or fine-tuning.

- LLM Decoding
- LLM Optimization
- Information Retrieval
    
🏛️ _Lab_: Language and Data Intelligence Laboratory ([ldi.snu.ac.kr](https://ldi.snu.ac.kr)), under the supervision of Prof. Hwang (황 교수님).

[![Website](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Brave&logoColor=white&link=https://rstr.fr/)](https://rstr.fr/)
[![Linkedin: romain-storaï](https://img.shields.io/badge/-Romain-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/romain-storaï/)](https://www.linkedin.com/in/romain-storaï/)
![Stars](https://img.shields.io/github/stars/romsto)

```java
class Romain extends Student {
    
    final String username;
    String location;
    String[] skills;
    
    Romain() {
        username = "romsto";
        location = "South Korea"; // "France"
        skills = {"Large Language Models", "Deep Learning", "Software Engineering"};
    }
    
    Education[] getEducation() {
        Education[] myEducation = new Education[2];

        // Currently attending
        myEducation[1] = new EducationBuilder().degree(Degree.MASTER_OF_SCIENCE)
                                                .university("Seoul National University")
                                                .subjects("AI", "Natural Language Processing", "LLM", "Transformers")
                                                .attending();

        myEducation[0] = new EducationBuilder().degree(Degree.MASTER_OF_ENGINEERING)
                                                .university("IMT Mines Alès")
                                                .subjects("Computer Science", "AI", "General Engineering")
                                                .finished();

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
