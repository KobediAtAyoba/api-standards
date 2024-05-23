# api-standards
The repository is dedication on displaying and communicating a sample service that is seened and confirmed to be compliant with our proposed api standards. 
https://simfyafrica.atlassian.net/wiki/spaces/TEC/pages/2820964512/Ayoba+API+Governance.

The purpose of the Ayoba API governance is to create a consistent approach to the development of an API across processes, standards, and guidelines while putting compliance mechanisms and measures in place.
API governance activities include planning the development of new APIs and updating current APIs and management of the individual APIs to ensure that service specification updates are consistent with our API best practices, operational principles and guidelines.

3 Parts of the Ayoba API Governance have been defined to support our API development. 

Part One: Components of API best practices

Part Two: API Design, Development and Operation Principles

Part Three: Practical guidelines for RESTful APIs 

Components of API Best Practices
API best practices is a set of specifications and guidelines for developing, managing, and consuming APIs. It is the foundation on which we can build successful APIs. When properly designed and implemented, it helps to ensure that APIs are reliable, secure, scalable, and easy to use.

The most commonly used specifications of API best practices include:

1. Data Model:
A data model encapsulates the structure of the data that will be exchanged between clients and servers through the API. This includes elements such as objects, attributes, and relationships between objects.  Within the context of Ayoba, a data model is required for almost all of our product briefs, whether new or existing changes, our data models should be designed to provide maximum flexibility.

2. Endpoints:
Endpoints allow our mobile client, partners and providers to make requests to our backend server side. A good API architecture should have well-defined endpoints to ensure the correct content type header data is returned for successful response to the request body of http header a given request.

3. Authentication and Authorisation:
This component of an API architecture provides authentication (verifying users are who they say they are) and authorisation (determining what data or actions they can access). Currently this is done differently for varying use cases, depending on the user journeys within payments, mobile client etc. In some cases, other methods such as JWT is utilised, however further in the future, we would consider the use of IDPs. 

4. Versioning:
This component allows for different versions of an API to exist side by side, ensuring that existing mobile applications are not broken when changes are made to major or less major version number of the underlying API codebase. It also allows developers to test new features with the same version number on select group of users before being released to everyone.

5. Analytics and Monitoring:
APIs should be monitored and analysed in order to quickly identify any performance issues or security risks as well as track usage patterns. This helps us make better decisions about our APIs and provide better service for our customers.

By understanding these components and implementing them into an API architecture, we can ensure successful API delivery that is reliable, secure, and easy-to-use. 
