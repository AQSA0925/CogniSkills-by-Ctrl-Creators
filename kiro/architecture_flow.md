CogniSkills: The Intelligence Pipeline Architecture

System Flow (Logic Visualization)
[Frontend: React/Vercel] 
    |-- (POST multipart/form-data) --> 
[Backend: Node/Express/Render]
    |-- (pdf-parse) --> [Sanitized Resume String]
    |-- (Prompt Engineering) --> [Context-Aware Payload]
    |-- (Groq API) --> [Llama 3.1 Inference Engine]
    |-- (JSON Parser) --> [Structured Skill Matrix]
    |-- (Response) --> 
[Frontend: Dynamic Dashboard Rendering]

Latency Optimization
To ensure a high-performance UX, we bypassed standard cloud providers for the AI layer and utilized Groq’s deterministic compute LPUs.