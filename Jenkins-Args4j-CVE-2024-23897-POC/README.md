# Jenkins-Args4j-CVE-2024-23897-POC

A vulnerability in Jenkins (versions 2.441 and earlier, LTS 2.426.2 and earlier) allows attackers to read arbitrary files on the Jenkins controller using the default character encoding.

   - Attackers with `Overall/Read` permission can read entire files.
   - Attackers without `Overall/Read` permission can read up to three lines of a file, depending on available CLI commands.
  
For more information: [Jenkins Security Advisory](https://www.jenkins.io/security/advisory/2024-01-24/)