# Меры защиты данных

## Тегирование
- Внедрить Apache Atlas + OPA
- Теги: classification, retention, encryption_required

## Шифрование
- Покоя: AES-256 (БД, S3)
- Передачи: TLS 1.3

## Обезличивание
- Хэш (SHA-256 + соль) для аналитики
- Токенизация для production-контуров

## Контроль доступа
- RBAC + ABAC через API Gateway + OPA
- Аудит в Wazuh + ELK