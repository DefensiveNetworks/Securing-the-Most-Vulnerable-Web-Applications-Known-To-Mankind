# Securing the Most Vulnerable Web Applications Known To Mankind

This repository contains the files and resources for Defensive Networks' "Securing the Most Vulnerable Web Applications Known To Mankind" whitepaper. The whitepaper is a comprehensive study on enhancing web security through the integration of Cloudflare and CrowdStrike, targeting some of the most vulnerable web application and API setups.

## Project Overview

The project aims to test the effectiveness of Cloudflare (WAF) and CrowdStrike against vulnerable web applications and APIs, using DVWA (Damn Vulnerable Web Application) and vAmPI (a vulnerable web API) as test platforms. It involves simulating attacks based on the OWASP Top 10 vulnerabilities to identify potential threats and fine-tune configurations between Cloudflare and CrowdStrike for optimal security.

## Components & Environment Setup

The experiment involves a detailed setup including attacker machines, main attack tools (e.g., Burp Suite, OWASP ZAP, Postman, Cymulate), and the configuration of AWS servers and Docker containers hosting DVWA and vAmPI. The project also utilizes security and monitoring tools like CrowdStrike and Cloudflare WAF to monitor and defend against simulated attacks.

## Attack Simulations

A variety of attack simulations were conducted, including Brute Force Login, Command Injection, Cross-Site Scripting (XSS), SQL Injection, and more, to evaluate the defenses offered by Cloudflare and CrowdStrike. The results showcase the effectiveness of the integrated security measures in protecting vulnerable web applications and APIs.

## Further Reading

For more detailed insights into the whitepaper and its findings, please visit: [Defensive Labs - Securing the Most Vulnerable Web Applications](https://defensive.com/defensive-labs-securing-the-most-vulnerable-web-applications-known-to-mankind/).

