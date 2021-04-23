# Onboarding Checklist

1. Network Access Info
    *  [MyID](https://profile.myid.disney.com/) - Single Sign On Provider
        *  AD domain: swna
        *  [The Hub](https://enterpriseportal.disney.com) - Gitlab and Chef repo authority
        *  [SOLO](https://confluence.disney.com/display/IDAM/SOLO+User+Documentation+-+Self+Service+Application+Integrations) - MyID cloud replacement
    *  Keystone - Pagerduty
        *  Note: you will need to change your password every 90 days. Best practice to change all three at once.

2. [820 S. Flower, Burbank CA](https://goo.gl/maps/4SqSzkv5hGDWSUHZ8) - Facilities Information
    *  [Condeco](https://disney.condecosoftware.com/) - Desk / Room reservation system
    *  Bunson & Beaker - Lobby tech support

3. Site Account Generation
    *  [Confluence](https://confluence.disney.com/display/DEVSVC/SRE+Shared+Services) - documentation
        *  [List of known Confluence / Jira instances](https://devcentral.disney.com/display/ATL/Known+Atlassian+Instances+throughout+Disney)
        *  [List of known instances per AES](https://confluence.disney.com/display/YODA/Atlassian+Engineering+Environment+Design+Document#AtlassianEngineeringEnvironmentDesignDocument-EnterpriseConfluence)
    *  [Rostr](https://rostr.disney.com/) - company directory
    *  [Supportal](https://supportal.disney.com/) - help desk portal
    *  [Supportal-Jira Sprint Board](https://supportal-jira.disney.com/secure/RapidBoard.jspa?rapidView=88&projectKey=COTS) - for se-devsvc
    *  Git Repos (both maintained as alternatives, used according to team /personal preferences)
        *  [Github Enterprise](https://github.disney.com/) - code repo 
        *  [Gitlab Enterprise](https://gitlab.disney.com/) - main code repo
    *  [Service Now](https://disney.service-now.com/) (SNOW) - help desk portal
    *  [Service Now](https://confluence.disney.com/display/GSST/Service+Now+Training) Training
    *  VPN access
        *  [Backstage Instructions](https://disney.service-now.com/dtoolsitsp?id=kb_article&sys_id=01c2c6e1db407b485a1e41deaa9619a5ckstagepassnewuserinstructions.pdf)
        *  Require OKTA
        *  [Request access form](https://hdforms.disney.com:4431/hdforms2.0/rasrequest.aspx)
    *  Cloud Services Portals
        *  [Cloud Manager](https://manager.cloud.disney.com/) - Corp cloud hosting portal
        *  [Hosting Services](https://hostingservices.corp.disney.com/#/) - Previous cloud hosting portal, additional features
        *  [AWS access](http://aws.corp.disney.com/) - Corp AWS Console Access
        *  [CloudHealth](https://apps.cloudhealthtech.com/) - Cloud Services Usage reporting
        *  [IAM status page](https://trust.iam.disney.com/)
        *  [AWS Status Dashboard](https://status.aws.amazon.com/)
    *  [New Relic](http://newrelic.com/) - Monitoring and alerting
        *  [How to suppress alerts for maintenance work](https://confluence.disney.com/pages/viewpage.action?pageId=457741088)
    *  [PagerDuty](https://dtss.pagerduty.com/) - oncall scheduling
        *  [Add to PagerDuty request form](https://disney.service-now.com/DToolsIT/catalog_detail.do?v=1&sysparm_document_key=sc_cat_item,ae32a291dbd5fa00a256fb541d96194c)
        *  The group is "Developers Service Pod"
    *  [Nexus](https://nexus.disney.com/) - Artifact repo
    *  [DToolsIT](https://inside.disney.com/) - Self Service IT / help desk portal (??? how differentiate from SNOW?)
    *  [AWS-SAML-Auth set up](https://confluence.disney.com/display/DTSSBDE/New+Hire+Onboarding+-+BDE+Engineer+Setup+Guide) - for cli access to AWS accounts
    *  AWS SSM Session Manager CLI (to start and terminate sessions that connect you to your managed instances)
        *  [OSX Install Steps](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html#install-plugin-macos)
        *  [Windows Install Steps](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-working-with-install-plugin.html#install-plugin-windows)
    *  [Time Card reporting](https://augustus.iqnavigator.com/) - IQN

4. Team Specific References
    *  [Runbooks](https://confluence.disney.com/display/DEVSVC/Shared+Services+Runbooks)
    *  [Sprint Dashboard](https://supportal-jira.disney.com/projects/COTS/summary)
    *  [Gitlab Team Repos](https://gitlab.disney.com/se-devsvc)
    *  [Gitlab Terraform Module Repo](https://gitlab.disney.com/tf-modules)
    
5. Slack channels (see on boarding doc, plus:)
    *  disney-aws
    *  gitlab
    *  terraform-general
    *  jira
    *  nexus
    *  announcements 
    *  confluence
    *  bde-monitoring
    *  Requires invites:
        *  aes-aws-working-group
        *  aes-notifications
        *  aes-ops
        *  aes-team
        *  bde-devsvc
        *  bde-security
        *  case-all-team
        *  disney-github
        *  se-devsvc
        *  se-devsvc-we-ddm

6. Acronym / glossary
    *  TTP: Testing Tools Platform - Test with Confidence, Options & Efficiency
    *  AES: Atlassian Engineering Services (devops team dedicated to Jira / Confluence apps)
    *  BDE: Build and Delivery Engineering = gitlab, hub, nexus, jenkins
    *  DDM: Digital Media Agency
    *  Confluence (internal documentation wiki, tied to jira)
    *  DGN: Disney Global Network
    *  Netbond: branded Direct Connect vendor 
    *  GIS: Global Information Security
    *  [RSAM](https://remediation.disney.com): Remediation
    *  [GitLab runner](https://docs.gitlab.com/runner/)
    *  DATG: Disney ABC Television Group
    *  ESS:
    *  PCM: Public Cloud Manager, replaced by Cloud Account Manager (CAM), often referred to as [bespin](https://manager.cloud.disney.com/)

7. Good things to know:
    *  Look before you post. / @ in slack. You may alert a LOT of people around the world.
    *  Stand up mtg format: 2 min max each person.
        *  What I did yesterday
        *  What I will do today
        *  Blockers
    *  Point(s) per ticket .5 for half day, 1 for one day, max 2 points per ticket.

8. Useful online resources
    *  [PCM Review](https://docs.google.com/spreadsheets/d/1aJuOPPd_k0LNoGS5b-cs1KrnAa2hjNfZnSXixnFo2C0/edit#gid=67073469)
    *  [Disney tf_modules](https://gitlab.disney.com/tf-modules)
    *  [Disney DevCentral](https://devcentral.disney.com/)
    *  [SNOW Tips & Tricks](https://confluence.disney.com/pages/viewpage.action?spaceKey=SEABC&title=SNOW+Tips+N+Tricks)
    *  [SSLMonitor](https://sslmonitor.disney.com/report.html)
    *  [Platform & Systems Reliability Engineering Overview](https://disney.slack.com/files/U03RQ9RU9/FHQBDT2F3/platform_engineering_and_sre_-_overview.pdf)
    *  [Key Management as a Service](https://kms-ui.disney-iam.com/)
    *  [DBA Change Request Form](https://disney.service-now.com/nav_to.do?uri=%2Fcom.glideapp.servicecatalog_cat_item_view.do%3Fv%3D1%26sysparm_id%3D7279893b8c110a80bbb230d2496aa0f1%26sysparm_link_parent%3D92fd46016f73f540fa0c0f7c5d3ee4a1%26sysparm_catalog%3De0d08b13c3330100c8b837659bba8fb4%26sysparm_catalog_view%3Dcatalog_default)
    *  [Large File Transfer Service](https://www.relayit.net/)
    *  [GIS Security Configuration Standards](https://infosec.disney.com/policies/configuration-standards/)
    *  [Bluejeans Support](https://support.bluejeans.com/s/contactsupport)
    *  [HP-ALM Runbook](https://confluence.disney.com/display/DEVSVC/HP+ALM)
    *  [HP ALM - configuration details](https://confluence.disney.com/display/DEVSVC/HP+ALM+-+configuration+details)
    *  [TCOE AWS Migration Page](https://confluence.disney.com/pages/viewpage.action?spaceKey=ECSSS&title=TCOE+Parks+-+AWS+Migration#TCOEParks-AWSMigration-Infrastructure)
    *  [TCOE Apps Initialization Steps](https://confluence.disney.com/display/DEVSVC/TCOE+Support)
    *  [Lambda Monitor Functions](https://confluence.disney.com/display/DEVSVC/Lambda+-+Functions+that+Monitor)
    *  [TCOE FlexSRE Runbooks](https://confluence.disney.com/display/ECSSS/Tcoe+Tools+-+Corp+Runbook)
    *  [RSAM - security violation listings.](https://remediation.disney.com/rsam/) Use upper case Hub ID and self register.
    *  [Service Now Dashboard for Config Items](https://disney.service-now.com/nav_to.do?uri=%2Fsys_report_template.do%3Fjvar_report_id%3Daaa124d1db66330484e141a4059619c4)

9. Common Tasks Documentation
    *  [Root Cause Analysis Template](https://confluence.disney.com/display/YODA/RCA+Template)
    *  [Jira & Confluence Operational Procedures](https://confluence.disney.com/display/DEVSVC/JIRA+and+Confluence+Operational+Procedures) - super useful
    *  [Changing SSL Certificates](https://confluence.disney.com/display/YODA/SSL)
    *  [Jira / Confluence AMI upgrade procedures - previous](https://confluence.disney.com/display/DEVSVC/%5Bdeprecated%5D+Jira+and+Confluence+AMI+and+Instance+Type+Update+Procedures)
    *  [Jira / Confluence AMI upgrade procedures - broken](https://confluence.disney.com/display/DEVSVC/JIRA+and+Confluence+AMI+Upgrade+Procedures)
    *  [Moving SSL Certs from Entrust to AWS](https://confluence.disney.com/pages/viewpage.action?pageId=474276067)
    *  [Disable / Enable New Relic Alerts](https://confluence.disney.com/pages/viewpage.action?pageId=457741088)
10. Other Documentation
    *  [Control Catalog definitions](https://infosec.disney.com/policies/twdc-isps-control-catalog/)
    *  [Nexus Environment](https://confluence.disney.com/display/DEVSVC/Nexus+AWS+Environment+details)
    *  [AWS SSL Cert Migration Status](https://confluence.disney.com/display/DEVSVC/Endpoints+in+Scope+for+AWS+Certs)
11. Generate ssh key
12. Upload public key for access to instances
13. Add to /etc/ssh_config for Atlassian server instances name resolution:
```bash
Host atl-*
 Hostname %h.int.sedevsvc.engsvc.go.com
 IdentitiesOnly yes
 IdentityFile ~/.ssh/id_rsa
```
