---
title: Deal Coach Spike — Privacy Policy
---

# Deal Coach Spike — Privacy Policy

**Effective date:** 18 October 2026

This policy explains how **Khandakar Noushadur Rahman**, the independent developer of Deal Coach Spike ("we",
"us"), handles information when your organization uses **Deal Coach Spike**, an extension for Zoho CRM available on the Zoho Marketplace (the "Service").

If you have questions, contact us at **khandakarnoushadurrahman@gmail.com**.

## 1. Our role

- For the **CRM content your users choose to analyze** (deal records, notes, emails and related
  activities), your organization decides what is analyzed and why. We process that content **on
  your organization's behalf** and only to provide the Service.
- For **account and usage information** (for example your organization ID and the number of
  analyses run), we are responsible for it as the provider of the Service.

## 2. Information we process

### 2.1 Deal content you analyze

When a user clicks **Analyze deal**, or when automatic re-analysis is turned on and a user opens a
deal with new activity, the extension reads that deal from Zoho CRM **inside Zoho, with that user's
own CRM permissions**. This can include:

- deal fields (name, stage, amount, dates, owner),
- contact roles and the names and titles of those contacts,
- notes, emails (including their content), calls, tasks and meetings linked to the deal.

This content can contain personal data, such as names, email addresses, job titles and anything
written in emails or notes.

### 2.2 Information we store

| Information                                                                                                                   | Purpose                                                            | Retention                                                           |
| ----------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------- |
| Your Zoho CRM organization ID                                                                                                 | Identify your installation                                         | Until you ask us to delete it (see section 7)                       |
| A one-way hash of your installation's access token (never the token itself)                                                   | Authenticate requests from your CRM                                | Until deletion is requested; replaced when you reinstall            |
| Your organization's Anthropic API key, **encrypted** (AES-256-GCM), and its last 4 characters                                 | Run analyses using your own Anthropic account                      | Until an administrator removes it                                   |
| Your settings (summary note on/off, automatic re-analysis on/off)                                                             | Product behavior                                                   | Until deletion is requested                                         |
| Number of analyses and estimated AI cost per month                                                                            | Usage display and support                                          | Until deletion is requested                                         |
| The result of each analysis (scores, findings, **short quotes** from your records, risks, recommended actions), **encrypted** | Deliver the result to your users (an analysis takes 20–40 seconds) | About **1 hour**, then deleted automatically                        |
| Technical logs (errors, request information)                                                                                  | Operating and securing the Service                                 | A limited period, according to our hosting provider's log retention |

We **do not keep the deal content** (emails, notes and other records) sent for an analysis after the
analysis is finished. Only the result above is kept, briefly.

Zoho does not notify us when an organization uninstalls the extension, so the records above are
not deleted automatically on uninstall. We delete them on request (section 7).

### 2.3 Information stored in your CRM

The Service writes to your own Zoho CRM: the score, status and date of the last analysis on the
deal, and, only if an administrator turns it on, a summary note on the deal. This data stays in
your CRM under your Zoho account and your Zoho settings.

## 3. How we use information

We use the information only to:

- run the analyses your users request and show the results,
- save results to your CRM as described above,
- keep the Service secure, prevent abuse (for example rate limits) and fix problems,
- show your organization its usage.

We **do not** sell personal data, use it for advertising, or use your CRM content to train AI
models.

## 4. Service providers (sub-processors)

| Provider                             | What they do                 | Data involved                     |
| ------------------------------------ | ---------------------------- | --------------------------------- |
| **Zoho Corporation** (Zoho Catalyst) | Hosts and stores the Service | All information in section 2.2    |
| **Anthropic, PBC** (Claude API)      | Performs the AI analysis     | The deal content of each analysis |

Analyses are sent to Anthropic **using your organization's own Anthropic API key**, so they are
processed under your organization's agreement with Anthropic and Anthropic's terms and privacy
policy. Zoho processes data under Zoho's terms and privacy policy. Payments for the extension are
handled by Zoho through the Zoho Marketplace; we do not receive your payment card details.

## 5. International transfers

The Service is hosted on Zoho Catalyst in Zoho's United States data center, and Anthropic processes
analyses in the United States. If you are outside the United States, your data is transferred
there. These transfers rely on the safeguards our service providers offer, such as standard
contractual clauses under their data processing terms.

## 6. Security

- All connections use HTTPS.
- Secrets (your Anthropic API key) and analysis results are encrypted at rest; the encryption key
  is kept only in the Service's protected configuration.
- Each installation can only access its own settings, usage and results.
- Only CRM administrators can change your organization's Anthropic key and settings; the key is
  never shown again after it is saved and is never written to logs.

No method of transmission or storage is completely secure, but we work to protect your information
and will notify affected customers of a security incident as required by law.

## 7. Your choices and rights

- **Remove your Anthropic key** at any time in the extension's settings; it is deleted immediately.
- **Turn off** summary notes and automatic re-analysis in the settings.
- **Delete your organization's records:** email **khandakarnoushadurrahman@gmail.com** from an administrator address
  of your organization with your Zoho CRM organization ID. We delete the records in section 2.2
  within **30 days** and confirm by email.
- Depending on where you live, you or the people whose data is in your CRM may have rights to
  access, correct, delete or restrict the processing of personal data. Because your organization
  controls the CRM content, we will help your organization respond to such requests. Contact us at
  **khandakarnoushadurrahman@gmail.com**.

## 8. Children

The Service is meant for businesses and is not directed to children.

## 9. Changes to this policy

We may update this policy. We will change the effective date above and, for significant changes,
tell installed customers through the Zoho Marketplace listing or by email.

## 10. Contact

**Khandakar Noushadur Rahman**, independent developer of Deal Coach Spike
Dhaka, Bangladesh
khandakarnoushadurrahman@gmail.com
