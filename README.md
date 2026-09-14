create a folder ComfyUI-AceStep15-LLMAuto in custom_nodes and extract ComfyUI-AceStep15-LLMAuto.zip contents into it. 


Something I forgot to change, is sampler_name in the KSampler node. Change it from lcm to euler for better outputs.

The system prompt for the auto lyrics (auto lyrics txt) tells the AI to aim for 230-33 words for a 120 second song, so changing the duration will give very different results.
