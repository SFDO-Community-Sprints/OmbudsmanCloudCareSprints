### Project Name
Ombudsman Cloud Care

"Do what you can, with what you have, where you are." ~Theodore Roosevelt

### Project Theme
Welcome Everyone! Ombudsman Cloud Care (OCC) is an Open Source Commons project and a released package. Thank you for volunteering to bring your passion, experience, and technical know-how to the Ombudsman Cloud Care (OCC) project. Your voice is crucial and no contribution is too small. Teamwork makes the dreamwork!

### Feb'21 Sprint Goals
  
1. Refresh Training Scripts & Videos - 8 skill-based videos
  
2. Update Installation Instructions & Tips Documentation - Release 1.2.0
  
3. Create Experience Cloud Documentation - Optional Family Portal 

### Project Vertical
OCC is for use by military ombudsman groups, the volunteers that support military families during deployment.

### OCC GitHub Repo
[SFDO-Community/OmbudsmanCloudCare](https://github.com/SFDO-Community/OmbudsmanCloudCare)

### OCC Power of Us Hub Group
[Community Project - Ombudsman Cloud Care](https://powerofus.force.com/s/group/0F91E0000000hq1SAA/community-project-ombudsman-cloud-care)

### Steering Committee/Tiger Team
[Mary Crozier](https://powerofus.force.com/s/profile/0051E00000GYcPYQA1), Founder

[Michael Kolodner](https://powerofus.force.com/s/profile/00580000009bjBJAAY), App Architect

[Shelley Bolt](https://powerofus.force.com/s/profile/0051E000003jsuzQAA), Salesforce Admin+Ombudsman Success

### Project Team
[Katie Bianco Hernandez](https://powerofus.force.com/s/profile/0051E00000GYmx7QAD)

[Nick Lindberg](https://powerofus.force.com/s/profile/00580000006BbyJAAS)

Laura Etzler

Brittany Dickerson

Liz McCormick

### Feb '21 SFDO Sprint Volunteers
Participants: Michael Kolodner, Shelley Bolt, Laura Etzler, Liz McCormick, Dennis Markunas, Kathy Olney, Allison Roscoe, Bill Florio, Rodney Zhu, and Sprinty

### OCC Community-Driven Vision
OCC is an Open Source Commons application, built by community volunteers to handle Navy Ombudsman (volunteer) needs during crisis and day-to-day operations. With Ombudsman Cloud Care, Ombudsmen have access to a modern, secure, cloud-based case management and a collaboration solution so they will be ready for the regular challenges of deployment and the extraordinary stresses of future crises. 

### Documentation
[OCC Documentation Table of Contents](https://occadminhandbook.bit.ai/docs/view/K9FMWpJOOUACb8T2)

[Handbook](https://occadminhandbook.bit.ai/docs/view/zv0wSuubp84Vnzsq)

[Installation Guide](https://ombudcare.com/installationguide)

[Presentation/White Paper](https://drive.google.com/file/d/1J1ZFsZ2pZaGdE3lKT_NPUxL1KmibO0h1/view?usp=sharing)

[OCC Package Repo](https://github.com/SFDO-Community/OmbudsmanCloudCare)

Listen to OCC Founder, Mary Crozier on the [Salesforce Admin Podcast](https://admin.salesforce.com/blog/2020/ombudsman-cloud-care-with-mary-crozier)


### Project Team Accomplishments
Feb'21 Sprint Accomplishments

1. Updated and tested Release 1.2.0 Installation Instructions.

2. Updated (9) scripts to support new App Release 1.2.0

3. Recorded OCC Metéchō Demo. Presented by Michael Kolodner.  

4. Updated Experience Cloud Documentation to align with Spring '21 Release. Hello Experience Cloud, Farewell Community Cloud.

5. Most importantly, welcomed new community volunteers to the community-driven OCC Team.

[OCC AppExchange Release: 1.2.0 on January 29, 2021](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3u00000OMs0uEAD)

[OCC AppExchange Listing on August 18, 2020](https://appexchange.salesforce.com/appxListingDetail?listingId=a0N3u00000OMs0uEAD&utm_medium=email&utm_source=newsletter&utm_medium=email&utm_campaign=appex_weekly-newsletter&eid=ss-appex-nl)

### Roadmap for Future Development
Examples of what we are planning to develop include:

  • Custom object for use as knowledge base that can be exposed on an Experience Site (object tentatively named Resource).
  
  • Web to Case form for families to request help (available on Experience Site.
  
  • Email to Case for families to request help.
  
  • Web to Lead form that allows family to input information about their sailor, who probably hasn't yet been created in Salesforce.
  
  • Further development of reports an dashboards for ombudsman use and reporting to Command Leadership and central Ombudsman Registry.
  
  • Solution (has to be 100% free) for customer satisfaction survey and the like. 

### Use Considerations
This app is being developed for a very particular “market”: Ombudsman groups supporting Navy commands. In the current form we have made the specific design decision that this will be a Navy-specific app (hence the Sailor__c object) rather than generalizing out to other services. Should the need and/or interest arise from ombudsman-equivalents in the other US services, we foresee creating service-specific products instead of trying to abstract or generalize the current product. That will allow the terminology and other design decisions to be service-specific.

In addition, it should be noted that Navy ombudsmen are volunteers. Though they are organized, trained, and overseen by the command structure they support, they do not have a budget for services nor are the ombudsmen themselves paid. Therefore, one of the main considerations in the development of Ombudsman Cloud Care is that the solution must be absolutely zero cost. Each command ombudsman group will need to apply for a Power of Us license grant, working with a related eligible 501c3 or 501c4 organization to use their eligibility for a Salesforce instance. In many cases this will be the Family Readiness Group (FRG), but some commands without an FRG may need to find other partners. Admin support for each command is expected to come from the Salesforce Military community. Support for the OCC app, responses to questions, etc will come primarily through the OCC Power of Us Hub group. Users and admins of OCC orgs will be strongly encouraged to join the Power of Us Hub and follow the OCC group.

### Development
To work on this project in a scratch org:

1. [Set up CumulusCI](https://cumulusci.readthedocs.io/en/latest/tutorial.html)

2. Run cci flow run dev_org --org dev to deploy this project.

3. Run cci org browser dev to open the org in your browser.

### Thank You For Your Awesome Support
