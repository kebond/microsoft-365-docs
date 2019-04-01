# GDPR Breach Notification #

Microsoft takes seriously its obligations under the General Data Protection Regulation (GDPR). A security incident/data breach refers to events such as unlawful access to customer’s data stored on Microsoft equipment or in Microsoft facilities, or unauthorized access to such that has the potential to result in the loss, disclosure or alteration of customer data.

This document outlines details actions around Breach Notification (BN). Note that in most cases, Microsoft has the role of data processor; your organization is the data controller.

GDPR [terms][gdprTerms] that will be helpful in this document:
 * _Data Controller (Controller)_ – A legal person, public authority, agency or other body which, alone or jointly with others, determines the purposes and means of the processing of personal data.  
 * _Personal data_ and _data subject_ – Any information relating to an identified or identifiable natural person (data subject); an identifiable natural person is one who can be identified, directly or indirectly.  
 * _Processor_ – A natural or legal person, public authority, agency or other body which processes personal data on behalf of the controller.  
 * _Customer Data_ – Data produced and stored in the day-to-day operations of running your business.

As a data processor, Microsoft will ensure that our customers are able to meet the GDPR’s breach notification requirements as data controllers. Our notification to customers will provide the information needed to make that assessment, along with your GDPR compliance policy. Microsoft will notify customers of any personal data breach, except for those cases where personal data is confirmed to be unintelligible (for example, strongly encrypted data where integrity of the keys is confirmed).

Data controllers are responsible for assessing risks to data privacy and determining whether a breach requires notification of a customer’s DPA. Microsoft will provide the information needed, in conjunction with your GDPR compliance policy, to make that assessment. More information about how Microsoft detects and responds to a breach of personal data in [Data Breach Notification Under the GDPR][dataBreachNotif].

Microsoft is committed to following:
 * Providing the ability to specify a dedicated privacy contact, who will be notified in the event of a breach.  
 * Notifying customers of a personal data breach within 72 hours of a breach being declared. Notification will be done by e-mail to the contact specified by the customer.  
 * Initial notification will include, at least, a description of the nature of the breach, approximate user impact, and mitigation steps (if applicable). If our investigation is not complete at the time of initial notification, we will indicate next steps and timelines for subsequent communication in our initial notification

Microsoft asks _customers_ to do the following regarding our breach notification processes (expanded in [Call to Action for Customers][custCallToAct]):
 * Decide on a contact to receive notifications regarding personal data breach. This contact should be aware of controller requirements under GDPR and be in contact with the organization’s data privacy officers. Tenant administrators will also receive breach notifications and should be aware of requirements under GDPR.  
 * Enter the privacy contact’s e-mail address into the AAD portal.  
    * If customers choose to specify a distribution list for this contact, they should ensure that it is configured to enable receipt of messages from external senders.  
    * If no Global Privacy Contact information is provided, Microsoft will only notify the tenant administrator.

The following details breach notification regarding specific Microsoft products and services.  
1. [Office 365][O365BN]:

    A. Office 365 strongly invests in systems, processes, and personnel to reduce the likelihood of personal data breach and to quickly detect and mitigate consequence of breach if it does occur. These include:  
    1. _Access Control Systems_: Engineers cannot access a service unless explicitly granted permission in response to a specific incident that requires access elevation.  
    1. _Security Monitoring Systems and Automation_: Office 365 maintains robust, real-time security monitoring systems.  
    1. _Personnel and Processes_: Processes and teams responsible for both educating about privacy and incident management processes; and for executing those processes during a breach.

    Additional details can be read at [Office 365 Investments in Data Security][O365investDS].

    B. [What to Expect in the Event of Breach][O365expectWhenBreach]:  
    1. _Consistent incident response life cycle within Office 365_: This includes detailed processes describing how teams should prepare for a data breach, and operate if one does occur.  
    1. _Consistent criteria for notifying customers_: Notification criteria focus on Confidentiality, Integrity, and Availability of customer data. You will be directly notified if either the confidentiality or integrity of customer data is impacted.
    1. _Consistent notification details_: Customers can expect communication regarding data breach to, at a minimum, provide the following details:
        * Timing of the breach and breach awareness  
        * The approximate number of users impacted  
        * The type of user data that was breached  
        * Actions needed to mitigate the breach, by the controller or by the processor  
