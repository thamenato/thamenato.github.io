---
company: "InsightM"
role: "Senior Software Engineer"
dateStart: "May 2023"
dateEnd: "Dec 2024"
---

- Helped establish a dedicated Infrastructure team that provided reusable
  Terraform modules for the development teams, by standardizing application
  architectures across the organization, allowing easier deployment to ECS,
  Lambda and supporting infrastructure such as Route53, ACM and S3.

- Refactored previously implemented Terraform by converting it from a single
  monolith module to multiple small and reusable ones, which allowed easier
  maintenance in multiple environments.

- Imported AWS infrastructure created manually via Console (GUI) to Terraform
  and added build pipelines using GitHub Actions / CircleCI for projects that
  required it.

- Used ansible with Ubuntu and nix with NixOS for deploying and configuring
  services to EC2 instances.

- Added code quality validation using GitHub Actions for linting, formatting and
  security and pre-commit hooks to multiple repositories containing Terraform,
  Python and JavaScript code.

- Implemented, from scratch, a build pipeline in GitHub Action for the Report
  generator team, which develops critical-mission services for the company,
  allowing developers to quickly test and deploy only applications that changed
  during their development cycle.

- Worked on security initiatives such as defining database access policies,
  users and roles, also implemented Ansible playbooks to help manage them.

- Participated in on-call rotation.
