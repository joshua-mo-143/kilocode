---
sidebar_label: Venice AI
---

# Using Venice AI With Kilo Code

Venice AI provides access to a broad model catalog through a single API, including reasoning, coding, and multimodal models. Kilo Code supports Venice directly as a provider.

**Website:** [https://venice.ai](https://venice.ai)

## Getting an API Key

1. **Sign Up/Sign In:** Go to the [Venice dashboard](https://venice.ai/) and sign in.
2. **Create API Key:** Open your API key settings and generate a new key.
3. **Copy the Key:** Copy the key and keep it secure.

## Configuration in Kilo Code

1. **Open Kilo Code Settings:** Click the gear icon ({% codicon name="gear" /%}) in the Kilo Code panel.
2. **Select Provider:** Choose **Venice AI** from the **API Provider** dropdown.
3. **Enter API Key:** Paste your Venice key into the **Venice API Key** field.
4. **Select Model:** Pick a Venice model from the **Model** dropdown.

## Tips and Notes

- **Reasoning control:** Venice reasoning-capable models support reasoning effort controls in model options.
- **Model coverage:** Venice includes both frontier closed models and open-weight options, which can be useful for different cost/performance targets.
- **Prompt caching:** Kilo Code automatically sets a per-session cache key for Venice requests.

