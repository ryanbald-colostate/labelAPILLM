# labelAPILLM
This program will utilize LLM to add domain and subdomain labels (json files found [here](https://github.com/RESHAPELab/ART-UI/tree/master/AST_Rock_Website)) to API names from [API_specific](https://github.com/fabiojavamarcos/parseAPIPath).

Use small_LLM to ensure every aspect is working properly and changes work as expected. LLM.ipynb will use roughly 250,000 tokens (mostly input tokens) and 20 minutes per 1,000 rows in order to give domain and subdomain labels.

Prompts should be updated with each new model and tested extensively in the free browser version of the LLM.
