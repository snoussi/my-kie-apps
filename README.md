# KieApps examples for the Business Automation Openshift operator

## Prerequisites

You will need:

- Openshift 4.6+ up and running
- A new openshift project
- The Business Automation operator installed

## Decision Manager KieApps examples

### DM Trial environments

- [my-decision-svc-trial.yml](my-decision-svc-trial.yml)

### DM Authoring environments

- [my-decision-svc-design-time.yml](my-decision-svc-design-time.yml)
- [my-decision-svc-design-time-cpu-mem.yml](my-decision-svc-design-time-cpu-mem.yml)
- [my-decision-svc-design-time-sso.yml](my-decision-svc-design-time-sso.yml)

  - Decision Central SSO Client config  
    ![Decision Central SSO Client config](img/sso-dc-client.png)

  - Kie Server SSO Client Config:
    ![Kie Server SSO Client config](img/sso-ks-client.png)

### PAM Trial environments

- [my-process-svc-trial.yml](my-process-svc-trial.yml)
