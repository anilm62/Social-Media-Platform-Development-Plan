# Social Media Platform Report

## 1. Project Overview
- Purpose and objectives
- Target user base
- Core functionality

## 2. System Architecture
- Frontend components
- Backend API design
- Database schema
```mermaid
erDiagram
    USER ||--o{ POST : creates
    USER ||--o{ COMMENT : writes
    USER ||--|{ FOLLOW : "follows/followed by"
    POST ||--o{ COMMENT : has
    POST ||--o{ LIKE : receives
