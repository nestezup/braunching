## 관련문서
#### supabase
- https://supabase.com/

#### supabase kakao login
- https://supabase.com/docs/guides/auth/social-login/auth-kakao

#### elevenlabs conversational AI
- https://elevenlabs.io/conversational-ai

#### elevenlabs 샘플코드
- https://github.com/nestezup/my-conversational-agent
- 코드공유를 어떻게 하는 지 몰라서 github주소에 초대해드렸어요.
- 
#### elevenlabs get-conversations
- https://elevenlabs.io/docs/conversational-ai/api-reference/conversations/get-conversations
- 대화가져오는 api주소입니다. 

---

#### 대화내역 요약
- http://dify.automationpro.online/v1/chat-messages
- api_key : app-aOG12NIHydS8q2B7mJVIAadU

curl -X POST 'http://dify.automationpro.online/v1/chat-messages' \
--header 'Authorization: Bearer {api_key}' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {},
    "query": "What are the specs of the iPhone 13 Pro Max?",
    "response_mode": "streaming",
    "conversation_id": "",
    "user": "abc-123",
    "files": [
      {
        "type": "image",
        "transfer_method": "remote_url",
        "url": "https://cloud.dify.ai/logo/logo-site.png"
      }
    ]
}'


#### STP분석

curl -X POST 'http://dify.automationpro.online/v1/workflows/run' \
--header 'Authorization: Bearer app-JFPzzyroAt6AOAvu0rA1FkNE' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {
        "interview_content":"이곳에 대화내용이 들어가면 됩니다."
    },
    "response_mode": "blocking", 
    "user": "abc-123"
}'

#### 브랜드전략기획보고서
curl -X POST 'http://dify.automationpro.online/v1/chat-messages' \
--header 'Authorization: Bearer app-WaVF8poAO1YLFE7dNbpSjt8A' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {
        "stpContent" : "STP분석내용입니다"
    },
    "query": "What are the specs of the iPhone 13 Pro Max?",
    "response_mode": "streaming",
    "conversation_id": "",
    "user": "abc-123",
    "files": [
      {
        "type": "image",
        "transfer_method": "remote_url",
        "url": "https://cloud.dify.ai/logo/logo-site.png"
      }
    ]
}'

#### 브랜드아이덴티티
curl -X POST 'http://dify.automationpro.online/v1/chat-messages' \
--header 'Authorization: Bearer app-anaJeTBoLv5HyO9IhKdANTqR' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {},
    "query": "이쪽으로 요청하시면 됩니다. ",
    "response_mode": "streaming",
    "conversation_id": "",
    "user": "abc-123",
    "files": [
      {
        "type": "image",
        "transfer_method": "remote_url",
        "url": "https://cloud.dify.ai/logo/logo-site.png"
      }
    ]
}'




#### 브랜드네이밍보고서
curl -X POST 'http://dify.automationpro.online/v1/chat-messages' \
--header 'Authorization: Bearer app-V5GYVtSw2TvkyAxyYeVeQcdp' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {},
    "query": "What are the specs of the iPhone 13 Pro Max?",
    "response_mode": "streaming",
    "conversation_id": "",
    "user": "abc-123",
    "files": [
      {
        "type": "image",
        "transfer_method": "remote_url",
        "url": "https://cloud.dify.ai/logo/logo-site.png"
      }
    ]
}'


#### 브랜드로고생성
curl -X POST 'http://dify.automationpro.online/v1/chat-messages' \
--header 'Authorization: Bearer app-rtTY3tr6GLb3wwmVNjtNBT56' \
--header 'Content-Type: application/json' \
--data-raw '{
    "inputs": {},
    "query": "이쪽으로 요청해주세요",
    "response_mode": "streaming",
    "conversation_id": "",
    "user": "abc-123",
    "files": [
      {
        "type": "image",
        "transfer_method": "remote_url",
        "url": "https://cloud.dify.ai/logo/logo-site.png"
      }
    ]
}'
