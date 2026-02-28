<!-- Profile README for thteam47 -->

<h1 align="center">Phạm Văn Thái (thteam47)</h1>
<p align="center">
  Backend/Fullstack Developer • Golang Microservices • System & Product Builder
</p>

<p align="center">
  <a href="https://github.com/thteam47">GitHub</a> •
  <a href="mailto:thteam47@gmail.com">Email</a>
</p>

---

## 👋 Giới thiệu
Mình là developer tập trung vào **backend & hệ thống**, thích xây những thứ chạy ổn định, mở rộng được và dễ vận hành. 
Mình có kinh nghiệm làm việc với **Golang microservices (gRPC/Protobuf)**, thiết kế API, tối ưu hiệu năng, và triển khai hệ thống bằng **Docker**.

Ngoài kỹ thuật thuần túy, mình cũng thích tư duy **sản phẩm**: hiểu bài toán, chọn giải pháp vừa đủ, làm ra tính năng “dùng được thật” thay vì chỉ “đúng về mặt lý thuyết”.

---

## 🧠 Tech stack
- **Backend:** Golang, gRPC/Protobuf, REST
- **Data & Queue:** MongoDB, Redis, Elasticsearch, RabbitMQ, Nats
- **Infra:** Docker (Swarm/Compose), Linux
- **Frontend:** Angular, Vue

## ⚡ Realtime / WebSocket
- **Centrifugo (WebSocket realtime):** thiết kế luồng publish/subscribe cho chat, presence, notification, realtime dashboard
- Tích hợp backend **Golang (gRPC/REST)** → Centrifugo (JWT auth, channel permission, private channels)
- Tối ưu vận hành: scale theo node, cấu hình Redis/NATS làm broker, monitoring & log để debug realtime
