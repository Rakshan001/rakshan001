<div align="center">
  <img src="https://rakshan-shetty.netlify.app/favicon.svg" width="52" alt="RS" />
  <h1>Rakshan Shetty</h1>
  <p>
    Full stack, backend and GenAI engineer.<br />
    I build web products end to end, and open-source tools for shipping software faster with AI coding agents.
  </p>
  <p>
    <a href="https://rakshan-shetty.netlify.app/">Portfolio</a>
    &nbsp;&nbsp;/&nbsp;&nbsp;
    <a href="https://linkedin.com/in/rakshan-shetty-953864225">LinkedIn</a>
    &nbsp;&nbsp;/&nbsp;&nbsp;
    <a href="mailto:rakshanshetty2003@gmail.com">Email</a>
    &nbsp;&nbsp;/&nbsp;&nbsp;
    <a href="https://rakshan-shetty.netlify.app/resume/Rakshan_Shetty_Resume.pdf">Resume</a>
  </p>
</div>

<br />

### About

I'm a full stack engineer with a backend focus, working on GenAI products. I build web applications end to end in React, Next.js, Node.js and Python, design the APIs and data models behind them, and add LLM features such as RAG pipelines and AI agents with LangChain, LangGraph and the Gemini and OpenAI APIs.

Most of my recent work is about AI-assisted engineering: how to ship software faster by running several AI coding agents in parallel, coordinating them so they don't overwrite each other, handing a plan from one agent to the next, and giving them memory they can actually trust. I build open-source tools for exactly that.

<br />

### What I work on

- **Full stack development.** React, Next.js and TypeScript front ends on Node.js and Python back ends, with server-side rendering and responsive UI.
- **Backend engineering.** REST APIs, authentication and role-based access control, PostgreSQL, MongoDB and Redis, CI/CD with GitHub Actions and Docker.
- **GenAI engineering.** RAG pipelines, embeddings and vector search, LLM integration, AI agents and the agent loop, MCP servers.
- **Multi-agent coding workflows.** Running Claude Code, Cursor, Codex and Gemini together on one codebase, with isolated git worktrees, agent handoff and verified agent memory.

<br />

### Open source

**[Baton](https://github.com/Rakshan001/Baton-Multi-Agent-)** &nbsp; Run several AI coding agents on one repository without conflicts.

Baton lets Claude Code, Cursor, Codex, Gemini, Aider and OpenCode work in the same repo at the same time. Every task gets its own git worktree, a local dashboard shows which agent is editing what, and a single `HANDOFF.md` passes the plan from the agent that reasons to the agent that writes the code. Plan on your expensive model, build on your cheaper one.

<sub>TypeScript, Node.js, React, SQLite, MCP. 16,000 lines, 641 tests, no runtime dependencies in the daemon. MIT.<br /><a href="https://baton-landing.vercel.app">Website</a> &nbsp;/&nbsp; <a href="https://github.com/Rakshan001/Baton-Multi-Agent-">Repository</a></sub>

<br />

**[Elmory](https://elmory.vercel.app)** &nbsp; Memory for AI coding agents that knows when it's out of date.

Agent memory goes stale silently: a note says one thing, the code now says another, and the agent acts on the note. In Elmory every fact quotes the exact code that proves it, and each recall checks that the quote still exists. If it does, the fact is served. If the code changed, the fact is withheld, and when nothing holds the answer is "I don't know" instead of a guess. Works as a CLI or an MCP server for Claude Code, Cursor and Codex.

<sub>TypeScript on Node 24, SQLite full-text search, runs offline. Pre-release. MIT.<br /><a href="https://elmory.vercel.app">Website</a> &nbsp;/&nbsp; <a href="https://elmory.vercel.app/docs/introduction">Docs</a> &nbsp;/&nbsp; <a href="https://github.com/Rakshan001/elmory">Repository</a></sub>

<br />

<sub>Baton coordinates the agents. Elmory gives them memory that can't silently go stale.</sub>

<br />

### Stack

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts%2Cjs%2Cpy%2Cjava%2Creact%2Cnextjs%2Cnodejs%2Cexpress%2Cdjango%2Cflask%2Ctailwind%2Cmongodb%2Cpostgres%2Cmysql%2Csqlite%2Credis%2Cdocker%2Caws%2Cgithubactions%2Cgit%2Cvercel%2Ctensorflow%2Csklearn&perline=12&theme=dark" />
    <img src="https://skillicons.dev/icons?i=ts,js,py,java,react,nextjs,nodejs,express,django,flask,tailwind,mongodb,postgres,mysql,sqlite,redis,docker,aws,githubactions,git,vercel,tensorflow,sklearn&perline=12&theme=light" alt="TypeScript, JavaScript, Python, Java, React, Next.js, Node.js, Express, Django, Flask, Tailwind CSS, MongoDB, PostgreSQL, MySQL, SQLite, Redis, Docker, AWS, GitHub Actions, Git, Vercel, TensorFlow, scikit-learn" />
  </picture>
</p>

<sub>GenAI: RAG, LangChain, LangGraph, LangSmith, Gemini API, OpenAI API, MCP, AI agents, multi-agent orchestration</sub>

<br />

### GitHub

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api?username=Rakshan001&show_icons=true&include_all_commits=true&disable_animations=true&hide_rank=true&hide_border=true&theme=transparent&title_color=E6EDF3&text_color=9198A1&icon_color=E6EDF3" />
    <img height="165" src="https://github-stats-extended.vercel.app/api?username=Rakshan001&show_icons=true&include_all_commits=true&disable_animations=true&hide_rank=true&hide_border=true&theme=transparent&title_color=1F2328&text_color=59636E&icon_color=1F2328" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-stats-extended.vercel.app/api/top-langs/?username=Rakshan001&layout=compact&langs_count=8&disable_animations=true&hide_border=true&theme=transparent&title_color=E6EDF3&text_color=9198A1&icon_color=E6EDF3" />
    <img height="165" src="https://github-stats-extended.vercel.app/api/top-langs/?username=Rakshan001&layout=compact&langs_count=8&disable_animations=true&hide_border=true&theme=transparent&title_color=1F2328&text_color=59636E&icon_color=1F2328" alt="Most used languages" />
  </picture>
</p>
