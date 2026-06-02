# Mohammed Baobaid

<p align="center">
  <img src="./assets/profile-banner.svg" alt="Mohammed Baobaid - Laravel systems, data analytics, and AI workflows" width="100%">
</p>

Laravel systems builder. Data analytics thinker. Product-polish person.

I build practical software where backend structure, useful data, and calm interfaces meet: Laravel apps, Filament panels, AI-aware workflows, BI dashboards, and developer tools.

[![Laravel Junior Certificate](https://img.shields.io/badge/Laravel_Certified-Junior-FF2D20?style=for-the-badge&logo=laravel&logoColor=white&labelColor=4A1D1D)](https://certificates.dev/laravel/certificates/a1ece076-e374-459c-b8b3-8f090fe89a8d)
[![Portfolio](https://img.shields.io/badge/Portfolio-baobaid.me-111827?style=for-the-badge&logo=firefox&logoColor=white)](https://baobaid.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mbs0-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mbs0/)

```mermaid
flowchart LR
    Start["Messy workflow"] --> Intake["Process + data signals"]

    subgraph Core["Laravel product core"]
        Model["Eloquent domain model"]
        Guard["Policies + validation"]
        Jobs["Queues + integrations"]
        Panel["Filament / Livewire UI"]
        Model --> Guard --> Jobs --> Panel
    end

    subgraph Intelligence["Analytics + AI layer"]
        Metrics["SQL / KPI model"]
        BI["Power BI / Tableau / KNIME"]
        Context["Approved AI context"]
        Metrics --> BI
        Metrics --> Context
    end

    Intake --> Model
    Panel --> Metrics
    Context --> Decision["Traceable decision surface"]
    BI --> Decision
    Decision --> Outcome["Useful product output"]

    classDef laravel fill:#2A1212,stroke:#FF2D20,color:#FFF3F0;
    classDef data fill:#1E293B,stroke:#38BDF8,color:#E0F2FE;
    classDef ai fill:#12332F,stroke:#14B8A6,color:#CCFBF1;
    classDef result fill:#2A2108,stroke:#F59E0B,color:#FEF3C7;
    class Model,Guard,Jobs,Panel laravel;
    class Metrics,BI data;
    class Context ai;
    class Decision,Outcome result;
```

## Build Mode

- Laravel products with Filament, Livewire, queues, policies, mail, APIs, and tests.
- Data workflows with SQL, Power BI, Tableau, KNIME, Excel, and statistical modeling.
- AI features that use approved application context instead of loose database guessing.
- Interfaces that make dense operations feel readable, traceable, and fast.

## Stack Signal

`Laravel` `PHP` `Filament` `Livewire` `Blade` `Tailwind CSS` `Alpine.js` `MySQL` `PHPUnit` `REST APIs` `Queues` `OpenAI` `SQL` `Power BI` `Tableau` `KNIME`

## Proof Points

| Work | Signal |
| --- | --- |
| [ModelMind](https://github.com/mbs047/model-mind) | Laravel AI assistant package with model-aware context, citations, providers, sessions, analytics, and tests. |
| [MBS Terminal](https://github.com/mbs047/MBS-Terminal) | Windows terminal setup for Laravel/PHP development, packaged with setup, restore, theme, prompt, and workflow helpers. |
| [MBS Portfolio](https://github.com/mbs047/MBS-Portfolio) | Laravel portfolio platform with case studies, certificates, references, contact flows, SEO, and Filament admin tooling. |

## Current Focus

Product-grade Laravel delivery, analytics clarity, and developer experience tooling.

Abu Dhabi, UAE. Open to thoughtful Laravel, data, dashboard, and workflow projects.
