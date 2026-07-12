<strong> Automated YouTube SEO Insights Platform </strong>

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
