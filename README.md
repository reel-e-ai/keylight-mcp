# Reel-E MCP server

Make and edit real estate listing videos, photos and websites from your AI assistant.

Reel-E turns a listing's photos into cinematic videos in every format, a listing website and
professional photo edits. This server lets an AI assistant do that work in your Reel-E account: start
a new listing video, change shots, music, titles and branding, check your website and video stats,
and hand you the link to your finished video.

This repository holds the public listing for the hosted server: this README and the
[MCP Registry entry](server.json). The server itself runs at Reel-E; there is nothing to install.

## Server address

```
https://www.reel-e.ai/mcp
```

Streamable HTTP. Sign-in is OAuth 2.1 (dynamic client registration and client ID metadata documents
are both supported).

## Connect

1. Add Reel-E to your assistant with the address above (this is usually called adding a connector or
   an MCP server).
2. Your assistant opens a Reel-E sign-in page. Sign in, choose what it may do, and press Allow.
3. Ask for what you want in plain language.

Step-by-step guides for Claude, Claude Code, ChatGPT, Cursor, VS Code, Gemini, Grok, Perplexity, Mistral
Le Chat, Manus, Meta Muse and Microsoft Copilot Studio are at
[reel-e.ai/docs/ai-assistants](https://www.reel-e.ai/docs/ai-assistants). Any assistant that supports
remote MCP servers can connect the same way.

## What you allow

- **Full control:** the assistant does the whole job without stopping.
- **Ask me first:** anything that uses a credit, publishes your website or starts a new listing waits
  for your yes in Reel-E.

You can also limit it to the listings you pick. Your assistant never sees your password, and you can
disconnect it any time in Reel-E under Account settings, Profile, Connected apps.

## What it can do

- Look at your listings and videos
- Start a new listing video from your photos or your public listing page
- Change shot order, camera moves, framing, pace, music, titles, text, stickers and branding
- Request AI motion, photo edits, virtual staging and voiceovers (these use your plan's credits)
- Publish and check your listing website, and read its visitor and video stats
- Give you the link to your finished video, where you download it

Every edit has an Undo. The full tool list, with which tools ask first, is at
[reel-e.ai/docs/ai-assistants/tools](https://www.reel-e.ai/docs/ai-assistants/tools).

It cannot start a plan, change billing or see anyone else's listings.

## Plans

Connecting is free. Work that uses a credit draws from the same allowance as the Reel-E app. Reel-E is
free to try and you can cancel anytime; see [plans](https://www.reel-e.ai/pricing).

## Support

Email [support@reel-e.ai](mailto:support@reel-e.ai) and say which assistant you use.

- [Privacy Policy](https://www.reel-e.ai/privacy-policy)
- [Terms of Service](https://www.reel-e.ai/terms-of-service)
