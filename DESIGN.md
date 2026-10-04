1. Which corpus, and how big? 
The corpus is 'nf-core pipelines' (https://nf-co.re/pipelines). It has around 150 pipelines.

2. What does a real query look like?
The researchers and Data Scientists use chat UI to provide their prompts to search the tools and pipelines. Example prompt would look like this: "I want to compare quality of multiple genomes along with their annotations. Get me suitable tool or pipeline for this work"

3. What exactly comes back?
Suggest one best suited pipeline or tool and also provide two more alternatives. The result should include why it suggested that particular pipeline/tool, how it's better compared to it's alternatives, source of usage document for that pipeline/tool, key parameters for that pipeline, limitations if any.

4. What happens when nothing fits? 
Then it should say something like "no suitable pipeline/tool found in nf core pipeline database" and it should suggest some relevant pipeline/tool from web search. But it should mention to the user that it suggested from web search and provide it's source.

