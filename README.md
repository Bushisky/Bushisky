# Create the content for the README file
readme_content = """
# 👋 Hi, I’m George Bush Odhiambo

🌍 **Location:** Nairobi, Kenya  
💻 **Passionate about:** Health Informatics, OpenMRS, and EMR integrations  
📚 **Currently learning:** React, Flutter, FHIR  
🤝 **Looking to collaborate on:** Health-related systems, especially around EMR solutions and patient management systems  
🔗 **Reach me:** [LinkedIn](https://www.linkedin.com/in/george-bush-odhiambo/)

---

## 🛠️ Projects
- **Kenya EMR Afya EHMS Integration:** A Java-based integration of OpenMRS modules, tailored for Kenya's Ministry of Health needs.
- **Patient Queue App:** Streamlining patient management with a focus on ease of use for healthcare workers, built using Groovy.
- **Mama’s Hub Mobile and Web Interface Forms Development:** A current initiative involving mobile and web interface design for maternal health tracking.

## 📈 GitHub Stats
![Bushisky's GitHub stats](https://github-readme-stats.vercel.app/api?username=Bushisky&show_icons=true&theme=radical)

## 🚀 Skills
- Java | Python | React | Groovy | EMR | FHIR | OpenMRS

Feel free to connect or collaborate!
"""

# Write the content to a README.md file
readme_filename = "/mnt/data/README.md"
with open(readme_filename, "w") as file:
    file.write(readme_content)

readme_filename
