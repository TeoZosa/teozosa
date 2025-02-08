# Howdy! I'm Teo, great to meet you :wave:

I build production ML systems that deliver customer impact at scale by any means necessary.

* Sometimes this means getting in the weeds wrangling raw data; training and evaluating models; or setting up super
  reliable high-throughput, low-latency, highly-observable online/offline ML feature and model serving systems[^1].
* Other times this means sitting in meetings with business, product, and technical stakeholders from all corners of the
  company, as well as partners and colleagues across the industry, to define the right problems to tackle and the right
  things to build.
* No matter what, it always means listening to the people we're serving, making sure we're solving the most important
  problems, and thinking beyond what's possible to what is actually needed to add the most value to our customers.

[^1]: My current personal record was for an AI Search Ranking system at [Mercari](https://jp.mercari.com/):

    1. **Offline** data & model training pipelines that processed petabytes of data.
    2. **Online** serving system that handled nearly 6K RPS of search traffic with average e2e latency <35ms (p95
       <100ms) and five 9's uptime.
        1. **Streaming real-time feature ingestion pipeline** that processed over 100K client events per second and over
           2.3 terabytes of data per day; significant optimization for a monthly operational cost of $567/mo.
        2. **Feature store** that served over 3.5M read/write RPS with average read latency <3ms (p95 <10ms).
        3. **Model server** that handled nearly 6K RPS with average read latency <13ms (p95 <38ms).

I'm currently focus-firing all of the above as a Staff Machine Learning Engineer at [Mercari](https://jp.mercari.com/),
Japan’s largest C2C e-commerce marketplace, to support the world-class AI teams and applications across the company.

<!--
**TeoZosa/teozosa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

---

## Talks

### 2023

* [**FOSSASIA Summit 2023**:
  The Bumpy Road of Bringing a Machine Learning Model From Development to Production - Part 2: Infrastructure, Testing, Productionalization, and Monitoring](https://youtu.be/76Wko6jsd9E)[^2]
* [**Berlin Buzzwords 2023**:
  Building MLOps Infrastructure at Japan's Largest C2C E-Commerce Platform](https://youtu.be/11xxPUSJTss)[^2]

[^2]: w/ [`@ginstrom`](https://github.com/ginstrom)

### 2024

* [**FOSSASIA Summit 2024**:
  Unleashing the Potential of AI Through Search Ranking: How Mercari Uses Data & Science to Drive Marketplace Growth](https://youtu.be/7FEwBj6Mvys?t=6298)[^3]
* [**Weights & Biases Fully Connected 2024** (San Francisco):
  How Mercari is Using Gen AI to Define the Future of Japanese C2C E-commerce](https://youtu.be/Ze0OwPedJjg)
* [**Berlin Buzzwords 2024**:
  Robust AI Search Ranking for Radical C2C Marketplace Growth](https://youtu.be/ultbLz1y4OI)[^3]
  * [Mercari @ Berlin Buzzwords 2024! A closeup.](https://youtu.be/PrPmrUWLzTM)[^3]
* [**Weights & Biases Fully Connected 2024** (Tokyo):
  The Gen AI Powering the Next Generation of the Mercari Marketplace](https://youtu.be/fvZSaHTarfE)

[^3]: w/ [`@chingisooinar`](https://github.com/chingisooinar)

### 2025

* *[Coming Soon]* **FOSSASIA Summit 2025**: LLMOps for Eval-Driven Development at Scale[^4]  

[^4]: w/ [`@jehandadk`](https://github.com/jehandadk)
