<h1 align="center">Andres Uribe</h1>
<h3 align="center">Full-Stack Engineer · AI Agents on Serverless AWS</h3>

<h2>About me</h2>
<p>
I'm a full-stack engineer at <a href="https://palomma.com" target="_blank">Palomma</a>, where I build LLM-powered agents that help real estate brokerages capture, qualify, and close leads across LATAM. I work end-to-end: from the agent runtime and CRM plumbing on the backend, to the admin and merchant-facing dashboards on the frontend, to the AWS infrastructure that runs all of it.
</p>
<p>
Before tech, I worked across engineering, finance, and operations, and I taught myself to code while at a venture-backed retail company. That mix shows up in how I work — I care about shipping things that move business metrics, not just shipping code.
</p>

<h2>What I'm building</h2>
<ul>
  <li><b>LLM agents on WhatsApp</b> — Conversational agents (built with LangChain / LangGraph + OpenAI) that handle inbound real-estate leads end-to-end: intent detection, listing search, appointment booking, and clean handoff to human agents.</li>
  <li><b>CRM & portal integrations</b> — Bidirectional sync with Bitrix24, Zoho, HubSpot, Pipedrive, and listing portals (Proppit, Bienraiz, Fincaraíz, Ciencuadras), including custom field mappings, picklist normalization, and lead routing.</li>
  <li><b>Assignment & analytics</b> — Rule-based lead assignment, funnel and demand dashboards, Tinybird pipelines, and PostHog event tracking for the operations team.</li>
  <li><b>Admin & merchant portals</b> — React/Next.js dashboards for internal ops and brokerage customers to configure agents, review conversations, and monitor performance.</li>
</ul>

<h2>Stack & skills</h2>

<p><b>Infrastructure as Code · AWS Serverless</b><br/>
The product runs on a TypeScript SST v2 + AWS CDK codebase with 25+ independently deployable stacks. I work across all of it — defining new stacks, wiring services together, and managing deploys.</p>
<ul>
  <li><b>SST v2 / AWS CDK</b> — infra defined in TypeScript, multi-stage (dev / prod) deploys</li>
  <li><b>AWS Lambda</b> (Node.js 20) for the agent runtime, queue consumers, webhooks, and APIs</li>
  <li><b>DynamoDB</b> single-table design with multiple GSIs, accessed via <b>ElectroDB</b></li>
  <li><b>EventBridge, SQS (with DLQs), SNS</b> for the event-driven backbone</li>
  <li><b>API Gateway</b> (REST + WebSockets) and <b>S3</b> for media and assets</li>
</ul>

<p><b>Monorepo</b><br/>
Yarn workspaces monorepo with separate packages for the agent runtime, analytics pipeline, admin dashboard, and merchant portal — shared types and utilities across all of them.</p>

<p><b>Backend & agent runtime</b><br/>
TypeScript / Node.js, Python where it fits, <b>LangChain</b> + <b>LangGraph</b>, <b>OpenAI</b>, <b>WhatsApp Cloud API</b>, <b>Vapi</b> for voice, <b>Stytch</b> for auth.</p>

<p><b>Frontend</b><br/>
React, Next.js, TypeScript, Tailwind, shadcn/ui, TanStack Query.</p>

<p><b>Data & analytics</b><br/>
DynamoDB, MongoDB, <b>Tinybird</b> for real-time analytics, <b>PostHog</b> for product analytics and event tracking.</p>

<p align="left"> <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> <a href="https://aws.amazon.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/> </a> <a href="https://sst.dev/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/55178746?s=200&v=4" alt="sst" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> <a href="https://nextjs.org/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/nextjs-2.svg" alt="nextjs" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg" alt="tailwind" width="40" height="40"/> </a> <a href="https://js.langchain.com/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/126733545?s=200&v=4" alt="langchain" width="40" height="40"/> </a> <a href="https://posthog.com/" target="_blank" rel="noreferrer"> <img src="https://avatars.githubusercontent.com/u/60330232?s=200&v=4" alt="posthog" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> </p>

<h2>Get in touch</h2>
<p>
  📫 <a href="mailto:anduri1997@gmail.com">anduri1997@gmail.com</a><br/>
  💼 <a href="https://www.linkedin.com/in/andr%C3%A9s-uribe-2a537517b/" target="_blank">LinkedIn</a>
</p>
