## Database Design

Table: contact_messages

- message_id (INT, Primary Key)
- name (VARCHAR)
- email (VARCHAR)
- phone_number (VARCHAR)
- subject (VARCHAR)
- message_content (TEXT)
- submission_date (DATETIME)
- is_spam (BOOLEAN)
- gdpr_consent (BOOLEAN)
