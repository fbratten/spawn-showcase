# spawn Showcase

> Demo and documentation site for spawn — the pattern-to-MCP server generator for AI agent workflows.

[![Live Site](https://img.shields.io/badge/site-live-blue)](https://fbratten.github.io/spawn-showcase/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## What to look at first

1. The pipeline overview — logs become reusable MCP/FastMCP servers.
2. A worked session-log-to-server flow.
3. A generated-output example showing the expected server shape.
4. The source repository for implementation details and tests.

## What is spawn?

spawn is a meta-MCP server that analyzes patterns in AI agent session logs, scores them for buildability, and generates complete MCP server implementations. 17 tools, 156 tests.

In plain terms: spawn helps turn repeated agent behavior into explicit tools.

## Public surface

This showcase repo is the public proof surface for the project. It should make the concept understandable before someone reads the implementation.

The source repository contains the actual MCP server, pattern extraction pipeline, scoring model, generator, validator, and tests.

## Source Repository

Development happens at [fbratten/spawn](https://github.com/fbratten/spawn).

This showcase repository is the documentation and demo site. It is not open for collaborative development.

## About

Built by [Fredrik Bratten](https://github.com/fbratten) as part of the [AdaptiveArts.ai](https://adaptivearts.ai) research initiative.