# Hi there, I'm l7on3n! 👋

### GitHub Analytics

<p align="center">
  <img src="https://github-stats-alpha.vercel.app/api?username=l7on3n&cc=222&tc=fff&ic=fff" alt="l7on3n's GitHub Stats" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=l7on3n&theme=dark&hide_border=true" alt="l7on3n's GitHub Streak" width="49%" />
</p>

---

## Tech Stack & Toolkit

| Category | Tools & Technologies |
| :--- | :--- |
| **Web Engineering & Auth** | ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=flat&logo=laravel&logoColor=white) ![GoFiber](https://img.shields.io/badge/gofiber-%2300ADD8.svg?style=flat&logo=go&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=flat&logo=oauth&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%234479A1.svg?style=flat&logo=mysql&logoColor=white) |
| **Data Science & ML** | <a href="https://www.kaggle.com/faturrahmanilhamid" target="_blank">![Kaggle](https://img.shields.io/badge/Kaggle-%2320BEFF.svg?style=flat&logo=Kaggle&logoColor=white)</a> ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=flat&logo=PyTorch&logoColor=white) ![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?style=flat&logoColor=black) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black) |
| **Languages & Viz** | ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=flat&logo=go&logoColor=white) ![Python](https://img.shields.io/badge/python-%233776AB.svg?style=flat&logo=python&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=flat&logo=php&logoColor=white) ![Mermaid](https://img.shields.io/badge/mermaid-%23FF6584.svg?style=flat&logo=mermaid&logoColor=white) |
| **Infrastructure & OS** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google%20Colab-%23F9AB00.svg?style=flat&logo=google-colab&logoColor=white) |

> *Comfortable navigating CLI, tweaking systems, versioning code, and configuring environments.*

---

## My Workflow Ecosystem

Below is a breakdown of how my tech stack interacts, mapped via an architecture workflow:
```mermaid
graph TD
    A[Linux OS & Git] --> B[Data Pipelines]
    A --> C[Backend APIs]
    K[Kaggle Datasets] --> B
    L[Data Scrape] --> B
    
    subgraph ML [ML & Data Engineering]
    B --> D[Google Colab]
    D --> E[PyTorch & Hugging Face]
    E --> F[Matplotlib Charts]
    E --> M[Model Weight]
    end
    
    subgraph WEB [Web Engineering]
    C --> G[GoFiber / Laravel]
    G --> H[MySQL DB]
    G --> I[TailwindCSS Frontends]
    J[OAuth 2.0 Provider] --> G
    end

    %% Subgraph Styling
    style ML fill:#f0f7f4,stroke:#333,stroke-width:1px,color:#1b4332
    style WEB fill:#f0f4f8,stroke:#333,stroke-width:1px,color:#1a365d

    %% Core Nodes
    style A fill:#2d3748,stroke:#FCC624,stroke-width:2px,color:#fff
    style B fill:#4a5568,stroke:#cbd5e0,stroke-width:1px,color:#fff
    style C fill:#4a5568,stroke:#cbd5e0,stroke-width:1px,color:#fff
    style L fill:#718096,stroke:#cbd5e0,stroke-width:1px,color:#fff

    %% ML & Data Engineering Stack
    style K fill:#20BEFF,stroke:#008bb9,stroke-width:2px,color:#000
    style D fill:#F9AB00,stroke:#e09a00,stroke-width:2px,color:#000
    style E fill:#FF6F20,stroke:#d4520e,stroke-width:2px,color:#fff
    style F fill:#3182ce,stroke:#2b6cb0,stroke-width:1px,color:#fff
    style M fill:#10b981,stroke:#059669,stroke-width:1px,color:#fff

    %% Web Engineering Stack
    style G fill:#E11D48,stroke:#be123c,stroke-width:2px,color:#fff
    style H fill:#00758F,stroke:#005e73,stroke-width:2px,color:#fff
    style I fill:#06B6D4,stroke:#0891b2,stroke-width:1px,color:#fff
    style J fill:#EB5424,stroke:#c84218,stroke-width:2px,color:#fff

    linkStyle default stroke:#94A3B8,stroke-width:2px
