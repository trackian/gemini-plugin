# Trackian

Trackian is a marketing analytics service. Its tools read the signed-in company's projects (web analytics, ad platforms, search, online stores) and make the changes the connection is allowed to make.

- Start with `list_projects`. Every project tool takes the `projectRef` it returns.
- Money figures are labelled with their currency. Ad budgets stay in the ad account's own currency.
- Changes are two-step: the first call returns a preview and a `confirmToken` and changes nothing. Show the preview to the user and call again with the token only after they say yes.
- A project can have several accounts on one platform. `list_connected_accounts` shows them, and the live tools take an `account` input to pick one.
- A result may carry `_notice`, a short note for the user (for example a platform outage). Pass it on.
- New to Trackian? `get_command` with `getting-started` walks through connecting platforms.
- Answer in plain business language. Every number must come from a Trackian tool call.
