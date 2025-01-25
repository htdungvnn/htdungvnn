# Hi, I'm Hoang Tien Dung! 👋

## Summary

- 🎓 **Education**: Graduated in Software Engineering from Industrial University of Ho Chi Minh City (IUH), GPA: 3.2/4.
- 💼 **Current Role**: Full-Stack Developer at FPT Software with over 3 years of professional experience.
- 🌟 **Objective**: Eager to become an expert back-end developer, driving innovation and technological transformation.
- 🏆 **Awards**:
  - Innovation Award (AI Training Assistant) - 2022
  - Sao Khue Award (E-Commerce & Logistics) - 2022
  - Vietnam Technology Excellence Award - 2022
- 📫 **Contact**:
  - Email: [htdung.vnn@gmail.com](mailto:htdung.vnn@gmail.com)
  - LinkedIn: [linkedin.com/in/htdungvnn](https://www.linkedin.com/in/htdungvnn)
  - GitHub: [github.com/htdungvnn](https://github.com/htdungvnn)
  - Facebook: [facebook.com/htdung.vnn](https://www.facebook.com/htdung.vnn)

---

## Skills

- **Back-End**: ASP.NET, Node.js (Express.js)
- **Front-End**: Angular, React
- **Databases**: SQL, PostgreSQL, MongoDB, Redis, MySQL
- **Cloud Services**: AWS (EC2, S3)
- **DevOps**: Docker, Kubernetes, Jenkins, GitLab CI/CD
- **Messaging**: RabbitMQ, Kafka
- **Version Control**: Git (GitHub, GitLab, Azure Repos)
- **Task Management**: Jira, Odoo

---

## Skill Proficiency Spider Chart

![Skill Proficiency Spider Chart](Skill_Proficiency_Spider_Chart.png)
## Skill Proficiency Spider Chart

To generate the spider chart, you can use the following Python code:

```python
import numpy as np
import matplotlib.pyplot as plt

# Skills and proficiency levels
skills = ['ASP.NET', 'Node.js (Express.js)', 'Angular', 'React', 'SQL', 'PostgreSQL', 'MongoDB', 'Redis', 'RabbitMQ', 'Kafka', 'AWS', 'Docker & Kubernetes']
proficiency = [90, 75, 85, 80, 90, 85, 75, 70, 70, 65, 75, 80]

# Close the loop for radar chart data
values = proficiency + [proficiency[0]]
angles = np.linspace(0, 2 * np.pi, len(skills), endpoint=False).tolist()
angles += angles[:1]

# Create the radar chart
fig, ax = plt.subplots(figsize=(10, 10), subplot_kw=dict(polar=True))
fig.patch.set_facecolor('black')  # Set the figure background to black

# Plot the data
ax.fill(angles, values, color='limegreen', alpha=0.4)
ax.plot(angles, values, color='limegreen', linewidth=2)

# Set the category labels and ticks
ax.set_yticks([20, 40, 60, 80, 100])
ax.set_yticklabels(['20%', '40%', '60%', '80%', '100%'], color='white', fontsize=10)
ax.set_xticks(angles[:-1])
ax.set_xticklabels(skills, fontsize=12, color='white')

# Chart styling
ax.set_facecolor('black')  # Set the chart area background to black
ax.grid(color='limegreen', linestyle='--', linewidth=0.5, alpha=0.6)  # Green gridlines
ax.set_title('Skill Proficiency Spider Chart (Dark Mode)', fontsize=16, color='white', y=1.1)

plt.tight_layout()
plt.savefig('updated_skill_proficiency_spider_chart_dark.png', dpi=300)
plt.show()

---

## Experience Highlights

### FPT Software (2024 - Present)
- Full-Stack Developer for CQC project (Global Health Care - Integrated Management System).
- Technologies: Angular 17, ASP.NET 8.0, PostgreSQL, AWS, Kafka.

### ITL Corp (LogTechHub) (2021 - 2024)
- Full-Stack Developer for EFMS (Excellence Freight Management System).
- Migrated systems from ASP.NET Core 2.2 to 6.0 and Angular 9 to 15.

### NashTech (2021)
- Intern Developer for Equipment Management System.
- Technologies: ASP.NET MVC, ReactJS, SQL.

---

## Interests

- Learning new technologies and improving English proficiency.
- Reading books, listening to music, and playing badminton.

Feel free to connect for collaboration or knowledge sharing!

