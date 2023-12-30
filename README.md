
# Terraform folder structure for multi-companies, multi-environemtn setup


dldemotfdirstructure
├─ companies
│  ├─ comp1
│  │  └─ environment
│  │     ├─ prod
│  │     │  ├─ aws
│  │     │  │  ├─ main.tf
│  │     │  │  ├─ output.tf
│  │     │  │  └─ variable.tf
│  │     │  ├─ azure
│  │     │  │  ├─ main.tf
│  │     │  │  ├─ output.tf
│  │     │  │  └─ variable.tf
│  │     │  └─ gcp
│  │     │     ├─ main.tf
│  │     │     ├─ output.tf
│  │     │     └─ variable.tf
│  │     └─ stage
│  │        ├─ aws
│  │        │  ├─ main.tf
│  │        │  ├─ output.tf
│  │        │  └─ variable.tf
│  │        ├─ azure
│  │        │  ├─ main.tf
│  │        │  ├─ output.tf
│  │        │  └─ variable.tf
│  │        └─ gcp
│  │           ├─ main.tf
│  │           ├─ output.tf
│  │           └─ variable.tf
│  ├─ comp2
│  │  └─ environment
│  │     ├─ prod
│  │     │  ├─ aws
│  │     │  │  ├─ main.tf
│  │     │  │  ├─ output.tf
│  │     │  │  └─ variable.tf
│  │     │  ├─ azure
│  │     │  │  ├─ main.tf
│  │     │  │  ├─ output.tf
│  │     │  │  └─ variable.tf
│  │     │  └─ gcp
│  │     │     ├─ main.tf
│  │     │     ├─ output.tf
│  │     │     └─ variable.tf
│  │     └─ stage
│  │        ├─ aws
│  │        │  ├─ main.tf
│  │        │  ├─ output.tf
│  │        │  └─ variable.tf
│  │        ├─ azure
│  │        │  ├─ main.tf
│  │        │  ├─ output.tf
│  │        │  └─ variable.tf
│  │        └─ gcp
│  │           ├─ main.tf
│  │           ├─ output.tf
│  │           └─ variable.tf
│  └─ comp3
│     └─ environment
│        ├─ prod
│        │  ├─ aws
│        │  │  ├─ main.tf
│        │  │  ├─ output.tf
│        │  │  └─ variable.tf
│        │  ├─ azure
│        │  │  ├─ main.tf
│        │  │  ├─ output.tf
│        │  │  └─ variable.tf
│        │  └─ gcp
│        │     ├─ main.tf
│        │     ├─ output.tf
│        │     └─ variable.tf
│        └─ stage
│           ├─ aws
│           │  ├─ main.tf
│           │  ├─ output.tf
│           │  └─ variable.tf
│           ├─ azure
│           │  ├─ main.tf
│           │  ├─ output.tf
│           │  └─ variable.tf
│           └─ gcp
│              ├─ main.tf
│              ├─ output.tf
│              └─ variable.tf
├─ global
│  ├─ main.tf
│  ├─ output.tf
│  └─ variable.tf
├─ modules
│  ├─ aws
│  │  └─ eks
│  │     ├─ main.tf
│  │     ├─ output.tf
│  │     └─ variable.tf
│  ├─ azure
│  │  └─ aks
│  │     ├─ main.tf
│  │     ├─ output.tf
│  │     └─ variable.tf
│  └─ gcp
│     └─ gke
│        ├─ main.tf
│        ├─ output.tf
│        └─ variable.tf
├─ README copy.md
└─ README.md

```