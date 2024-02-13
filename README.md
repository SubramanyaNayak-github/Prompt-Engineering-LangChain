# Prompt-Engineering-LangChain

Prompt templates are predefined recipes for generating prompts for language models.

A template may include instructions, few-shot examples, and specific context and questions appropriate for a given task.

LangChain provides tooling to create and work with prompt templates.

LangChain strives to create model agnostic templates to make it easy to reuse existing templates across different language models.

Typically, language models expect the prompt to either be a string or else a list of chat messages.


**Prompts:-**

[prompts documentation](https://python.langchain.com/docs/modules/model_io/prompts/quick_start)


`A prompt for a language model is a set of instructions or input provided by a user to guide the model's response, helping it understand the context and generate relevant and coherent language-based output, such as answering questions, completing sentences, or engaging in a conversation.`

`Text generally used as instructions to your model`



**Prompt:-**

`What you'll pass to the underlying model`

**Prompt Template**

`An object that helps create prompts based on a combination of user input, other non-static information and a fixed template string.`

`Use PromptTemplate to create a template for a string prompt.`

By default, PromptTemplate uses Python’s str.format syntax for templating.


**ChatPromptTemplate:-**


`The prompt to chat models is a list of chat messages.`

Each chat message is associated with content, and an additional parameter called role. For example, in the OpenAI Chat Completions API, a chat message can be associated with an AI assistant, a human or a system role.



