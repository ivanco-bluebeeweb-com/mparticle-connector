# mParticle Connector — Discovery

**Vendor:** mParticle (https://mparticle.com)  
**API Base URL:** `https://api.mparticle.com`  
**Authentication:** Platform API Key + Secret (HTTP Basic Auth)

## Архитектура API
- **Ключевые сущности:** фиды данных, конфигурации подключений (/connections), аудитории (/audiences), профили идентичности (/identity)
- **Формат обмена данными:** JSON / HTTPS REST.
- **Обработка ошибок:** Стандартные HTTP-коды (400, 401, 403, 404, 429, 500) с типизацией ответа.
- **Тестовая точка проверки подключения:** `GET /v1/orgs`.
