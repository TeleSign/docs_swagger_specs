# OpenAPI (Swagger) Specifications

This repository is for storing all of TeleSign's OpenAPI specifications for its product offerings. 

OpenAPI (formerly known as <a href="https://swagger.io/docs/specification/about/">Swagger</a>*) is an API description format for REST APIs. You can use OpenAPI to describe an entire API, including endpoints, operations available for the end points, parameter input and output, and many authentication methods (but not all). You can write your specification in YAML or JSON, and there are a variety of editors and tools to help you. 

Each API is in its own file, so if you want to use some of TeleSign's APIs for an integration you can grab the ones you want instead of needing to go through a giant single file for the specific APIs you are interested in. 

There are two repositories, Enterprise and Standard. These are based on customer type. The main differences between the customer types are: 
* Enterprise uses rest-ww endpoints and Standard uses rest-api endpoints.
* Enterprise offers many more APIs. 
* You can sign up right away by yourself to try Standard products by going to portal.telesign.com. 
* For Enterprise versions of APIs, if you want to try them, you must currently contact sales. 

# APIs in the Standard Repository 
Standard versions available for use are: 
* SMS API - TeleSign’s SMS API allows you to build communications and account security messaging into web and mobile applications.
* Voice API - TeleSign’s Voice API (Legacy) allows you to build communications and account security voice-based messaging into web and mobile applications.
* Score API - TeleSign’s Score API delivers reputation scoring based on phone number intelligence, traffic patterns, machine learning and a global data consortium. When you submit a request for information about a phone number, you get back all the PhoneID information for the phone number and a score telling you how likely it is the number is used for fraudlent activities.
* PhoneID API - TeleSign’s PhoneID API allows you to collect detailed and actionable global phone number and subscriber data intelligence to strengthen authentications, evaluate fraud risks, and enhance the user experience.

Documentation for Standard products is available at <a href="https://standard.telesign.com">standard.telesign.com</a>.
You can sign up to try these products at <a href="https://portal.telesign.com">portal.telesign.com</a>.

# APIs in the Enterprise Repository
Enterprise versions available for use are: 
* Anonymous SMS API - TeleSign’s Anonymous SMS API allows you to mask phone numbers, safeguarding user identities with anonymized SMS communication experiences between two parties.
* Get Status API 
* Phone Numbers API 
* PhoneID API - TeleSign’s PhoneID API allows you to collect detailed and actionable global phone number and subscriber data intelligence to strengthen authentications, evaluate fraud risks, and enhance the user experience.
* PhoneID with Add-ons API 
* SMS API - TeleSign’s SMS API allows you to build communications and account security messaging into web and mobile applications.
* SMS Verify API - TeleSign’s SMS Verify API lets you send patented, phone-based verification and two-factor authentication using a time-based, one-time passcode sent over SMS.
* Score API - TeleSign’s Score API delivers reputation scoring based on phone number intelligence, traffic patterns, machine learning and a global data consortium. When you submit a request for information about a phone number, you get back all the PhoneID information for the phone number and a score telling you how likely it is the number is used for fraudlent activities.
* Voice API - TeleSign’s Voice API (Legacy) allows you to build communications and account security voice-based messaging into web and mobile applications.
* Voice Verify API - TeleSign’s Voice Verify API allows you to send phone-based verification and two-factor authentication using a one-time passcode sent over message.

Documentation for Enterprise products is available at <a href="https://enterprise.telesign.com">enterprise.telesign.com</a>.

*Frequently during discussions, developers will use Swagger to refer to the specification and the tools for creating the specification. To be clear, Swagger is now used to refer to the open-source tools you can use to work with your specification. For example, you might put your OpenAPI specification into the Swagger Editor to work on writing it. 
