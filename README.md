# Hey, I'm Abhishek 👋

**AI Engineer** building production-ready ML and LLM systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhisheksharma04/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:abhisheksharma1404@gmail.com)

---

### 🔧 Tech Stack

**LLM & NLP**  
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/🦜_LangChain-1C3C3C?style=flat)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/🦙_LlamaIndex-5A29E4?style=flat)

**Vector DBs & RAG**  
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat)

**ML Frameworks**  
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

**Languages**  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

**Tools & Platforms**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)

---

### 📊 GitHub Stats

<p>
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=Abhishek01454&show_icons=true&theme=github_dark&hide_border=true" />
  <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=Abhishek01454&theme=github-dark-blue&hide_border=true" />
</p>

<p>
  <img width="40%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abhishek01454&layout=compact&theme=github_dark&hide_border=true" />
</p>

---

### 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Abhishek01454/Abhishek01454/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Abhishek01454/Abhishek01454/output/github-snake.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/Abhishek01454/Abhishek01454/output/github-snake-dark.svg" />
</picture>

<details>
<summary>⚙️ Snake Setup</summary>

Create `.github/workflows/snake.yml`:

```yaml
name: Snake
on:
  schedule:
    - cron: "0 */12 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Abhishek01454
          outputs: |
            dist/github-snake.svg
            dist/github-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

</details>
