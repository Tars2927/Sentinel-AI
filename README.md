User Input Stream
    ↓
[WebSocket/Server-Sent Events]
    ↓
FastAPI Endpoint (async)
    ↓
Redis Cache (check recent similar messages)
    ↓
DistilBERT Inference (ONNX Runtime for speed)
    ↓
Threshold Check (adaptive based on user history)
    ↓
[Nudge API Response] → [Frontend Intervention]
