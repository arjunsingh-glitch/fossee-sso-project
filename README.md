# FOSSEE System Administration Task: SSO Server Setup

## Project Overview

This project demonstrates the setup of a Single Sign-On (SSO) server using Keycloak on an AWS EC2 instance. It includes the deployment and integration of three web applications: Drupal 11, a Django project, and a generic PHP application.

**Note on Platform:** The original task specified using a DigitalOcean droplet with Rocky Linux. Due to payment gateway issues, permission was granted by the FOSSEE team to use **AWS Free Tier** as an alternative. Within the AWS Free Tier, a stable version of Rocky Linux 10 was not available, so **Amazon Linux 2023** was used as a close, RHEL-based equivalent to complete the project.

---

## Live URLs

* **Server IP Address:** `http://52.66.54.160`
* **Keycloak Admin Console:** `http://52.66.54.160:8080`
* **Active Application (PHP):** `http://52.66.54.160/login.php`

---

## Technology Stack

* **Cloud Provider:** Amazon Web Services (AWS)
* **Virtual Server:** EC2 t2.micro (Free Tier)
* **Operating System:** Amazon Linux 2023
* **SSO Server:** Keycloak 24.0.4
* **Web Server:** Apache 2.4
* **Database:** MariaDB
* **Languages & Frameworks:** PHP 8.4, Drupal 11, Python 3.9, Django 4.2

---

## Detailed Documentation

Please see the detailed, step-by-step documentation in the `docs` folder:

1.  [Server Setup & Hardening](./docs/01-server-setup.md)
2.  [Keycloak Installation & Configuration](./docs/02-keycloak-setup.md)
3.  [Drupal SSO Integration](./docs/03-drupal-sso.md)
4.  [Django SSO Integration](./docs/04-django-sso.md)
5.  [PHP SSO Integration](./docs/05-php-sso.md)