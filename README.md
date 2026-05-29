# DramaSO-Status-Checker-Test

Well I better explain how this works

### So what does this do?
What this repo does is checks the status for a given website (in my case for The Sims Online Private Server - Dramaso.org), and reports a message out like so 
via a Discord Webhook.

STATUS >= 200 and <400<br />
<img width="674" height="180" alt="image" src="https://github.com/user-attachments/assets/44a06cd1-e834-451c-b2ae-b2fabba28721" /><br />

STATUS >=400<br />
<img width="779" height="190" alt="image" src="https://github.com/user-attachments/assets/8a14f367-1832-495c-909c-9305556d6ae6" /><br />

<br /><br /><br />
### How can I use this?

If you want to use this yourself:

- Fork this repository
- Edit URL="https://dramaso.org" to be the URL you want to check in .github\workflows\dso-health-check.yml
- Create a Secret in Settings > Secret and Variables > Actions called DISCORD_WEBHOOK_URL and have it be the webhook URL for your well Webhook/Integration in Discord
- Run the action manually to test
- PROFIT!

<br />

IS THIS OVERKILL? YES<br />
WAS IT A TIMESYNC? YES<br />
WAS IT FUN? OH FUCK YEAH!<br />
<br />
Copyright - Whatever LOL
