# Google Secret Manager PAM Provider

The Google Secret Manager PAM Provider allows for the use of a Secret Manager instance in Google Cloud to be used as a credential store for Keyfactor. Secret values can be retrieved and used in the Keyfactor Platform as passwords or other sensitive fields.

#### Integration status: Prototype - Demonstration quality. Not for use in customer environments.

## About the Keyfactor PAM Provider

Keyfactor supports the retrieval of credentials from 3rd party Priviledged Access Management (PAM) solutions. Secret values can normally be stored, encrypted at rest, in the Keyfactor Platform database. A PAM Provider can allow these secrets to be stored, managed, and rotated in an external platform. This integration is usually configured on the Keyfactor Platform itself, where the platform can request the credential values when needed. In certain scenarios, a PAM Provider can instead be run on a remote location in conjunction with a Keyfactor Orchestrator to allow credential requests to originate from a location other than the Keyfactor Platform.

---



