# Testsy

Testsy runs QA tests written in plain English on websites and on iOS and Android apps, and returns a verdict for every check with its evidence: a replay, video, the values it saw, console and network.

Documentation: https://testsy.dev/docs/mcp/ · Sign up: https://app.testsy.dev

This Gemini CLI extension adds the Testsy MCP server and three skills: check a release, investigate a failed run, and turn a fixed bug into a saved regression test.

Install with `gemini extensions install https://github.com/testsy-ai/testsy-gemini-extension`. Enter a Testsy workspace API key (from https://app.testsy.dev) when prompted; it is stored as a sensitive setting. Restart the CLI and check its MCP and skill lists.

Keep API keys in your secret store, out of prompts and version control. A run uses the workspace allowance and performs real actions on the site or app it is pointed at, so use it on apps and accounts you are allowed to test. These integration files are MIT licensed.