Data controllers are expected to determine the following:  
        * Breach severity (that is, risk determination)  
        * Whether end users need to be notified  
        * Whether regulators (DPAs) need to be notified

    A customer may become aware of a breach and wish to [contact Microsoft][breachContactMS]. In this case, notify Microsoft Support, which will then interface with engineering teams for more information.

1. [Azure][AADBN]: Security is built into Microsoft Azure through a mandatory process (the [Security Development Lifecycle][AADSecDevLC]) that incorporates privacy-by-design and privacy-by-default methodologies. Microsoft has a global, 24x7 incident response service that works to mitigate the effects of attacks against Microsoft Azure.

    A.  _Detection of Breaches_: Azure services employs a shared responsibility model to define security and operational accountabilities. This is important when discussing security of a cloud service, since both the service provider and the customer have security obligations. Microsoft does not monitor or respond to security incidents within the customer’s realm of responsibility.

    1. Customer incident response may involve collaboration with Azure [customer support][AADcustSup], given appropriate service contracts. Microsoft Azure also offers various services (e.g., [Azure Security Center][AADASC]) that customers can utilize for developing and managing security incident response.  
    1. Azure’s response to potential data breach is guided by the following stages: Detect, Assess, Diagnose, Stabilize and Recover; Close and Post-mortem.

    For a list of events that trigger a breach investigation in Microsoft Azure, see [Detection of Potential Breaches][AADdetPotBrch]. The Microsoft Azure Security Response in the Cloud white paper further details how Microsoft investigates, manages, and responds to security incidents within Azure.

    B.  _Data Breach Response_: Microsoft determines appropriate priority and severity levels of a breach by investigating the functional impact, recoverability, and information impact of the incident. Priority and severity may change over the course of the investigation, based on new findings and conclusions.  
    1.  _Breach Categories_: Privacy Breach, Proprietary Breach, Integrity Loss, None.  
    1. _Security Breach Classifications_: False positive, Security Incident, Customer-Reportable Security Incident, Privacy breach

    Microsoft’s security response team works closely with global legal advisors to help ensure that forensics are performed in accordance with legal obligations and commitments to customers. Microsoft verifies that customer and business risk is successfully contained, and that corrective measures are implemented. Microsoft also follows internal processes to evaluate and update responses as necessary. These processes are detailed in [Azure’s Data Breach Response][AADDBresp].

    C. _Customer Notification_: Microsoft Azure notifies customers and regulatory authorities of data breaches as required. Customer notices are delivered in no more than 72 hours from the time we declared a breach except for the following circumstances:  
    1. Microsoft believes the act of performing a notification will increase the risk to other customers.  
    1. While the goal is to provide impacted customers with an accurate, actionable, and timely notice, to achieve the 72-hour notification commitment the initial notification may not include complete details as all details may not be available during the early stages of a data protection incident.

    Microsoft Azure provides customers with detailed information enabling them to perform internal investigations and assisting them in meeting end user commitments, while not unduly delaying the notification process. Notification of a personal data breach will be delivered to the customer by any means Microsoft selects, including via email. Further details are in [Customer Notification][AADCustNotf].

1. [Dynamics 365][D365BN]: Breach Notification is handled as described above for Azure.

1. [Microsoft Support and Professional Services][MSPSBN]: The nature of professional services means some data protection incidents may fall within the customer’s realm of responsibility. When Microsoft Professional Services identifies a data protection incident, it follows documented industry standard response plan as outlined in [Scope & Limits of Data Protection Incident Response Process][MSPSscopeLim].  

    When providing notice to customers of a personal data breach, Microsoft will include the following information, if applicable and known:  
     * Nature of the breach
     * Mitigation measures Microsoft is taking or proposing
     * Product, service, application involved
     * Length of time personal data was exposed, if known
     * Volume of affected/exposed personal data records, if known
     * Sub-processor/supplier details, if one is involved in the breach

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
[AADDBresp]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json#azures-data-breach-response
[AADCustNotf]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-azure?toc=/microsoft-365/enterprise/toc.json

[D365BN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-dynamics365?toc=/microsoft-365/enterprise/toc.json

[MSPSBN]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-microsoft-support-professional-services?toc=/microsoft-365/enterprise/toc.json
[MSPSscopeLim]: https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-breach-microsoft-support-professional-services?toc=/microsoft-365/enterprise/toc.json#scope--limits-of-data-protection-incident-response-process