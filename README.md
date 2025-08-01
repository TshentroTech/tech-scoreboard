# 🎯 Advanced Scoreboard System for QBCore

A high-performance, secure scoreboard system for QBCore servers with dynamic job display, comprehensive Discord integration, and enterprise-grade security.

## ✨ Key Features

### 🚀 Dynamic Job Display
- **Automatic detection** of active player jobs
- **Zero-player jobs hidden** for cleaner interface
- **Dynamic job cards** created in real-time
- **Smooth animations** for job appearance/disappearance

### 🔒 Enterprise Security
- **OWASP Top 10 compliance** (All vulnerabilities addressed)
- **SQL injection protection** through parameterized queries
- **XSS prevention** with input sanitization
- **Rate limiting** (10 requests/5 seconds per player)
- **Secure Discord configuration** via server.cfg

### ⚡ Performance Optimized
- Supports **128+ players** with minimal impact

### 🎭 Enhanced Discord Integration
- Real-time Discord usernames & avatars
- Role-based colored badges
- Configurable role mappings
- Cached API calls (5-minute TTL)
- Secure token handling via server.cfg

## 🚀 Installation

### Prerequisites
- FiveM Server
- QBCore Framework
- oxmysql

```bash
cd resources
git clone https://github.com/yourusername/scoreboard.git [scoreboard]
