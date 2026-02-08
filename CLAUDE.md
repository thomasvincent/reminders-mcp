# CLAUDE.md

MCP server that wraps Apple Reminders on macOS, providing tools to create, complete, search, and organize reminders through AppleScript.

## Stack

- TypeScript, Node.js, ESM
- MCP SDK

## Build

```sh
npm run build  # tsc
npm start      # node dist/index.js
npm run dev    # tsc --watch
```

## Project Structure

- Single source file at `src/index.ts`
- No test framework, linter, or formatter configured yet
- The `prepare` script auto-builds on install
