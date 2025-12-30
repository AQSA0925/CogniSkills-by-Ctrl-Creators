CogniSkills: Development Strategy & MVP Scoping
Project ID: HackXios-2K25-EdTech-04

1. Objective
Bridge the "Feedback Vacuum" by providing students with an automated Competency Matrix Matcher.

2. Core Sprints
- Sprint A (Data Ingestion): Implement Multer for PDF handling and pdf-parse for raw text extraction.
- Sprint B (AI Engine): Integrate Groq SDK for near-zero latency LLM inference using Llama 3.1.
- Sprint C (Roadmap Logic): Develop the "72-Hour Skill Sprint" generation algorithm to convert gaps into tasks.

3. Critical Success Factors
- Inference speed must be < 5 seconds via Groq LPUs.
- Semantic matching must identify technical context, not just keywords.