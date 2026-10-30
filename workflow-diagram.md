flowchart TD
    A[Google Forms: Applicant submits application] --> B[Make.com: Processes application]
    B --> C[Airtable: Stores application record]
    C --> D[Twilio WhatsApp: Notifies school]
    C --> E[Gmail: Sends school notification]
    C --> F[Gmail: Sends applicant confirmation]
