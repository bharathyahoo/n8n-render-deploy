\# n8n on Render



Minimal repo to deploy n8n with Docker on Render free tier.



\## Deploy



1\. Push this repo to GitHub/GitLab.

2\. In Render: New → Blueprint → point to this repo.

3\. After deploy, copy the Render URL (e.g. https://n8n-xxxxx.onrender.com).

4\. Go to Render Dashboard → Environment → set:

&nbsp;  - N8N\_HOST = n8n-xxxxx.onrender.com

&nbsp;  - WEBHOOK\_URL = https://n8n-xxxxx.onrender.com/

&nbsp;  - N8N\_EDITOR\_BASE\_URL = https://n8n-xxxxx.onrender.com/

&nbsp;  - Set N8N\_BASIC\_AUTH\_PASSWORD to a strong secret.

5\. Redeploy.

6\. Open the URL and log in.



