**AI-Powered Railway Assistant**

A simple AI chat assistant that gives **real-time train information** for Indian Railways. You can ask questions about train schedules, seat availability, and routes, and get instant answers using **Cursor AI** and a **MCP server**.

---

## Demo

<img width="900" height="700" alt="Screenshot " src="https://github.com/user-attachments/assets/92808e3f-ae65-4768-84c1-c3585fc587a4" />
*Example of the assistant answering train-related questions.*

---

=> Features

- Chat-like interface to ask train questions.  
- Shows train schedule and seat availability in real-time.  
- Works for different classes and quotas (like AC, Sleeper, etc.).  
- Easy to use with just a `mcp.json` file.

---

=> How It Works

1. Open **Cursor AI**.  
2. Load the `mcp.json` file:
```json
{
  "mcpServers": {
    "Indian Railway": {
      "url":"https://railway-mcp.amithv.xyz/mcp"
    }
  }
}


