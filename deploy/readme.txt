=========================================================================================
├── roles
│   ├── base
│   │   ├── tasks
│   │   │   └── main.yml
│   │   └── vars
│   │       └── main.yml
│   └── nginx
│       ├── defaults
│       │   └── main.yml
│       ├── files
│       │   ├── index.html
│       │   └── main.yml
│       ├── handlers
│       │   └── main.yml
│       ├── meta
│       │   └── main.yml
│       ├── tasks
│       │   ├── configure.yml
│       │   ├── install.yml
│       │   ├── main.yml
│       │   └── service.yml
│       └── templates
│           └── default.conf.j2
├── site.yml
├── www.retry
└── www.yml
==========================================================================================

1. Install nginx
2. Configure

Using roles, fatcs, variable, defaults, templates
