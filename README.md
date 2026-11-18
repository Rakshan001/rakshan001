<div align="center">
  <img src="https://rakshan-shetty.netlify.app/favicon.svg" width="52" alt="RS" />
  <h1>Rakshan Shetty</h1>
  <p>
    Full stack, backend and GenAI engineer.<br />
    I build web products end to end, and open-source tools for working with AI coding agents.
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

I'm a full stack engineer with a backend focus, working on GenAI products. I build web apps in
React, Next.js, Node.js and Python, design the APIs and data models behind them, and add LLM
features such as RAG pipelines and agents.

Lately most of my time goes into AI-assisted engineering: running several coding agents on one
codebase without them overwriting each other, passing a plan from one agent to the next, and
giving them memory they can trust. The projects below came out of that.

<br />

### Open source

**[Baton](https://baton-landing.vercel.app)** &nbsp; Run several AI coding agents on one repo without conflicts.

Claude Code, Cursor, Codex, Gemini and others work in the same repo at the same time. Each task
gets its own git worktree, a local dashboard shows which agent is editing what, and a handoff file
passes the plan from the agent that reasons to the agent that writes the code.

<sub>TypeScript, Node.js, React, SQLite, MCP. On npm as <code>batonhq</code>.<br /><a href="https://baton-landing.vercel.app">Website</a> &nbsp;/&nbsp; <a href="https://baton-landing.vercel.app/download/mac">Download for Mac</a></sub>

<br />

**[Elmory](https://github.com/Rakshan001/elmory)** &nbsp; Memory for coding agents that knows when it is out of date.

Every fact quotes the code that proves it, and each recall checks that the quote is still there.
If the code changed, the fact is held back, and when nothing holds up the answer is "I don't know"
instead of a guess. Works as a CLI or an MCP server.

<sub>TypeScript on Node 24, SQLite, runs offline. On npm as <code>elmory</code>. MIT.<br /><a href="https://elmory.vercel.app">Website</a> &nbsp;/&nbsp; <a href="https://github.com/Rakshan001/elmory">Repository</a></sub>

<br />

**[Agent skills](https://github.com/Rakshan001/agent-skills)** &nbsp; Skills I wrote for AI coding agents.

Plain `SKILL.md` folders for Claude Code, Codex, Cursor and Antigravity: fixing bugs without
regressions, verifying work before calling it done, splitting a monolith, migrating a stack,
privacy compliance, site search and more. Copy a folder into your agent's skills directory.

<sub>Markdown. MIT.<br /><a href="https://github.com/Rakshan001/agent-skills">Repository</a></sub>

<br />

**[JavaScript](https://github.com/Rakshan001/JavaScript)** &nbsp; My JavaScript study notes and exercises: execution model, promises and async, DOM, storage.

<br />

### Stack

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts%2Cjs%2Cpy%2Cjava%2Creact%2Cnextjs%2Cnodejs%2Cexpress%2Cdjango%2Cflask%2Ctailwind%2Cmongodb%2Cpostgres%2Cmysql%2Csqlite%2Credis%2Cdocker%2Caws%2Cgithubactions%2Cgit%2Cvercel%2Ctensorflow%2Csklearn&perline=12&theme=dark" />
    <img src="https://skillicons.dev/icons?i=ts,js,py,java,react,nextjs,nodejs,express,django,flask,tailwind,mongodb,postgres,mysql,sqlite,redis,docker,aws,githubactions,git,vercel,tensorflow,sklearn&perline=12&theme=light" alt="TypeScript, JavaScript, Python, Java, React, Next.js, Node.js, Express, Django, Flask, Tailwind CSS, MongoDB, PostgreSQL, MySQL, SQLite, Redis, Docker, AWS, GitHub Actions, Git, Vercel, TensorFlow, scikit-learn" />
  </picture>
</p>

<sub>GenAI: RAG, LangChain, LangGraph, Gemini API, OpenAI API, MCP, AI agents, multi-agent workflows</sub>
