<strong>YouTube SEO Insights Generator with Jenkins, ArgoCD & Kubernetes</strong>

<strong>Features:</strong>

<ul>
<li>Automated CI/CD pipeline: Jenkins builds Docker images, pushes to Docker Hub, and updates deployment manifests.</li>
<li>GitOps deployment: ArgoCD syncs Kubernetes manifests for declarative, repeatable rollouts.</li>
<li>Kubernetes orchestration: Production-ready deployment with deployment.yaml and service.yaml.</li>
<li>Streamlit user interface Interactive web UI for entering YouTube URLs and generating SEO insights.</li>
<li>Video metadata extraction:video_extractor.py pulls title, author, views, duration, thumbnail, and other metadata.</li>
<li>AI-driven SEO analysis: seo_engine.py uses OpenAI to generate tags, audience analysis, timestamps, flaws, and fixes.</li>
<li>SEO recommendation engine: Automated tags, keyword suggestions, ranking improvements, and content optimization guidance.</li>
<li>Environment-driven config: API keys and secrets managed using python-dotenv and environment variables.</li>
<li>Modular architecture: Clear separation of UI, extraction, analysis, logging, and deployment logic.</li>
<li>Monitoring-ready logging: Structured logging support in logger.py for observability and debugging.</li>
</ul>

<strong>Technologies used:</strong>

<ul>
  <li>Python: Core language for the application, SEO engine, and data ingestion logic.</li>
  <li>Streamlit: for the frontend UI</li>
  <li>OpenAI API: AI-powered analysis for generating tags, audience insights, timestamps, and improvement suggestions.</li>
  <li>python-dotenv: Environment config management for secure API keys and runtime settings.</li>
  <li>requests: HTTP integration library used to fetch YouTube metadata and external data sources.</li>
  <li>Docker: Containerization for packaging the app and making deployments portable.</li>
  <li>Jenkins: CI/CD automation that builds Docker images, pushes to Docker Hub, and updates deployment manifests.</li>
  <li>Docker Hub: Container registry to store and version application images built by the pipeline.</li>
  <li>Kubernetes: Orchestrates the deployed service with scalable pods and production-grade runtime.</li>
  <li>ArgoCD: GitOps deployment tool that syncs Kubernetes manifests for declarative, repeatable rollouts.</li>
  <li>kubectl / argocd CLI: Command-line tooling used in the Jenkins pipeline to apply manifests and sync the app.</li>
  <li>GitHub: Source control and repository integration for code checkout and manifest updates.</li>  
</ul>

# Output


<img width="5420" height="2660" alt="IMG-20260702-WA0244" src="https://github.com/user-attachments/assets/962e5acb-40bd-4bba-8b93-a89b6b44a193" />


<img width="5464" height="2615" alt="IMG-20260702-WA0240" src="https://github.com/user-attachments/assets/3adb055a-3595-40d2-8b3a-f352e7636170" />


<img width="5412" height="2592" alt="IMG-20260702-WA0227(2)" src="https://github.com/user-attachments/assets/19500e81-0178-40ea-bf2f-1b4c249cb526" />


<img width="5464" height="2556" alt="IMG-20260702-WA0225 (1)" src="https://github.com/user-attachments/assets/a972ee24-cab0-483a-a04f-e760172f5516" />


<img width="5464" height="2572" alt="IMG-20260702-WA0239" src="https://github.com/user-attachments/assets/c0f0bcec-7b96-4fdf-b4d1-c1fd35f86bb1" />


<strong> CI/CD pipeline using Jenkins and ArgoCD </strong>

<img width="5412" height="2672" alt="IMG-20260702-WA0237" src="https://github.com/user-attachments/assets/e272867b-8dae-4c84-bc99-d97b7f5163fe" />


<img width="5464" height="2611" alt="IMG-20260702-WA0229" src="https://github.com/user-attachments/assets/6b815c6c-1dfa-49ef-b247-10dda053d73e" />


<img width="1366" height="768" alt="IMG-20260702-WA0231(1)" src="https://github.com/user-attachments/assets/443cb654-b625-4411-8cc4-3d82f322236c" />




























