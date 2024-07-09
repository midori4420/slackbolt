python 

# slackbolt
Download image file that uploaded file to Slack channel 

## APP preparation (Slack web site)
(https://api.slack.com/apps?new_app=1)

Event Subscriptions
〇Subscribe to bot events
app_mention
message.channels
message.groups
message.im
message.mpim

〇Bot Token Scopes
calls:read
chat:write
files:read
files:write
groups:history
im:history
im:read
im:write
mpim:history

〇User Token Scopes
channels:read
channels:history
files:read
groups:history
groups:read
mpim:history
mpim:read
users:read
