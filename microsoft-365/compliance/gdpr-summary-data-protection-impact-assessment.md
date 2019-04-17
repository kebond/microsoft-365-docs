# Data Protection Impact Assessment for the GDPR #

The General Data Protection Regulation (GDPR) introduces new rules for organizations that offer goods and services to people in the European Union (EU), or that collect and analyze data for EU residents no matter where you or your enterprise are located. Additional details can be found at [GDPR][GDPRhomeTopic].

This document guides you to information regarding Data Protection Impact Assessments (DPIAs) under the GDPR when using Microsoft products and services.

## What is a DPIA? ##

The GDPR requires controllers to prepare a [Data Protection Impact Assessment (DPIA)][DPIAref] for operations that are “likely to result in a high risk to the rights and freedoms of natural persons.” There is nothing inherent in Microsoft products and services that necessitate the creation of a DPIA; however, because Microsoft products and services are highly-customizable, a DPIA may be needed depending on the details of your Microsoft configuration. Microsoft has no control over, and little or no insight into such information. The data controller must determine appropriate uses of their data.

Microsoft recognizes that controllers are responsible for conducting risk assessments and determining whether a breach requires notification of the customer’s DPA. Microsoft’s notifications will ensure that data controllers are able to meet the GDPR’s breach notification requirements. For more information on breaches, refer to [Breach Notification][summaryDocLink].

GDPR [terms][gdprTerms] that will be helpful in this document:
 * _Data Controller (Controller)_ – A legal person, public authority, agency or other body which, alone or jointly with others, determines the purposes and means of the processing of personal data.  
 * _Personal data_ and _data subject_ – Any information relating to an identified or identifiable natural person (data subject); an identifiable natural person is one who can be identified, directly or indirectly.  
 * _Processor_ – A natural or legal person, public authority, agency or other body which processes personal data on behalf of the controller.  
 * _Customer Data_ – Data produced and stored in the day-to-day operations of running your business.

## DPIA in Action ##

The following guidelines apply to Office 365, Azure, Dynamics 365 and Microsoft Support and Professional Services. Further details relevant to your Microsoft implementation are also provided.

1. _When is a DPIA needed?_
    The risk factors listed below should be addressed when considering whether to complete a DPIA. Other potential factors and further details are found in [Determining Whether a DPIA is Needed][DPIAwhenNeeded].  
     * A systematic and extensive evaluation of data based on automated processing.  
     * Processing on a large scale of special categories of data (data revealing information uniquely identifying a natural person), or of personal data relating to criminal convictions and offences.
     * Systematic monitoring of a publicly accessible area on a large scale.

    The GDPR clarifies “The processing of personal data should not be considered to be on a large scale if the processing concerns personal data from patients or clients by an individual physician, other health care professional or lawyer. In such cases, a data protection impact assessment should not be mandatory.”

1. _What is required to complete a DPIA?_  
     * The GDPR mandates that a DPIA include:  
         * Assessment of the necessity, and proportionality of data processing in relation to the purpose of the DPIA.  
         * An assessment of the risks to the rights and freedoms of natural persons.
         * Intended measures to address the risks, including safeguards, security measures and mechanisms to ensure the protection of personal data and demonstrate compliance with the GDPR.

    These, along with the following list of elements that must be considered, are detailed in [Contents of DPIA][DPIAcontents].  
     * Purpose(s) of processing  
     * Categories of personal data processed  
     * Data retention  
     * Location and transfers of personal data  
     * Data sharing with third-party subprocessors  
     * Data sharing with independent third-parties  
     * Data subject rights

## Additional Considerations ##

Specific details that may be relevant to your Microsoft implementation are below.

 * [Office 365][O365DPIA]: This document applies to Office 365 applications and services, including but not limited to Exchange Online, SharePoint Online, Yammer, Skype for Business, and Power BI. (Refer to Tables 1 and 2 of the [Office 365 Data Subject Requests for the GDPR][O365DSR].)  
 * [Azure][AADDPIA]: Customers are encouraged to work with their privacy officers and legal counsel to determine the necessity and content of any DPIAs related to their use of Microsoft Azure.  
 * [Dynamics 365][D365DPIA]: The contents of a DPIA may vary according to which Dynamics 365 tools you are employing. For specific details refer to [Part 2 – Contents of a DPIA][D365DPIAContents]  
 * [Microsoft Support and Professional Services][MSPSDPIA]: Professional Services does not conduct certain routine or automated data processing, nor is it intended to process special categories or perform tasks that facilitate or require monitoring of publicly accessible data. For details see [Part 1 – Determining Whether a DPIA is needed][MSPSpart1DPIA]. Controllers must consider the DPIA elements outlined above, along with any other relevant factors, in the context of the controller’s specific implementation(s) and use(s) of Professional Services. For Professional Services information see [Part 2 – Contents of a DPIA][MSPSpart2DPIA]

[GDPRhomeTopic]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr?toc=/microsoft-365/enterprise/toc.json

[gdprTerms]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dsr-office365?toc=/microsoft-365/enterprise/toc.json#terminology

[DPIAref]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-data-protection-impact-assessments
[DPIAwhenNeeded]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-office365#part-1--determining-whether-a-dpia-is-needed
[DPIAcontents]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-office365#part-2--contents-of-a-dpia

[O365DPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-office365
[O365DSR]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dsr-office365?toc=/microsoft-365/enterprise/toc.json

[AADDPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-azure

[D365DPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-dynamics
[D365DPIAContents]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-dynamics#part-2--contents-of-a-dpia

[MSPSDPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-prof-services
[MSPSpart1DPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-prof-services#part-1--determining-whether-a-dpia-is-needed
[MSPSpart2DPIA]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dpia-prof-services#part-2--contents-of-a-dpia