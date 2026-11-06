<div align="center">

# Hey, I'm Vaidhyam

I write mostly TypeScript, with more Python lately, and I like building the backend that an ML model plugs into.

<a href="https://github.com/vaidii2008">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=3178C6&center=true&vCenter=true&width=600&lines=Applied+AI+and+full-stack+web+dev;TypeScript%2C+React%2C+Next.js+and+Node.js;Python%2C+Django%2C+PyTorch+and+RAG;Backend+APIs+with+Postgres+and+Redis" alt="Typing SVG" />
</a>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vaidhyam-gautam-766973215/)
[![Email](https://img.shields.io/badge/Email-Reach%20Out-D14836?style=flat&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=flat&logo=github&logoColor=white)](https://github.com/vaidii2008)

</div>

---

## About me

I did my undergrad in Electronics and Communication Engineering, freelanced as a MERN developer for a year, and then came to Ireland for an MSc in AI/ML at the University of Limerick. I'm based in Dublin now.

I enjoyed the ML side of the MSc, but the part I keep coming back to is the engineering around a model: the API and database it sits behind, and whatever keeps running after the notebook is closed. Most of what's on this profile is me practising that.

---

## Projects

### [Slipstream](https://github.com/vaidii2008/slipstream-exchange)
A crypto exchange simulator, and the project I'm finishing right now. It has a price-time priority matching engine with property-based tests, a double-entry ledger for balances, accounts and sessions, and live order books, trades and account updates over WebSockets, fanned out through Redis pub/sub. Benchmarked on its own on an Apple M4, the engine handles about 4.4 million orders and cancels a second, with p99 latency under a microsecond. It's TypeScript on Fastify, Postgres (through Drizzle) and Redis. Still to come: trading bots that trade in the same order books as real users.

### [Binless](https://github.com/vaidii2008/Binless)
Tells an independent grocer how much of each fresh product to order for tomorrow, and explains why in plain English. LightGBM quantile forecasts feed a newsvendor order rule, and in the backtest, ordering the median forecast cut waste from 20.6% to 14.6% compared with reordering last week's sales. It's a Django and HTMX app on AWS Lambda, with a nightly batch job, Neon Postgres, and tests that run against Postgres in GitHub Actions. It's also my first proper Python project. There's a [live demo](https://a9lersj3kf.execute-api.eu-west-2.amazonaws.com/) with a simulated shop.

### [DocQA](https://github.com/vaidii2008/docqa)
Upload documents, ask questions, get answers grounded in what's actually in them (RAG). It's Next.js 15 and TypeScript on Postgres with pgvector, Prisma and Auth.js, tested with Vitest and Playwright, with CI on GitHub Actions. It runs on Vercel and Neon. I'm now extending it into something closer to an enterprise knowledge assistant.

### [Skin lesion classification](https://github.com/vaidii2008/xception-dermoscopy-cv)
Multi-class skin lesion classification on HAM10000 in PyTorch, using an ImageNet-pretrained Xception with patient metadata fused in. I used 3-fold cross-validation and ablations to see what each part added, and Grad-CAM to check what the model was actually looking at.

---

## Open source

I updated the Lunar Lander example in [ansys/pyfluent](https://github.com/ansys/pyfluent) to work with the library's current field data API ([#5482](https://github.com/ansys/pyfluent/pull/5482)). Two maintainers have approved it, and it's waiting to be merged.

---

## Tech I've used

### Languages
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![HTMX](https://img.shields.io/badge/HTMX-3366CC?style=flat&logo=htmx&logoColor=white)

### Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat&logo=fastify&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat&logo=drizzle&logoColor=black)
![Auth.js](https://img.shields.io/badge/Auth.js-7C3AED?style=flat)
![REST](https://img.shields.io/badge/REST-005571?style=flat)
![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=flat)

### Data and storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=flat)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

### AI / ML
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-000000?style=flat&logo=vercel&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-8A2BE2?style=flat)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)

### Cloud, DevOps and testing
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonwebservices&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![SageMaker](https://img.shields.io/badge/SageMaker-FF9900?style=flat)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

## What I'm learning right now

![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)
![LLM Evals](https://img.shields.io/badge/LLM%20Evals-8A2BE2?style=flat)

MCP servers and LLM evals. Once Slipstream is done, they're what I'll be building with next, to take my RAG work further. I'm also working through NeetCode 150 on the side.

## Next on the list

- MCP servers and a proper eval setup for my RAG work, with a real evaluation dataset
- Hybrid search (BM25 plus vectors), reranking and semantic chunking for DocQA
- Checking that answers actually match the sources they cite, and catching hallucinations
- Latency and cost tracking
- An AWS certification, once I decide which one

---

## A few things I'm proud of

- My MSc dissertation, GE-RAG, used grammatical evolution to evolve query reformulation strategies for RAG. It was graded 4.0.
- A paper from my ECE days: *CMOS Low Noise Amplifier Design Optimization Techniques* (a 950 MHz Zigbee LNA), published by Taylor & Francis / CRC Press in 2024.
- I trained Vanilla and Double DQN agents on Atari's Atlantis for 2M steps on an A100 ([repo](https://github.com/vaidii2008/DQN-for-Attari-games)). Vanilla DQN averaged around 5,341 reward over the last 100 episodes, against roughly 533 for a random agent. (It was supposed to be Video Pinball, but the cluster nodes kept failing.)
- I reworked a diabetes prediction model ([repo](https://github.com/vaidii2008/diabetes-prediction-knn)) and found a data-leakage bug that had inflated the original accuracy by 11 points.
- My team built edge AI apps at the LERO x Qualcomm hackathon.

---

## Education

- MSc in Artificial Intelligence and Machine Learning, University of Limerick (2025-26). QCA 3.57.
- B.Tech in Electronics and Communication Engineering, AKTU (2020-24). Second Class Honours, Grade 1 (2:1).

---

## Say hi

I'm looking for software engineer, backend and AI engineer roles, graduate programmes included. If something here caught your eye, or you just want to talk about matching engines or RAG, message me on LinkedIn.

<div align="center">

![Profile views](https://komarev.com/ghpvc/?username=vaidii2008&color=lightgrey&style=flat)

</div>
