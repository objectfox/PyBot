### Incoming Web Hooks

```
curl -X POST --data-urlencode \
'payload={"text": "This is posted to <#general> and comes from *monkey-bot*.", \
"channel": "#general", "username": "monkey-bot", "icon_emoji": ":monkey_face:"}' \
https://hooks.slack.com/services/T00000000/B00000000/XXXXXXXXXXXXXXXXXXXXXXXX
```

### Outgoing Web Hooks

Post from Slack:

```
token=XXXXXXXXXXXXXXXXXX
team_id=T0001
team_domain=example
channel_id=C2147483705
channel_name=test
timestamp=1355517523.000005
user_id=U2147483697
user_name=Steve
text=googlebot: What is the air-speed velocity of an unladen swallow?
trigger_word=googlebot:
```

Response:

{
  "text": "African or European?"
}

### Slash Commands

Respond with plain text to be shown to user.
