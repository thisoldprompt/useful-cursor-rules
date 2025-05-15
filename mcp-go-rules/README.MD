# MCP-GO Rules
Set of Rules Initalizing MCP Servers in GO.

## Requirments
- Add MCP-GO Readme to Cursor Docs as [mcp-go-readme](https://raw.githubusercontent.com/mark3labs/mcp-go/refs/heads/main/README.md)
- Add MCP Full LLM to Cursor Docs as [mcp-llms-full](https://modelcontextprotocol.io/llms-full.txt)


## How to use the Rules
- Add rules to .cursor/rule/mcp-go-rule.mdc
```bash
mkdir sample-mcp-project && cd sample-mcp-project && mkdir .cursor && mkdir .cursor/rules && cd .cursor/rules
wget https://raw.githubusercontent.com/thisoldprompt/useful-cursor-rules/refs/heads/main/mcp-go-rules/mcp-go-rules.mdc
cd ../..
cursor .
```

## Prompt
- Add the rule @mcp-go-rules to the chat
- **Add the Docs @mcp-go-readme & @mcp-llms-full**
- Make sure you add the docs and the rules before promptin.
```
Initialize a new go mcp server in my working directory
```