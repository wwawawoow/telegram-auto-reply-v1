# telegram-auto-reply-v1
keyword-based auto reply script for telegram


To make the program work, you need an api_id and api_hash.
How to get them:

1. Go to my.telegram.org
2. Log in with your phone number
3. Click API development tools
4. Create an application — it doesn’t matter what you enter in the fields
5. Copy your App api_id and App api_hash
6. Paste them into the program (along with your phone number)

Next, you'll need to authorize via Telegram: enter the login code, then your 2FA password if required.

Then (similar to the example already filled in), enter the keywords — the phrases the program will react to, and the responses to those phrases.
Example:

{
	"<trigger phrase>": "<response>",
	"number": "0123456789"
}

By clicking "Show Chats", you'll get a list of all chat IDs. These are the chats where the auto-reply will be active.
Enter those IDs in the input field, configure the keywords, and the script is ready to run.

P.S. The first reply might be slightly delayed, but all following replies will be instant.
