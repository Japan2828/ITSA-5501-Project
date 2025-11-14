 Humber College – ITSA-5501 DevOps Project (Milestone 1)
 Project Overview

This repository was created as part of the ITSA-5501 course to demonstrate practical knowledge of Git and DevOps workflows.
It includes folder structures for Docker, Kubernetes (K8s), and Infrastructure as Code (IaC) that will evolve across project milestones.
Objectives

Understand and apply version control using Git.

Create and manage branches for collaborative work.

Simulate team development using pull requests and merges.

Tag milestones for release tracking.

Prepare for future integration with Docker, CI/CD, and cloud deployment.

Repository Structure
ITSA-5501-Project/
├── docker/          # Dockerfiles and container configurations
├── k8s/             # Kubernetes YAML deployment files
├── iac/             # Infrastructure-as-Code (Terraform/Ansible) scripts
└── README.md        # Project overview and usage

Git Commands Used
git init
git add .
git commit -m "Initial project structure"
git branch -M master
git remote add origin https://github.com/<japan2828>/ITSA-5501-Project.git
git push -u origin master


Branching & Collaboration
git checkout -b experiment
# make edits
git add .
git commit -m "Updated workflow example"
git push origin experiment

Then on Github create a Pull Request>>>>review>>>Merge into master

Tagging Milestone 1

git tag -a v1.0 -m "Milestone 1 complete"
git push origin v1.0

Learning Reflection

This Milestone taughts us how to manage a Git repository effectively, simulate collaborative work, and understand the version control process used in DevOps environments. We learned how to create branches, handle merge conflicts, and maintain a clean project history using tags and structured commits.

Contributors

GROUP 1

Japankumar Pandya
Lakhwinder Singh

