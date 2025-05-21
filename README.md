🦊 VNSPROXY v1.0 - Firepower Edition
VNSPROXY là một công cụ thử nghiệm DDoS hiệu suất cao, hỗ trợ Layer 4 và Layer 7, được phát triển cho mục đích giáo dục và nghiên cứu.

🚀 Tính năng
✅ Hỗ trợ DDoS Layer 4 & Layer 7
🌐 Bypass Cloudflare thông qua cloudscraper
🧠 Hệ thống gợi ý chế độ tấn công động
🦾 Nhiều chế độ tấn công, bao gồm:
Random URI Flood
Slowloris
User-Agent Swarm
Cache Bypass Flood
POST Data Flood
Cookie Bomb
Random Method Flood
Referer Spam
HEAD Flood
Headless Browser Flood (Dự kiến)
📊 Bảng thống kê thời gian thực
🌍 Proxy xoay vòng & Giả mạo User-Agent
🔐 Botnets & OSINT Scraping (Sắp ra mắt)
📦 Yêu cầu
Python 3.8+
requests, cloudscraper, colorama, aiohttp, beautifulsoup4, v.v.
Khuyến nghị dùng Linux hoặc Termux (Windows hỗ trợ một phần)
bash
git clone https://github.com/hoanglamdz/VNSPROXY
cd ddos
pip install -r requirements.txt
python3 main.py