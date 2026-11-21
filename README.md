# Vulnerability Assessment of a Web Application Using OWASP ZAP

**MSc Electronic and Communications Engineering | Technological University Dublin | 2026**

## Project Overview

This Master's research project evaluates OWASP ZAP for identifying web application vulnerabilities using WebGoat in a controlled, isolated virtual environment.

The assessment involved manual configuration, spidering, passive scanning, active scanning, vulnerability analysis and remediation recommendations.

## Technologies Used

- OWASP ZAP 2.17.0
- OWASP WebGoat
- Ubuntu 24.10
- Oracle VirtualBox
- HTTP/HTTPS Security Testing
- Web Application Vulnerability Assessment

## Experimental Architecture

The environment consisted of two Ubuntu virtual machines connected through an isolated VirtualBox internal network named `THESIS`.

- **VM 1:** WebGoat vulnerable application server
- **VM 2:** OWASP ZAP security assessment workstation

This architecture allowed controlled vulnerability testing without targeting external systems.

## Testing Methodology

1. **Spidering:** Discovered accessible URLs and application resources.
2. **Passive Scanning:** Analysed HTTP requests and responses to identify security weaknesses.
3. **Active Scanning:** Tested discovered resources for potential vulnerabilities.
4. **Manual Analysis:** Reviewed security alerts, severity levels, potential impacts and recommended mitigations.

## Key Results

The assessment identified **12 distinct security alert types**.

| Severity | Alert Types |
|---|---:|
| High | 1 |
| Medium | 4 |
| Low | 3 |
| Informational | 4 |
| **Total** | **12** |

### Notable Findings

- SQL Injection (High Risk)
- Absence of Anti-CSRF Tokens
- Content Security Policy Header Not Set
- Missing Anti-clickjacking Header
- Session ID in URL Rewrite
- Cookie and session security weaknesses

## Key Outcomes

- Successfully configured an isolated two-VM cybersecurity laboratory.
- Conducted three stages of OWASP ZAP security assessment.
- Analysed vulnerability findings and their potential security impacts.
- Documented mitigation recommendations.
- Evaluated the strengths and limitations of vulnerability scanning.

## Project Documentation

The final dissertation, presentation and supporting assessment evidence will be added to this repository.

## Author

**Veera Manikanta Sai Kaja**  
MSc Electronic and Communications Engineering  
Technological University Dublin, Ireland

**Project Supervisor:** Dr. Joseph Kellegher

[GitHub Profile](https://github.com/Veeramanikantasai)
