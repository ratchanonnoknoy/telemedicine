## Overview

[![Official Project Publication](https://res.cloudinary.com/dpa96jvla/image/upload/v1789533029/1747791924700_124000_g4_vc7jbg.jpg)](https://www.kppmu.go.th/news-detail?hd=1&id=124000)

[View Official Publication →](https://www.kppmu.go.th/news-detail?hd=1&id=124000)

## System Architecture

```mermaid
flowchart TD
    A[Patient] --> B[Next.js Web Application]
    B -->|API Request| C[Google Apps Script]
    C -->|Store Registration Data| D[(Google Sheets)]
    C -->|Push Notification| E[LINE Messaging API]
    E --> F[Nursing Staff]
```

## Notification Preview

Automated Registration Notifications with **24/7** Real-Time Alerts for Senior Professional Nurses

![LINE Messaging Notification](https://res.cloudinary.com/dpa96jvla/image/upload/v1779584919/%E0%B8%94%E0%B8%B5%E0%B9%84%E0%B8%8B%E0%B8%99%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD_1_v8yqdd.png)

## Tech Stack

- **Frontend:** Next.js, Tailwind CSS
- **Backend:** Google Apps Script
- **Data Storage:** Google Sheets
- **Messaging:** LINE Messaging API
