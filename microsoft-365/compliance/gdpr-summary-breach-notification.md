# GDPR Breach Notification #

The General Data Protection Regulation (GDPR) introduces new rules for organizations that offer goods and services to people in the European Union (EU), or that collect and analyze data for EU residents no matter where you or your enterprise are located. Additional resources can be found at [GDPR][GDPRhomeTopic].

This document leads you to information on the completion of Breach Notifications under the GDPR using Microsoft products and services.

GDPR [terms][gdprTerms] that will be helpful in this document:
 * _Data Controller (Controller)_ – A legal person, public authority, agency or other body which, alone or jointly with others, determines the purposes and means of the processing of personal data.  
 * _Personal data_ and _data subject_ – Any information relating to an identified or identifiable natural person (data subject); an identifiable natural person is one who can be identified, directly or indirectly.  
 * _Processor_ – A natural or legal person, public authority, agency or other body which processes personal data on behalf of the controller.  
 * _Customer Data_ – Data produced and stored in the day-to-day operations of running your business.

## What is a Data Breach? ##

Personal data is information related to an identified, or identifiable person. A breach of data security affects the confidentiality, integrity or availability of personal data. This includes the accidental or unlawful loss, alteration, access to or unauthorized disclosure of that data.

## Microsoft and Breach Notification ##

Microsoft takes its obligations under the General Data Protection Regulation (GDPR) seriously. A security incident/data breach refers to events such as unlawful access to customer’s data stored on Microsoft equipment or in Microsoft facilities, or unauthorized access to such that has the potential to result in the loss, disclosure or alteration of customer data.

As a data processor, Microsoft will ensure that our customers are able to meet the GDPR’s breach notification requirements as data controllers. Our notification will provide the information needed to make that assessment. Microsoft will notify customers of any personal data breach, except for those cases where personal data is confirmed to be unintelligible (for example, strongly encrypted data where integrity of the keys is confirmed).

Data controllers are responsible for assessing risks to data privacy and determining whether a breach requires notification of a customer’s DPA. Microsoft will provide the information needed, in conjunction with your GDPR compliance policy, to make that assessment.

Initial notification will include, at least, a description of the nature of the breach, approximate user impact, and mitigation steps (if applicable). If our investigation is not complete at the time of initial notification, we will indicate next steps and timelines for subsequent communication. More information about how Microsoft detects and responds to a breach of personal data in [Data Breach Notification Under the GDPR][dataBreachNotif].

Additional information that Microsoft will include in a breach notification, if applicable and known:
 * Nature of the breach
 * Mitigation measures Microsoft is taking or proposing
 * Product, service, application involved
 * Length of time personal data was exposed, if known
 * Volume of affected/exposed personal data records, if known
 * Sub-processor/supplier details, if one is involved in the breach

## Additional Considerations ##

Details regarding breach notification for specific Microsoft products and services is given below.
  
1. [Office 365][O365BN]:  
    Microsoft invests extensively in systems, processes, and personnel to reduce the likelihood of personal data breach and to quickly detect and mitigate consequence of breach if it does occur. Additional details can be read at [Office 365 Investments in Data Security][O365investDS].

    A customer may become aware of a breach and wish to contact Microsoft. In this case, notify Microsoft Support, which will then interface with engineering teams for more information.

2. [Azure][AADBN]:  
    Microsoft has a global, 24x7 incident response service that works to mitigate the effects of attacks against Microsoft Azure.

    * _Detection of Breaches_: Since both Microsoft and the customer have security obligations, Azure services employs a shared responsibility model to define security and operational accountabilities. Microsoft does not monitor or respond to security incidents within the customer’s realm of responsibility. Note that customer incident response may involve collaboration with Azure [customer support][AADcustSup], given appropriate service contracts. Microsoft Azure also offers various services (e.g., [Azure Security Center][AADASC]) that customers can utilize for developing and managing security incident response.

        For a list of events that trigger a breach investigation in Microsoft Azure, see [Detection of Potential Breaches][AADdetPotBrch]. The [Microsoft Azure Security Response][AADBresp] in the Cloud white paper further details how Microsoft investigates, manages, and responds to security incidents within Azure.


    *   _Data Breach Response_: Microsoft determines appropriate priority and severity levels of a breach by investigating the functional impact, recoverability, and information impact of the incident. Priority and severity may change over the course of the investigation, based on new findings and conclusions.
    Microsoft’s security response team works closely with global legal advisors to help ensure that forensics are performed in accordance with legal obligations and commitments to customers. These processes are detailed in [Azure’s Data Breach Response][AADBresp].

    * _Customer Notification_: Microsoft Azure notifies customers and regulatory authorities of data breaches as required. Customer notices are delivered in no more than 72 hours from the time we declared a breach except for the following circumstances:  
        1. Microsoft believes the act of performing a notification will increase the risk to other customers.  
        1. 	The 72 hour timeline may leave some incident details available. These will be provided to you as the investigation proceeds.

        Further details can be found in [Customer Notification][AADCustNotf].

1. [Dynamics 365][D365BN]:  
    Breach Notification is handled as described above for Azure.

1. [Microsoft Support and Professional Services][MSPSBN]:  
    The nature of professional services means some data protection incidents may fall within the customer’s realm of responsibility. When Microsoft Professional Services identifies a data protection incident, it follows documented industry standard response plan as outlined in [Scope & Limits of Data Protection Incident Response Process][MSPSscopeLim].

[GDPRhomeTopic]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr?toc=/microsoft-365/enterprise/toc.json
[gdprTerms]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dsr-office365?toc=/microsoft-365/enterprise/toc.json#terminology

[dataBreachNotif]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-notification?toc=/microsoft-365/enterprise/toc.json
[custCallToAct]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-office365#call-to-action-for-customers
[O365BN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-office365?toc=/microsoft-365/enterprise/toc.json
[O365investDS]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-office365#office-365-investments-in-data-security
[O365expectWhenBreach]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-office365#what-to-expect-in-the-event-of-breach
[breachContactMS]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-office365#contacting-microsoft

[AADBN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json
[AADSecDevLC]: https://www.microsoft.com/sdl/
[AADcustSup]: https://azure.microsoft.com/support/options/
[AADASC]: https://azure.microsoft.com/services/security-center/
[AADdetPotBrch]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json#detection-of-potential-breaches
[AADBresp]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json#azures-data-breach-response
[AADCustNotf]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json

[D365BN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-dynamics365?toc=/microsoft-365/enterprise/toc.json

[MSPSBN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-microsoft-support-professional-services?toc=/microsoft-365/enterprise/toc.json
[MSPSscopeLim]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-microsoft-support-professional-services?toc=/microsoft-365/enterprise/toc.json#scope--limits-of-data-protection-incident-response-process