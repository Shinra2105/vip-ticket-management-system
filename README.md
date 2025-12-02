**VIP Ticket Parsing & CRM Routing**

**Description: A webhook-based router that handles incoming high-value orders (VIP Tickets). It ensures premium customers are immediately identified and segmented.**

Key Features:

Tag Parsing: Uses JavaScript to parse incoming e-commerce tags (e.g., "VIP 10am" vs "VIP 3pm") and normalize the data.

Duplicate Prevention: Checks existing records in Google Sheets before appending new sales data.

CRM Updates: Updates Kommo CRM deal status and triggers specific "Post-Purchase" sequences based on the ticket tier.
