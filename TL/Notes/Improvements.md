# Strategy

At the moment we are missing a defined direction of how we want to do support from a technical perspective.

We are looking at tooling, that can help but without a clear view on what we are trying to solve by using these products apart from 'improving alerting & monitoring'

## Goal

By improving
- what we monitor
- how we monitor
- how we handle incidents
- how we handle requests

we want to
- reduce the amount of (manual) work
- imrove the reliability of customer solutions
- improve the response time
- improve our ability to resolve more complex issues

## Current Issues
- Too much manual work
- Response time
- Resolution time
- Follow Up
- Problem management is very limited
- Quality of work
- Lack of technical experience, in depth knowledge


## Improvement Ideas
- Active Problem Management
  - Reduce recurring issues and time spend on these
  - Dedicated resource for problem management. This could be an SRE task but can we wait for this?
  - Remarks
    - Do we have a good view on what problems to tackle, where can we make the biggest gains?
    - Improvements might mean changes in the customer's solution
  - > Reduce manual work
  - > Improve Reliability
  
- Automation
  - In Azure, we can take action on issues by creating workbooks , functions to act when issues occur reducing manual action
  - We need a mindset of more automation. We cshould not execute the same procedure 20 times at a customer if it can be automated
  - > Reduce manual work 
  - > Improve reliability 
  - > Improve response times 
  

- Rework the Alert Engine to make better use of the specific data we get in Azure
   - We loose a lot of possible useful information with the current setup where we need to send emails to the alert mail box
   - > Improve response times
   - > Improve ability to resolve more complex issues
- AI Ops
  - The main goal should be avoid problems before they result in incidents. 
  - In almost any case, to have good results from this solution it will require active management and follow up on alerts. If not, this will result in lots of alerts that will simple be ignored
  - > Improve reliability
  - > Improve response times
  - > Improve ability to resolve more complex issues
- Technical experience & in depth knowledge will only come from handling incidents, resolving problems, analysing issues, doing changes. This requires sufficient time to do this in depth
  - > Improve our ability to resolve more complex issues
  
