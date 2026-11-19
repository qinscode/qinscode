<a href="https://fudong.dev"><img src="./banner.svg" width="100%" alt="Hey, I'm Jack. Full-stack developer in Perth, Western Australia."></a>

I build **Dust IQ**, a dust monitoring platform for mine sites across Australia. On the side I make small macOS and web tools, usually because I wanted one myself.

[fudong.dev](https://fudong.dev) · [hello@fudong.dev](mailto:hello@fudong.dev)

## Day job

**Dust IQ** takes telemetry from dust sensors and flow meters in the field (millions of events a day) and turns it into live heatmaps, flow analytics and automated reports for the people running the site. It is closed source, so here is what it is made of instead:

<table>
  <tr><td><b>Web</b></td><td>React, TypeScript, Vite, TanStack Query</td></tr>
  <tr><td><b>API</b></td><td>.NET 10 modular monolith with a queue-backed worker</td></tr>
  <tr><td><b>Data</b></td><td>PostgreSQL, with TimescaleDB for telemetry</td></tr>
  <tr><td><b>Devices</b></td><td>Azure IoT Hub → Azure Functions → Service Bus</td></tr>
  <tr><td><b>Mobile</b></td><td>Two Expo / React Native apps: one for drivers, one for warehouse scanning</td></tr>
  <tr><td><b>Hosting</b></td><td>Azure Container Apps, Cloudflare Pages, GitHub Actions</td></tr>
</table>

## Open source

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/SeekSpider">SeekSpider</a> <a href="https://github.com/qinscode/SeekSpider/stargazers"><img src="https://img.shields.io/github/stars/qinscode/SeekSpider?style=flat&label=%E2%98%85&color=f59e0b" alt="GitHub stars" align="right"></a></h4>
      Scrapes IT job listings from Seek.com.au on a schedule, across Australian cities, then uses AI to pull out tech stacks and normalise salaries.
      <br><br>
      <code>Python</code> <code>Scrapy</code> <code>PostgreSQL</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/ccbuddy">CCBuddy</a></h4>
      macOS menu bar app that shows Claude Code token usage and cost in real time, for both subscription and API billing. Everything stays on your machine.
      <br><br>
      <code>Swift</code> <code>SwiftUI</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/PackPilot">PackPilot</a></h4>
      macOS launcher for monorepos. Point it at a folder and it finds every <code>package.json</code>, then starts, stops and restarts scripts with live logs in one window.
      <br><br>
      <code>Swift</code> <code>npm · pnpm · yarn · bun</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/GitHubRepoAnalyzer">GitHub Repo Analyzer</a></h4>
      Desktop app that digs into the metrics of GitHub repositories, one at a time or in batches.
      <br><br>
      <code>React</code> <code>TypeScript</code> <code>Tauri</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/ApplyTrack">ApplyTrack</a></h4>
      Job application tracker: applications, documents, history and analytics of the local IT job market in one dashboard.
      <br><br>
      <code>React</code> <code>TypeScript</code> <code>shadcn/ui</code>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/qinscode/UWA-Curriculum-Rules-Management-System">Curriculum Rules</a></h4>
      Course rule management for a university: nested rule hierarchies edited by drag and drop, with the formatted documents generated as PDFs.
      <br><br>
      <code>Next.js</code> <code>NestJS</code>
    </td>
  </tr>
</table>

Also: [UWA MIT Study Planner](https://github.com/qinscode/uwa-study-planner) (drag-and-drop course planning with prerequisite checks) and [FishFlow](https://github.com/qinscode/fishflow) (a fishing log with a collect-them-all fish guide, built with Expo).

## Toolbox

<img src="https://skillicons.dev/icons?i=ts,react,vite,tailwind,dotnet,cs,nodejs,py,swift,postgres,redis,rabbitmq,docker,azure,cloudflare,githubactions&perline=16" width="100%" alt="TypeScript, React, Vite, Tailwind CSS, .NET, C#, Node.js, Python, Swift, PostgreSQL, Redis, RabbitMQ, Docker, Azure, Cloudflare, GitHub Actions">
