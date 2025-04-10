```text
      _       _         _____                 _
     | | ___ | |__  _ _|_   _| __ _   _ _ __ (_)_  __
  _  | |/ _ \| '_ \| '_ \| || '__| | | | '_ \| \ \/ /
 | |_| | (_) | | | | | | | || |  | |_| | | | | |>  <
  \___/ \___/|_| |_|_| |_|_||_|   \__,_|_| |_|_/_/\_\
```

![](https://komarev.com/ghpvc/?username=JohnTrunix&color=blueviolet&style=flat-square&label=Profile+Views)
![](https://img.shields.io/github/followers/JohnTrunix?color=blueviolet&label=Followers&style=flat-square)
![](https://img.shields.io/github/stars/JohnTrunix?color=blueviolet&label=Stars&style=flat-square)

```tf
resource "github_profile" "this" {
  name      = "JohnTrunix"
  origin    = "Switzerland"
  languages = ["en_US", "de_CH"]

  roles = toset(["Student", "Working Student"])

  code {
    languages  = ["Python", "JavaScript", "Go", "R"]
    frameworks = ["Angular", "Django", "Flask", "Celery"]
    storage    = ["PostgreSQL", "Redis", "MongoDB"]

    cloud {
      providers = ["AWS"]
      platforms = ["Kubernetes"]
      tools     = ["Terraform"]
    }

    other {
      containers = ["Docker", "Podman"]
      vcs        = ["Git", "Gitlab", "GitHub"]
      ci_cd      = ["GitLab CI", "GitHub Actions"]
    }
  }

  interests = [
    "Open Source",
    "DevOps",
    "Cloud Native",
    "Microservices",
    "Containerization",
  ]

  philosophy = ["Minimalism", "Clean Code", "Declarative Infrastructure"]
}
```
