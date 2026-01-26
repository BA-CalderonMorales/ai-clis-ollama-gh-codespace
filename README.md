# AI CLIs + Ollama + GitHub Codespaces (remote development enviornment)

Skill repo to specifically setup any AI CLI to run without wasting massive amounts of tokens. 

Ultimately, you:

1) Leverage Claude Opus 4.5 (or flagship model at the time) SOLELY for planning;
2) Switch to locally running models in GH Codespaces (remote development enviornment);
3) Handle "grunt work" with GLM-4.7 or qwen3-coder (or models that can go on and on without fear of running out of tokens)

See:

- https://docs.ollama.com/quickstart:
  - ollama pull glm-4.7-flash (this one can be downloaded if GitHub Codespaces, but it's slow man. So is gpt-oss:20b; and the quantized qwen3-coder models)
  - ollama pull glm-4.7:cloud (this one requires subscription to ollama, would argue same quality as Claude Sonnet 4.5)
- https://docs.factory.ai/cli/getting-started/quickstart (to download Claude Code, requirement for ollama to work)
- https://code.claude.com/docs/en/quickstart (to download Droid, optional incase you want to try something other than Claude Code)

Ultimately, I'm using this as a record for when I ended up starting to use models that don't require me to get an entire server rack or spending more than $200 for decent output.

The bar is high folks.
