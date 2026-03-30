```tf
resource "github_profile" "this" {
  name      = "JohnTrunix"
  origin    = "Switzerland"
  languages = ["en_US", "de_CH"]

  roles = toset(["Student", "Working Student"])

  code {
    languages  = ["Python", "JavaScript", "Go", "R"]
    frameworks = ["Angular", "Django", "FastAPI", "Flask", "Celery"]
    storage    = ["PostgreSQL", "Redis", "MongoDB"]

    cloud {
      providers = ["AWS"]
      platforms = ["Kubernetes", "EKS"]
      tools     = ["OpenTofu"]
    }

    other {
      containers    = ["Docker", "Podman"]
      vcs           = ["Git", "GitLab", "GitHub"]
      ci_cd         = ["GitLab CI", "Argo CD", "GitHub Actions"]
      observability = ["Loki", "Grafana", "Tempo", "Mimir", "Alloy"]
    }
  }

  interests = [
    "Open Source",
    "DevOps",
    "GitOps",
    "Cloud Native",
    "Microservices",
    "Containerization",
  ]

  philosophy = ["Minimalism", "Clean Code", "Declarative Infrastructure"]
}
```
