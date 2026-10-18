# Deal Coach Spike — user guide

Deal Coach Spike scores your Zoho CRM deals against the MEDDIC framework and shows the exact evidence
behind every finding.

**Requirements:** Zoho CRM Enterprise edition or higher, and an Anthropic API key.

## 1. Set up (admin, once)

1. Install Deal Coach Spike from the Zoho Marketplace.
2. Create an API key at **console.anthropic.com → API keys**. Analyses are billed by Anthropic to
   this account (about $0.05 per analysis).
3. In Zoho CRM, open the Deal Coach Spike settings page ([Setup → Marketplace → installed extensions → Deal Coach Spike → Settings]), paste the key and click **Save key**. It is checked with Anthropic, stored encrypted, and only its
   last 4 characters are shown afterwards.
4. Optional, on the same page:
   - **Post a summary note on the deal after each analysis** (off by default).
   - **Re-analyze a deal automatically when it is opened and has new activity** (off by default).
5. Make the **Deal Coach** tab visible to the profiles that should use it (managers, sales ops).

## 2. Analyze a deal

1. Open a deal and find the **Deal Coach Spike** section.
2. Click **Analyze deal**. It takes 20–40 seconds.
3. You see:
   - **Score** out of 100 and a status: **On track**, **Needs attention** or **At risk** (any MEDDIC
     element at risk, or a score below 34).
   - **Six cards**, one per MEDDIC element: Confirmed, Partial, Unknown or Risk, a short summary, the
     **quotes** it is based on (with the source record, date and author), what is missing, and a
     next step.
   - **Top risks** and **recommended actions**.
4. The score, status and date are saved to the deal's **Deal Coach** fields, so you can use them in
   views, reports and workflows.

"Unknown" means there is no evidence in the CRM yet — log the information you have (notes, emails,
meetings) and analyze again.

## 3. Pipeline view (managers)

Open the **Deal Coach** tab:

- Open deals, most urgent first: At risk → Needs attention → Not analyzed → On track.
- Filter by owner, stage and status.
- **new activity** marks deals that changed since their last analysis.
- Click a deal name to open it; click **Re-analyze** to refresh one deal.

You only see deals your CRM permissions allow.

## 4. Usage

Your subscription includes unlimited analyses. The settings page shows how many analyses your
organization ran this month and in earlier months, with an estimate of the Anthropic cost.

## 5. Troubleshooting

| Message                                                 | What to do                                                        |
| ------------------------------------------------------- | ----------------------------------------------------------------- |
| "No Anthropic API key is set for your organization yet" | An admin adds the key in Settings.                                |
| "Anthropic rejected this API key"                       | Create a new key in the Anthropic console and save it again.      |
| "Analysis limit reached (30 per hour)"                  | Try again later.                                                  |
| "Score not saved to the deal: …"                        | Check that your profile can edit Deals and the Deal Coach fields. |

## Support

khandakarnoushadurrahman@gmail.com
