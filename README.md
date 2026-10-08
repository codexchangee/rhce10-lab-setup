# 🧪 RHCE RHEL 10 Practice Lab Auto Setup

This repository provides a fully automated setup for an *RHCE RHEL 10 practice lab*.

The setup script configures the required lab nodes, installs the required packages and Ansible collection, creates the `admin` user, deploys the RHCE practice papers and lab files, configures Apache, and prepares the local Git environment.

The complete lab can be deployed using a *single command*.

---

## 🚀 One-Line Installation

Run the following command on the RHEL 10 workstation:

After entering the script enter the student password : student 

*Remember run this scipt with student user only*

```bash
curl -L https://raw.githubusercontent.com/codexchangee/rhce10-lab-setup/main/e.sh | sudo bash

