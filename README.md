# FULL COMPONENTS

Bước 1: Cài đặt Docker và Docker compose

`bash install.sh`

Bước 2: Cài đặt toàn bộ các service liên quan (có thể mất vài phút)

`docker compose up -d --build`

Bước 3: Restart backend service (trong trường hợp lỗi)

`docker restart bkauto-be`

Các service sẽ có các port tương ứng:
- Backend: 6066
- Frontend: 5173
- Postgres DB: 5433