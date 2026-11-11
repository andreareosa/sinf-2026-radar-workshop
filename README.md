# ping Portugal: Measure the Internet with Cloudflare Radar 🌍

**SINF 2026 · FEUP · Cloudflare workshop**

Use real traffic data from Cloudflare's network to answer questions about how the world goes online.
Is Portugal more mobile than the rest of the world? How much of the traffic is bots, not people?
And can you find the day Portugal went dark?

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/andreareosa/sinf-2026-radar-workshop/blob/main/workshop.ipynb)

## Before the workshop

You need:

1. A laptop with a browser and a **Google account** (for Google Colab)
2. Basic **Python**
3. A free **Cloudflare account** and a **Radar API token**

### Create your Radar API token

1. Sign up at [dash.cloudflare.com/sign-up](https://dash.cloudflare.com/sign-up)
2. Go to **My Profile** → **API Tokens** → **Create Token**
3. Under **Custom token**, click **Get started**
4. Fill in:
   - **Token name:** `sinf-workshop`
   - **Permissions:** `Account` → `Radar` → `Read`
5. Click **Continue to summary** → **Create Token**
6. Copy the token and keep it private. It's shown only once.

## During the workshop

1. Click the **Open in Colab** button above
2. In Colab, click **File** → **Save a copy in Drive** (otherwise your work won't be saved)
3. Follow the notebook, step by step

## Useful links

- [Cloudflare Radar](https://radar.cloudflare.com)
- [Radar API reference](https://developers.cloudflare.com/api/resources/radar/)
- [Make your first Radar API request](https://developers.cloudflare.com/radar/get-started/first-request/)
