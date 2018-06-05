# Main high-level principles for Application Development (AD)
*	AD0: All developments must comply to Michelin Global Security Requirements  
*	AD1: All applications must comply with application development prescriptions   
*	AD2: Applications developed should comply with development recommendations   
*	AD3: Web-based (thin client) application are preferable over rich / fat clients   
*	AD4: Application must be based on Michelin standard technologies   
*	AD5: Editor package or developed application must not rely on obsolete development or runtime technologies  
*	AD6: Editor package or developed application must comply with “third party and open source component” group policy. Open source software sourcing shall be considered to introduce innovation and / or provide a viable alternative to commercial offerings  
*	AD7: Solution must be OS, Middleware, database, browser agnostic where possible 
*	AD8: Solution must be compliant with the latest version of OWASP Top 10 and OWASP top 10 mobile recommendations


# 1. General rules (all throughout application SDLC)  
## 1.1. Health Check & Audits  

### Prescriptions:

Developer must be able to measure and publish software code quality.

### Recommendations:

*	For new developments scanned on Sonar, SQALE notation must be lower than C, with no blocker or major issue
*	For new developments on Fortify, there must not be any critical or major issue. 
*	The quality is measured through standard software quality automation tools or languages used known to the DCSI/MQ teams. The design documentation can be read by human beings.
The expected quality must be defined and monitored by the developer to maintain the solution depending on the sustainability or lifecycle of the solution: the more the developed application is sustainable, the higher the expected code quality should be.
*	Reviews of the source code must be undertaken regularly.
*	Quality measurement tools (eg. SonarQUBE) must be implemented for each project, this type of tool integrates the security function that enables the verification of the obsolescence of the code, its quality and inherent security in particular for the authentication and session management mechanisms.
*	The technical liability of the projects and maintenance must be anticipated so that any obsolescence can be evaluated and the necessary regular updates are carried out. 


Requirement	Link / Contact
Sonar	https://sonar.michelin.com/sonar/sessions/new?return_to=%2Fsonar%2F

Static code analysis for security	https://mtwiki.michelin.com/xns/display/mtwiki/Application+Vulnerability+Detection

DCSI Code reviews	jerome.godard@michelin.com
	

Attention points:

The elements written as “hard” lead to compatibility problems and security risks.  The quality of the application code contributes to its security, using an obsolete code is a security risk.
