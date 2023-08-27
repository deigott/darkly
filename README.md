# Darkly Web Security Project
<img src="https://bs-uploads.toptal.io/blackfish-uploads/components/seo/content/og_image_file/og_image/1283513/cover-Redesign-WebSecurityVulnerabilities-Luke_Newsletter-04d5cdafdaf363f0bc6aa723a391c343-91ee4d294318c967b26187f4d67a8351.png">
## Introduction
Welcome to my Darkly web security project repository! This is where I've documented my journey through the exciting world of web security. In this project, I delved into various vulnerabilities and risks that websites can face on the World Wide Web, and I'm excited to share my findings and solutions with you.

## Project Summary
Darkly is a captivating web security project that provided me with hands-on experience in understanding and mitigating web vulnerabilities. The project involved auditing a simple website that showcased real-world breaches, some of which are still prevalent on established websites.

## Table of Contents
- [Introduction](#introduction)
- [Project Summary](#project-summary)
- [Vulnerabilities Explored](#vulnerabilities-explored)
- [My Approach](#my-approach)
- [Achievements](#achievements)
- [Challenges Faced](#challenges-faced)
- [Lessons Learned](#lessons-learned)

## Vulnerabilities Explored
Throughout the Darkly project, I encountered and successfully tackled various vulnerabilities, including:
- Admin (htpasswd) breach
- BruteForce attack
- Cookies manipulation
- Email recovery breach
- File upload bypass
- Local File Inclusion (LFI)
- Persistent Cross-Site Scripting (XSS)
- Recursive scraping vulnerability
- Referer header bypass
- SQL injection (advanced and basic)
- Survey Insecure Direct Object References (IDOR)
- URL Redirection vulnerabilities
- XSS using the OBJECT tag

## My Approach
I approached the project with a combination of careful analysis, research, and experimentation. Each vulnerability required a unique approach, and I had to dig deep into cybersecurity concepts and techniques to understand and exploit them.

## Folder Structure
To organize my work, I structured my repository as follows:

```bash
$> ls -al
drwxr-xr-x {Breach name} # Folder for each breached vulnerability
```
Inside each `{Breach name}` folder:

```bash
$> ls -alR {Breach name}
{Breach name}:
..
-rw-r--r-- flag                # File containing the captured flag for the breach
drwxr-xr-x Ressources          # Resources folder for supporting explanations

{Breach name}/Ressources:
..
-rw-r--r-- whatever.wahtever   # Supporting resource file
```
I've also included write-ups for each breach inside their respective folders.

## Achievements
Throughout the project, I successfully:
- Explored various vulnerabilities and understood their implications.
- Developed solutions to breach each vulnerability.
- Documented my findings, solutions, and the steps I took to exploit these vulnerabilities.

## Challenges Faced
While working on Darkly, I encountered some challenges:
- Navigating complex vulnerabilities and understanding their intricacies.
- Ensuring my explanations were clear and comprehensive for each vulnerability.
- Balancing time constraints and the in-depth exploration needed for each breach.

## Lessons Learned
Darkly was an eye-opening experience that taught me:
- The critical importance of web security in the development process.
- The significance of tools like OWASP in ensuring secure web applications.
- The need to carefully consider and address potential vulnerabilities at every stage.

## Disclaimer
Please note that the vulnerabilities discussed in this repository were exploited for educational purposes as part of the Darkly project. My intent is to share knowledge and raise awareness about web security challenges.

Feel free to reach out if you have any questions or insights to share!
