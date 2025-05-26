# Introduction

The Smallest AI platform empowers developers to build immersive, human-like voice experiences using our state-of-the-art speech synthesis APIs. Whether you're creating a virtual assistant, narrating dynamic content, or enabling natural voice interaction in your product, our APIs are designed to help you go from idea to implementation—fast.

At the core of our offering is **Lightning**, our ultra-low latency text-to-speech engine that generates high-quality audio with near-instant response times. For applications demanding greater realism and voice customization, we offer **Lightning Large**, which supports multilingual synthesis and custom voice cloning based on your audio samples.

This documentation is your complete guide to integrating with Smallest AI. You’ll find:

- ✅ Clear descriptions of all endpoints, from `/get_speech` to `/add_voice`  
- 🔐 Authentication instructions with API key setup and best practices  
- 📦 Standardized request/response examples, with field-level explanations  
- 🚨 Robust error handling documentation, including status codes and troubleshooting tips  
- 🚀 Quickstart samples for Python, JavaScript, cURL, and more  

## Real-Time Voice with Streaming API

For developers building live, interactive applications—like games, voice assistants, or conferencing tools—Smallest AI also supports real-time streaming. Our **Streaming API** allows you to start receiving audio fragments as soon as the first bytes are generated. This low-latency experience is powered by our WebSocket-based interface, and integrates easily with platforms like WebRTC.

You can use streaming mode by setting `stream=true` in supported endpoints or via SDK methods like `TextToAudioStream`, which deliver speech in real time. This ensures a more fluid and natural user experience for your customers and enables use cases that standard REST APIs simply can’t support. 

## Webhook Support & Asynchronous Workflows

Certain operations—like voice cloning or long-form synthesis—may take a few seconds to complete. To avoid polling or blocking your system, our platform is being built to support webhooks and async job status notifications. Once implemented, you’ll be able to register a callback URL and receive push updates when tasks complete.

Even now, you can check job statuses via polling endpoints like `/get_cloned_voices`, and our APIs return helpful status fields so you can track processing workflows efficiently. This allows your applications to remain responsive while background jobs complete seamlessly.

---

Let us help you create intelligent, expressive, and scalable voice experiences. Explore the docs and start building today.
