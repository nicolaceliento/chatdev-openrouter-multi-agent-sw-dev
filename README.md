
Pr il corretto funzionamento del notebook jupyter sono necessarie le seguenti librerie: 
    
    openai python-dotenv pyyaml ipywidgets git+https://github.com/OpenBMB/ChatDev.git "camel-ai[all]"

che possono essere instalalte mediante il comando:
    
    python -m pip install openai python-dotenv pyyaml ipywidgets git+https://github.com/OpenBMB/ChatDev.git "camel-ai[all]"

Inoltre, è necessario creare un file vars.env con le seguenty keys:
    
    OPENAI_API_BASE=https://openrouter.ai/api/v1 #url openrouter API
    OPENAI_API_KEY=sk-openrouter-api-key da creare su openrouter.ai