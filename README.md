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

4. Acronym / glossary
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
