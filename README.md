![ScreenShot](/screenshots/EF-logo.gif)

# AGN.EF Deployment

Deployment plan, Ant packages, and related issues for EF.


```
+---------+            +----------+              +-----+            +---------+
| AGN.PIG |            | AGN.BETA |              | AGN |            | Victory |
+---------+            +----------+              +-----+            +---------+
     |                      |                      |                     |
     |  EF naming fixes     |                      |                     |
     |--------------------->|                      |                     |  
     |  EF test classes     |                      |                     |
     |--------------------->|                      |                     |
     |  CodeRev/UAT fixes   |                      |                     |
     |--------------------->|                      |                     |          
     |                      |                      |                     |
     |                      |   EF Step 0          |                     |
     |                      |--------------------->|                     |
     |                      |   EF Step 1          |                     |
     |                      |--------------------->|                     |
     |                      |   EF Step 2          |                     |
     |                      |--------------------->|                     |
     |                      |                      |                     |
     |                      |                      |-------------------->|
     |                      |                      | Deployment Validates|
     |                      |                      |<--------------------|
     |                      |                      | Deployment Complete |
     |                      |                      |---------------------|-->
     |                      |                      |                     |
```

## Dates

Key Deployment Dates

* 2014-04-07 - Deployment from AGN.BETA > AGN validates (Assuming test coverage is adequate)
* 2014-04-14 - Deployment complete (Assuming test coverage is adequate)
* 2014-04-21 - EF go-live

## Status

* 2014-03-25: AGN.BETA >> AGN.AntDeploy: Deployed Successfully
* 2014-03-21: Package files separated into 2, validating via retrievals from AGN.BETA.

