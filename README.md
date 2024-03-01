# DevSecOps

DevSecOps stands for Development, security, and operations. It's an approach culture, automation, and platform design that integrates security as a shared responsibility throughout the IT lifecycle.

## DevSecOps vs DevOps

DevOps isn’t just about development and operations teams. If you want to take full advantage of the agility and responsiveness of a DevOps approach, IT security must also play an integrated role in the full life cycle of your apps.

Why? In the past, the role of security was isolated to a specific team in the final stage of development. That wasn’t as problematic when development cycles lasted months or even years, but those days are over. Effective DevOps ensures rapid and frequent development cycles (sometimes weeks or days), but outdated security practices can undo even the most efficient DevOps initiatives.

Now, in the collaborative framework of DevOps, security is a shared responsibility integrated from end to end. It’s a mindset that is so important, that it led some to coin the term "DevSecOps" to emphasize the need to build a security foundation into DevOps initiatives.

## Shifting left

In the past, security testing was implemented at the end of the development cycle. As the industry evolved and security functions were introduced, security teams would perform various analyses and security testing in the final stages of the lifecycle. 

Depending on the results of security testing, it would either permit the application to proceed for deployment into production or reject the application and pass it back to developers for remediating the flaws identified. This resulted in long delays in development and friction between teams.

Implementing security measures during all stages of the development lifecycle (shifting left) rather than at the end of the cycle will ensure the software is designed with security best practices built in. By detecting security flaws early in development, remediation costs are lower, and there would be no need to roll back changes as they are being addressed on time. This reduces cost, builds trust, and improves the security and quality of the product.

## Software Development Lifecycle

The Software Development Lifecycle is a set of practices comprising a framework to standardize building software applications. SDLC defines the tasks to perform at each software development stage. This methodology aims to improve the quality of the software and the development process to exceed customer expectations and meet deadlines and cost estimates, for example, with customer demand, computing power increases, which raises software costs and developer dependence. SDLC provides a way to measure and improve the development process by providing insights and analyzing each stage, maximizing efficiency and reducing costs.

The set of phases are:

- **Planning**: The planning phase encompasses all aspects of project and product management. This includes resource allocation, project scheduling, cost estimation, etc.
  
- **Requirements Definition**: is considered part of planning to determine what the application is supposed to do and its requirements. For example, a social media application would require the ability to connect with a friend.
  
- **Design & Prototyping**: establishing how the software application will work, programming language, methods to communicate with each other, architecture, etc
  
- **Software Development**: entails building the program, writing code, and documentation.

- **Testing**: In this phase, we ensure components work and can interact with each other. For example, each function works correctly, different parts of the application work seamlessly together, and performance-wise, there are no lags in processing, etc. 

- **Deployment**: in this stage, the application or project is made available to users.

- **Operations & Maintenance**: this is where engineers respond to issues in the application or bugs and flaws reported by users and sometimes plan additional features in future releases.

## CALMS

CALMS, as explained in the Atlassian post, is a framework that assesses a company's ability to adopt DevOps processes. The acronym was coined by Jez Humble, co-author of "The DevOps Handbook," which stands for Culture, Automation, Lean, Measurement, and Sharing.

## DevOps Metrics

During the process of manually creating infrastructure, deployments are blocked. There may be too many errors in the live application, indicating that the security test automation needs to be improved or is taking too much computing power and time. Understanding how and where to find improvement requires metrics to measure your resources. Here are the essential metrics gathered by engineers and the questions it aims to answer:

- Meantime to production (MTTP). What is the turnaround time for newly committed source code?
- Frequency of deployment. What is the frequency of deployment of releases? The average lead time. How long does it take to develop, build, test, and deploy a new feature?
- Speed of deployment. A new release is deployed into production; how long does it take?
- Deployment Agility. You can measure deployment agility by combining deployment speed and frequency.
- Production failure rate. How often do failures occur in production?
- MTTR stands for mean time to recover. What is the recovery time after a failure?
