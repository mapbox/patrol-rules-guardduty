# Patrol Rules GuardDuty
These are [patrol rules]() for GuardDuty, which sends the alerts you want to PagerDuty. Patrol is part of Mapbox's security framework.

Currently, there

## Dependencies
This project uses [dispatch]() to route AWS events over to PagerDuty and [lambda-cfn]() to deploy the functions. Only lambda-cfn needs to be installed on the project.

## Deployment Instructions
1. Deploy dispatch.
1. 
