# Easy Up

Easy Up is a suite of tools for quickly provisioning and managing cloud application deployments for containerized workloads across multiple cloud providers and CI/CD platforms.

## Portage CD

[Portage CD](https://github.com/easy-up/portage-cd) is a CLI tool that [carries](https://www.merriam-webster.com/dictionary/portage) your application from source code to container registry. It leverages open source code quality and security tools to ensure your application code meets a high standard before being merged or deployed. One of the biggest advantages of using `Portage CD` is that it decouples much of the logic of orchestrating different tools and steps in the continuous delivery process from your CI/CD platform. This gives you portability between different CI/CD platforms, and it provides a repeatable build process that you can run locally with the same effect as running it in a CI environment.

### Portage CD GitHub Actions

Portage CD is available as a [set of GitHub Actions](https://github.com/easy-up/portage-cd-actions) make it easy to use if GitHub is your CI/CD platform of choice.

## Gatecheck

[Gatecheck](https://github.com/easy-up/gatecheck) is a CLI tool for processing the output of a variety of open source code quality and security scanning tools. This simplifies the process of defining, enforcing, and monitoring policies for acceptable risks in your code.

## SightGlass

[SightGlass](https://github.com/easy-up/SightGlass) is a continuous monitoring and alerting to that ensures your application endpoints and microservices are always reachable and responsive. It can perform HTTP health checks against either internal or public endpoints, determining health based on a variety of rules. SightGlass also integrates with a variety of logging and application performance metrics tools to determine health status, as well as integrating directly with hosting platforms such as Kubernetes.

## TBD Tools for Provisioning and Managing Infrastructure