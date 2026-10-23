from pathlib import Path

content = """# Tanmay Kumar Sahu

**Information Technology Graduate | PGCP-ITISS Trainee at Sunbeam Infotech | IT Infrastructure & Information Security**

I am an Information Technology graduate currently pursuing PGCP-ITISS training at **Sunbeam Infotech**. I am developing a foundation in IT infrastructure management, operating systems, networking, information security, and DevOps, with a particular interest in how reliable systems are operated, monitored, and secured.

Alongside my coursework, I have built Python-based projects involving document intelligence and machine learning. I am now extending that technical background toward infrastructure and security through structured learning and practical labs. The topics below reflect my current learning path; I will add lab evidence and project write-ups as I complete them.

## Connect

- **LinkedIn:** [linkedin.com/in/tanmayksahu62](https://www.linkedin.com/in/tanmayksahu62/)
- **GitHub:** [github.com/Tanmaykumar0162](https://github.com/Tanmaykumar0162)

## PGCP-ITISS Learning Focus

My current course of study covers topics across IT infrastructure, operations, and information security, including:

- **IT Infrastructure & Service Management:** ITIL concepts, service desk, incident and problem management, change management, asset management, and data-centre fundamentals.
- **Systems, Virtualization & Storage:** operating-system concepts, virtualization, storage-area networks, and infrastructure fundamentals.
- **Networking & Network Defence:** firewall concepts, pfSense, Linux `iptables`, packet analysis with Wireshark, VPNs, IDS/IPS concepts, and network monitoring.
- **DevOps & Automation:** Docker, CI/CD concepts, infrastructure provisioning with Chef and Puppet, and monitoring with Prometheus.
- **Information Security & PKI:** cryptography fundamentals, digital certificates, public key infrastructure, TLS/HTTPS, authentication, and access-control concepts.
- **Security Operations & Forensics:** threat detection, incident response, vulnerability assessment, security-log analysis, evidence handling, and cyber-forensics fundamentals.
- **Compliance & Governance:** security controls, audit concepts, and relevant governance and compliance frameworks.

*These are syllabus and learning areas, not a claim that I have mastered or independently implemented every listed technology. I will highlight specific tools as I gain practical experience.*

## Selected Projects

### Enterprise Document Intelligence Chatbot

A Python application that uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from documents and generate context-aware responses.

- **Technologies:** Python, LangChain, ChromaDB, Gemini API, Streamlit
- **Repository:** [Enterprise Document Intelligence Chatbot](https://github.com/Tanmaykumar0162/Enterprise-Document-Intelligence-Chatbot)

### Bridging Traditional Rhythms and Digital DAWs with Machine Learning

A machine-learning project exploring recognition of traditional Tabla patterns and integration with digital audio workflows.

- **Technologies:** Python, PyTorch, Librosa, FastAPI
- **Repository:** [Bridging Traditional Rhythms and Digital DAWs with Machine Learning](https://github.com/Tanmaykumar0162/Bridging-Traditional-Rhythms-and-Digital-DAWs-with-Machine-Learning)

## Current Goals

- Build and document hands-on labs in Linux and network administration.
- Practise network monitoring, firewall configuration, and security-log analysis in controlled lab environments.
- Explore containerization, infrastructure automation, and monitoring tools as covered in my coursework.
- Publish clear lab notes and project documentation so my learning can be reviewed and reproduced.

## Areas of Interest

IT Infrastructure · System Administration · Network Defence · Information Security · DevOps · Cloud Infrastructure

I welcome opportunities to learn from the IT and cybersecurity community, collaborate on practical projects, and grow toward entry-level infrastructure or security roles.
"""

path = Path("/mnt/data/README.md")
path.write_text(content, encoding="utf-8")
print(f"Updated {path} ({path.stat().st_size} bytes)")
