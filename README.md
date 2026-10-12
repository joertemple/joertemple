<p align="center">
  <a href="https://frapea.com"><img src="https://frapea.com/logo.png" width="88" alt="Frapea" /></a>
</p>

<h1 align="center">Building Frapea: the video editor your AI drives</h1>

<p align="center">
  A real multitrack editor in a browser tab, exposed to AI agents over the Model Context Protocol.<br/>
  Your agent makes the edit instead of suggesting it, and hands back a timeline you can still take apart.
</p>

<p align="center">
  <a href="https://frapea.com"><b>frapea.com</b></a> ·
  <a href="https://app.frapea.com"><b>Open the editor</b></a> ·
  <a href="https://motion.frapea.com"><b>Motion</b></a> ·
  <a href="https://frapea.com/connect"><b>Connect your AI</b></a>
</p>

---

<a href="https://frapea.com/use-cases"><img src="https://frapea.com/shots/editor-motion-hero.jpg" alt="The Frapea editor: a viewer with an animated title over drone footage, a Motion inspector and a multitrack timeline" /></a>

### What I'm working on

**[Frapea](https://frapea.com)** is a full video editor that runs in Chrome, Edge or Brave. Nothing to install, and your footage never leaves your computer.
- **Editing:** cut, trim, ripple, captions, transcripts, multicam, face tracking, colour, transitions.
- **Export:** 4K export with SRT/VTT.
- **Agents:** Claude, ChatGPT, Cursor or Codex drive all of it through MCP, then render their own frames to check the result before they say it's done.

**[Motion](https://motion.frapea.com)** goes from one sentence to a finished animation. The agent writes motion graphics as code (springs, interpolation, React), renders real frames, looks at them and fixes what it sees.
- Free, no account, no watermark.
- A scene opens in the editor as an editable clip.

### Connect your agent

```sh
# Claude Code: the editor
claude mcp add --transport http frapea https://app.frapea.com/mcp

# Claude Code: Motion
claude mcp add --transport http motion https://motion.frapea.com/mcp
```

Both are in the [official MCP Registry](https://registry.modelcontextprotocol.io) as `com.frapea/editor` and `com.frapea/motion`. Setup for Claude Desktop, Cursor, VS Code, Windsurf, Codex CLI, Gemini CLI and Warp is on [frapea.com/connect](https://frapea.com/connect).

### See what it makes

| | |
|---|---|
| [<img src="https://frapea.com/use-cases/og-podcast-to-shorts.jpg" alt="Four hours of podcast in, three shorts out" />](https://frapea.com/use-cases/podcast-editing/podcast-to-shorts) | [<img src="https://frapea.com/use-cases/og-website-to-videos.jpg" alt="One website in, two videos out" />](https://frapea.com/use-cases/product-videos/website-to-story-video) |
| **Podcast to shorts:** a four-hour episode in, three captioned vertical shorts out. | **Website to video:** one URL in, a narrated story and a walkthrough out. |

More on [frapea.com/use-cases](https://frapea.com/use-cases) and in [Motion's 52 examples](https://motion.frapea.com/examples), each with the sentence that made it.

### Stack

`TypeScript` · `React` · `Next.js` · `WebCodecs` · `WebGPU` · `WebAssembly` · `Cloudflare Workers + Durable Objects` · `Model Context Protocol`

### Elsewhere

[X @hellofrapea](https://x.com/hellofrapea) · [Instagram](https://www.instagram.com/hellofrapea/) · [YouTube @Frapea](https://www.youtube.com/@Frapea)
