# ohio-energy-monitor-data

Public data feed for the **Ohio Leads** Android app.

`leads.json` is regenerated daily by the private
[ohio-energy-monitor](https://github.com/besiktask1903/ohio-energy-monitor)
workflow and pushed here, so the app can read it without any credentials —
the same split GridWise Ohio and GridScout PA use (private code, public data).

Everything here is links to already-public Facebook posts. The search queries,
API keys, and fetching logic stay in the private repo.

## Shape

```json
{
  "updated": "2026-07-27T16:04:20Z",
  "count": 30,
  "leads": [
    {
      "id": "<normalized url — stable key the app attaches status/stars to>",
      "url": "...",
      "title": "...",
      "snippet": "...",
      "source": "Facebook",
      "context": "facebook.com",
      "first_seen": "2026-07-27"
    }
  ]
}
```
