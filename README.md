


# Example

```
curl http://127.0.0.1:443/v1/chat/completions \
  -H "Content-Type: application/json" \
  -d '{
    "model": "gemini-1.5-flash",
    "messages": [
      {
        "role": "user",
        "content": "Explain how AI works in simple terms."
      }
    ]
  }'

```
