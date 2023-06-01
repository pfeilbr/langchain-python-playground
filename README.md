# langchain-python-playground

learn [LangChain (python)](https://python.langchain.com/)

## concepts


- **Agents** - use an LLM to determine which actions to take and in what order. An action can either be using a tool and observing its output, or returning to the user.

the llm is used to select the tool to use

`langchain/agents/agent.py` - `_call` method has main logic
`langchain/agents/types.py`
`langchain/agents/mrkl/prompt.py`
`langchain/agents/**/*prompt.py` - these contain all the prompts for different agents

## demo

```sh
pipenv shell
export OPENAI_API_KEY=...
export SERPAPI_API_KEY=...
jupyter lab
# visit `main.ipynb`
```

## resources

- [langchain-python](https://python.langchain.com/)