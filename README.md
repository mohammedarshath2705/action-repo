#  Action Repo

This is a simple GitHub repository created to test webhook events for the assessment task.

When actions like **push**, **pull request**, or **merge** happen in this repo, GitHub sends a webhook notification to the configured Webhook Receiver application.

---

##  Events Handled

-  Push commits to any branch
-  Create a Pull Request
-  Merge a Pull Request

Each action triggers a webhook to the **Webhook Receiver** Flask app via a public ngrok tunnel URL.

---

##  How to Use

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/action-repo.git
2. Make changes, push commits, open pull requests, and merge them to trigger webhook events.
3. Webhook requests will be sent to the Webhook Receiver’s /webhook endpoint.

