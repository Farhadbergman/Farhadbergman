- 👋 Hi, I’m Farhad Ramezani 
- 👀 I’m interested in Business Management, Mahine learning business analysis
- Systems Engineering
- 🌱 I’m currently learning Model-Based Systems Engineering
Advanced Manufacturing Processes
I’m looking to collaborate on Business Management and customer analysis and business analysis
-  Systems Engineering innovations
 ## Let's Connect:📫 
- Email: (imfarhadbergman@gmail.com)
- LinkedIn: [Connect](https://www.linkedin.com/in/farhad-ramezani-b648472a5?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
<!--
Farhadbergman/Farhadbergman is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
class FarhadRamazani:
    def __init__(self):
        self.name = "Farhad Ramazani"
        self.field = "Industrial Management"
        self.university = "University of Guilan"
        self.skills = ["Machine Learning", "Systems Engineering", "Business Management"]
        self.languages = {"Persian": "Native", "English": "IELTS 6.5", "Sorani Kurdish": "Fluent"}
        self.interests = ["Biomedical Engineering", "Chess (Elo 900)", "Manufacturing Processes"]
        self.github = "https://github.com/FarhadRamezani"
        self.linkedin = "https://www.linkedin.com/in/farhad-ramezani-b648472a5"

    def introduce(self):
        return f"Hi, I'm {self.name}! 🎓\n" \
               f"📍 Studying {self.field} at {self.university}\n" \
               f"🚀 Passionate about {', '.join(self.interests)}\n" \
               f"💡 Skilled in {', '.join(self.skills)}\n" \
               f"🌐 Languages: {', '.join([f'{lang} ({level})' for lang, level in self.languages.items()])}\n" \
               f"🔗 Connect with me on [GitHub]({self.github}) & [LinkedIn]({self.linkedin})"

if __name__ == "__main__":
    me = FarhadRamazani()
    print(me.introduce())
