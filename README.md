# emqx-nginx

使用 **EMQX** 和 **Nginx** 搭建的 MQTT 代理服務的 Docker 專案，提供高效的消息中繼和反向代理功能。

---

## 功能介紹

- **EMQX**: 高性能的 MQTT 消息中繼服務器，支持 MQTT 3.x/5.0 協議。
- **Nginx**: 作為反向代理，用於處理 HTTP、WebSocket 的請求，並實現負載均衡。
- **Docker-Compose**: 簡化環境配置和部署。