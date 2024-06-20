# what-i-learn-about-devops
here u can see what i understand from my college
│
├── .github/
│   ├── workflows/
│   │   └── ci-cd.yml
│   └── ISSUE_TEMPLATE.md
│
├── infrastructure/
│   ├── terraform/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── outputs.tf
│   └── ansible/
│       ├── playbook.yml
│       └── roles/
│           ├── webserver/
│           │   ├── tasks/
│           │   │   └── main.yml
│           │   ├── handlers/
│           │   │   └── main.yml
│           │   └── templates/
│           │       └── nginx.conf.j2
│           └── database/
│               ├── tasks/
│               │   └── main.yml
│               └── handlers/
│                   └── main.yml
│
├── app/
│   ├── Dockerfile
│   ├── docker-compose.yml
│   ├── src/
│   │   ├── main.py
│   │   └── requirements.txt
│   └── tests/
│       └── test_main.py
│
├── monitoring/
│   ├── prometheus.yml
│   └── grafana_dashboard.json
│
├── scripts/
│   ├── setup.sh
│   └── deploy.sh
│
└── README.md

