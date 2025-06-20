GET /auto/session/{agent_id}

HEADER:    session_token: "your_session_token",



instead of this endpoint: startE2ESession

POST /auto/session
{
  "apiKey": "<string>",
  "faceId": "tmp9i8bbq7c",
  "ttsProvider": "Cartesia",
  "ttsAPIKey": "<string>",
  "ttsModel": "sonic-turbo-2025-03-07",
  "voiceId": "a167e0f3-df7e-4d52-a9c3-f949145efdab",
  "systemPrompt": "<string>",
  "firstMessage": "<string>",
  "maxSessionLength": 3600,
  "maxIdleTime": 300,
  "language": "en",
  "customLLMConfig": {
    "model": "gpt-4o-mini",
    "baseURL": "<string>",
    "llmAPIKey": "<string>"
  },
  "createTranscript": false
}
@router.get





--- 

api.simli.ai/compose/