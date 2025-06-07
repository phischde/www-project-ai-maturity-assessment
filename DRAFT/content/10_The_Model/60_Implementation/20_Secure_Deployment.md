### Secure Deployment

#### Objectives

Ensure resilient and compliant deployment of AI components by enforcing access control, monitoring, fallback strategies, and regulatory alignment.

| **Maturity Level** | **Stream A – Process-Oriented**                                                                                   | **Stream B – Technical Controls**                                                                                     |
|--------------------|:------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| **Level 1**        | **AI Deployment Documentation**:<br>- Document configurations and environments.<br>- Record runtime dependencies. | **Basic Runtime Monitoring**:<br>- Monitor model performance.<br>- Log input/output.<br>- Track usage metrics.        |
| **Level 2**        | **Deployment Governance**:<br>- Define approval workflows.<br>- Establish rollback mechanisms and audits.         | **Access and Protection Controls**:<br>- Restrict and log access.<br>- Encrypt sensitive model data.                  |
| **Level 3**        | **Continuous AI Compliance**:<br>- Assess legal and regulatory compliance.<br>- Automate compliance checks.       | **Resilience and Fail-Safes**:<br>- Implement fallbacks.<br>- Monitor drift and hallucinations.<br>- Enable alerting. |

Secure deployment of AI requires organizations to recognize that models do not behave as static software artifacts but evolve over time. Therefore, deployment strategies must account for model drift, environmental changes, and real-world adversarial conditions. Continuous operational monitoring and governance are vital to ensure that deployed AI systems remain effective, fair, and secure throughout their lifecycle.

