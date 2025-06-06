# Project-gen-AI
resume-enhancer/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
└── resume_prompt_generator.py



prompt = f"""
You are a professional resume writer.
Given the following information:
Name: {name}
Experience: {experience}
Skills: {skills}
Projects: {projects}

Create a professional summary and improve the job descriptions.
"""