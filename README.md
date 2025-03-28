# Awesome Cloud Security Labs
A curated list of free cloud-native security learning labs. Includes Capture The Flag (CTF) challenges, self-hosted workshops, guided vulnerability labs, and research labs.

### Created and researched by Prof. (Dr.) Ajay Shriram Kushwaha

## Sorted by Technology and Category

| **Name**                           | **Technology**      | **Category**                          | **Author**                     | **Notes**                                                                                              |
|------------------------------------|---------------------|---------------------------------------|--------------------------------|--------------------------------------------------------------------------------------------------------|
| CloudFoxable                       | AWS                 | Self-hosted CTF Challenge             | Seth Art                       | Create your own vulnerable by design AWS penetration testing playground                                 |
| Pwned Labs                         | AWS                 | Author-hosted Guided Labs, CTF       | Ian Austin                    | Requires account registration; Commercial paid subscriptions; free hosted labs for learning cloud security |
| The Big IAM Challenge              | AWS                 | Author-hosted CTF Challenge          | Wiz                            | CTF challenge to identify and exploit IAM misconfigurations                                            |
| CloudSec Tidbits                   | AWS                 | Self-hosted Challenge                | Doyensec                       | Three web app security flaws specific to AWS cloud, self-hosted with terraform                          |
| AWS Well-Architected Security Workshop | AWS             | Self-hosted, guided labs             | AWS Well-Architected           | Hands-on-labs to help you improve the security of your architecture using AWS security best practices    |
| AWS CIRT Workshop                  | AWS                 | Self-hosted, guided lab              | AWS CIRT                       | Explore 5 common incident response scenarios observed by AWS CIRT                                       |
| CloudGoat                          | AWS                 | Self-hosted, guided vulnerability lab| Multiple, Rhino Security Labs | Python orchestration of terraform                                                                      |
| Attacking and Defending Serverless Applications | AWS  | Self-hosted, guided vulnerability workshop | Ryan Nicholson  | Attack and defend a Lambda that you build in your own AWS account with terraform                       |
| IAM Vulnerable                     | AWS                 | Self-hosted, guided vulnerability lab| Seth Art                       | IAM-focused priv esc playground with 31 attack pathways                                                |
| flaws.cloud                        | AWS                 | Author-hosted, CTF challenge         | Scott Piper                    | Challenge style with levels and clues                                                                  |
| flaws2.cloud                       | AWS                 | Author-hosted, CTF challenge         | Scott Piper                    | Attacker and Defender paths in a challenge style                                                       |
| CI/CDon't                          | AWS                 | Self-hosted CTF walkthrough          | Nick Frichette                 | Vulnerable CI/CD CTF infrastructure, hosted in your own AWS account with terraform                      |
| AWSGoat                            | AWS                 | Self-hosted, attack and defense manuals | Multiple, ine-labs           | Build with terraform, provides attack and defense manuals                                             |
| Sadcloud                           | AWS                 | Self-hosted                          | Multiple, NCC Group            | Terraform code, not guided like CloudGoat                                                               |
| DVCA                               | AWS                 | Self-hosted demo lab                 | Maxime Leblanc                 | Deploy a Damn Vulnerable Cloud Application to practice privilege escalation                            |
| lambhack                           | AWS                 | Self-hosted lab                      | James Wickett                  | Deploy a vulnerable AWS lambda serverless application in your AWS account                              |
| BadZure                            | Azure               | Self-hosted lab                      | Mauricio Velazco               | Powershell Graph SDK script to spin up an Azure AD lab with attack paths                               |
| Broken Azure                       | Azure               | Author-hosted, CTF challenge         | Secura                         | Vulnerable by design Azure infrastructure that you can attack                                          |
| Mandiant Azure Workshop            | Azure               | Self-hosted, guided commands         | Multiple                       | Vulnerable by design Azure lab with two scenarios; build with terraform                                |
| AzureGoat                          | Azure               | Self-hosted, attack and defense manuals | Multiple, ine-labs           | Build with terraform, provides attack and defense manuals                                             |
| XMGoat                             | Azure               | Self-hosted, guided labs             | Multiple                       | Build with terraform, 5 scenarios, solution docs provided                                             |
| CONVEX                             | Azure               | Self-hosted, CTF                     | Multiple                       | Spin up three CTF environments in your Azure tenant using powershell                                   |
| GCP CTF Workshop                   | GCP                 | Self-hosted, lab guide               | Marion Säckel, Marcus Hallberg | Build with terraform using bash script, hints and solutions provided                                  |
| GCP Goat (Josh Jebaraj)            | GCP                 | Self-hosted, mdbook lab guide        | Josh Jebaraj                   | Build in your GCP account with provided scripts, guided lab workbook                                   |
| GCPGoat (ine-labs)                 | GCP                 | Self-hosted, attack and defense manuals | Multiple, ine-labs           | Build with terraform, attack and defense manuals provided                                            |
| Thunder CTF                        | GCP                 | Self-hosted, CTF                     | Multiple                       | Practice attacking vulnerable GCP projects across 6 levels                                            |
| K8s Lan Party                      | Kubernetes          | Author-hosted, CTF challenge         | Wiz                            | Exploit vulnerabilities and misconfigurations in a Kubernetes cluster                                 |
| EKS Cluster Games                  | Kubernetes          | Author-hosted, CTF challenge         | Wiz                            | Vulnerable EKS pod challenges with leaderboard, registration required                                 |
| Bustakube                          | Kubernetes          | Self-hosted, import VMs              | Jay Beale                      | Download a vulnerable K8S cluster as VMs and import into VMware for local testing                     |
| Kubernetes Goat                    | Kubernetes          | Self-hosted, multi-cloud, K3S       | Madhu Akula                    | Host in your cloud (GKE, EKS, AKS) or K3S, includes a guided workbook                                 |
| Kubecon NA 2019 CTF                | Kubernetes          | Self-hosted in GKE                   | Multiple                       | Guided workbook with attack and defense scenarios in GCP                                             |
| Kube Security Lab                  | Kubernetes          | Local, kubernetes in docker          | Rory McCune                    | Local lab to create vulnerable Kubernetes clusters using Docker, Ansible, and Kind                    |
| Container Security 101             | Container           | Self-hosted, guided workshop        | Jon Zeolla                     | Host in your AWS account, guided vulnerability workshop                                              |
| Contained.af                       | Container           | Self-hosted Challenge                | Jessie Frazelle                | Break out of a container and email the author                                                          |
| TerraGoat                          | Terraform           | Self-hosted, multi-cloud             | Multiple, Bridgecrew           | Vulnerable by design terraform repository                                                             |
| PurpleCloud                        | Azure               | Research Lab                        | Jason Ostrom                   | Build your own Azure security lab with python and terraform                                            |
| SimuLand                           | Azure               | Research Lab                        | Roberto Rodriguez               | Create your own Azure security lab using Azure RM templates                                           |
| CNAPPgoat                          | AWS, Azure, GCP     | Research Lab                        | Ermetic Research               | Modularly provision vulnerable components in AWS, GCP, Azure using Pulumi                            |
| CI/CD Goat                         | CI/CD               | CTF, local docker                   | Palo Alto                      | Vulnerable CI/CD environment for hacking CI/CD pipelines                                             |
| Github Actions Goat                | CI/CD               | Self-hosted Github                  | StepSecurity                   | Vulnerable Github Actions CI/CD environment hosted in your Github account                             |

---

## Notes
1. Labs are organized by their respective technology and category.
2. Some resources may require a registration or the use of your own cloud account (AWS, Azure, GCP, etc.).
3. Most labs include detailed instructions, scripts, and guides for setting up and completing challenges.

Feel free to explore these labs, contribute to this list, or reach out with any feedback!

### Contact
Feel free to contact Prof. (Dr.) Ajay Shriram Kushwaha at [kushwaha.ajay22@gmail.com](mailto:kushwaha.ajay22@gmail.com).
