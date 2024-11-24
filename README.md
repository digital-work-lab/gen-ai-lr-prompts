# GenAI Prompts for Literature Reviews

A curated repository of prompts specifically tailored for standalone review papers, designed to enhance the use of generative AI tools like ChatGPT in literature review processes.

> [!NOTE]  
> This repository highlights prompts that have been academically evaluated and/or passed peer review, ensuring rigor and reliability in their application to literature review tasks. It serves as a resource for researchers looking to integrate GenAI effectively while maintaining high methodological standards.

## Open for Continuous Updates

This is an open resource, designed for continuous updates and community contributions. Researchers, practitioners, and educators are encouraged to share new prompts, insights, and use cases to further develop this repository as a comprehensive guide for GenAI-enhanced literature reviews.

**A reference to our work/the authors will be included here**

**Overview**

- [Search](#search)

## Search

### Search query suggestion prompt

```
You are an information specialist who develops Boolean queries for systematic reviews.
You have extensive experience developing highly effective queries for searching the 
information systems literature. Your specialty is developing queries that retrieve as
few irrelevant documents as possible and retrieve all relevant documents for your
information needs. You are able to take an information need such as: “Review of IT 
Business Value” and generate valid Web of Science queries such as:

“TI=(IT OR IS OR …) AND TI=(value OR payoff OR …) AND TI=(firm OR business OR …)”.

Now you have your information need to conduct research on “The effect of LLM on 
individual performance at work”, please generate a highly effective systematic 
review Boolean query for the information need.
```

> **Response**
> 
> For the information need "The effect of LLM on individual performance at work," we can generate a Boolean query for Web of Science (or similar databases) using a combination of keywords and Boolean operators. Here is an effective query to retrieve relevant documents while minimizing irrelevant ones:
> 
> `TI=("Large Language Model*" OR "LLM" OR "GPT" OR "Generative Pretrained Transformer" OR "Transformer model*") AND TI=("individual performance" OR "employee performance" OR "work performance" OR "job performance" OR "productivity" OR "efficiency" OR "output") AND TI=("work" OR "job" OR "employment" OR "organization" OR "labor")`

Reference: Wang, S., Scells, H., Koopman, B., and Zuccon, G. 2023. “Can ChatGPT Write a Good Boolean Query for Systematic Review Literature Search?” in Proceedings of the 46th International ACM SIGIR Conference on Research and Development in Information Retrieval, pp. 1426–1436. (https://doi.org/10.1145/3539618.3591703).

## Further prompts will be added here...

...

## Contributing

### Guidelines

**Prompts**  
- Prompts reported in published and peer-reviewed papers only.  
- If a prompt has been used in practice (e.g., to assist in specific review tasks), briefly describe the use case and its outcomes.  
- Indicate any limitations or specific requirements for the prompt to work effectively (e.g., tools needed, data formats).
- Prompts from influential preprints may also be considered, provided their effectiveness has been clearly demonstrated.
- Contributions should include information on how the prompt was evaluated (e.g., in academic papers, systematic reviews, or practical use cases).  
- If applicable, include links to resources showcasing the evaluation process or results.

### Adding a New Prompt

If you would like to add a new prompt, follow these steps:  

1. Click the [edit button](https://github.com/digital-work-lab/gen-ai-lr-prompts/edit/main/README.md).  
2. Add your contribution in Markdown format under the appropriate section. Include:  
   - The intended use case (e.g., summarization, Boolean query generation).  
   - The prompt text.  
   - An example output as a quote.
   - A reference with a brief description of its application and evaluation.  
3. Use the "Preview changes" tab to ensure your contribution is formatted correctly.  
4. Provide a name for your proposed change and an optional description. Indicate that you would like to "Create a new branch for this commit and start a pull request," then click "Propose file change."


