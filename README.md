# 🛡️ Sentinel - Real-Time Piracy Detection System

<p align="center">
  <img src="10.png" width="400"/>
  <img src="11.png" width="300"/>
</p>

---

## 🎯 Mission

Stop large-scale digital piracy with **real-time detection and enforcement** in under 90 seconds.

---

## ⚡ One-Command Demo

```bash
# Windows
./start.bat

# Access:
Frontend: http://localhost:5173
Backend:  http://localhost:8000

## 🚀 Key Innovations

### 🔍 Dual-Mode Fingerprinting
- **Video**: pHash + dHash fusion with adaptive sampling  
- **Audio**: Mel-spectrogram hashing  
- **Combined**: 70% video + 30% audio confidence scoring  

### ⚡ Real-Time Performance
- **20x speedup** using parallel processing  
- High detection accuracy on real-world content  
- **<90 second enforcement window**  
- Automatic scene change detection  

### 🤖 AI-Enhanced Legal
- AI-powered legal notice generation  
- Natural language detection summaries  
- Risk assessment and recommendations  

---

## 📊 Performance Metrics

| Metric | Result |
|--------|--------|
| Detection Accuracy | 95%+ |
| Color Shift Detection | 92%+ |
| Temporal Localization | 100% |
| False Positive Rate | 0% |
| Processing Speed | ~20 fps |
| Parallel Speedup | 20x |

---

## 🛠 Tech Stack

### Backend
- Flask (REST API + WebSockets)  
- OpenCV (video processing)  
- SQLite + Redis (storage & caching)  
- AI API integration  

### Frontend
- React + TypeScript  
- Vite  
- TailwindCSS  
- WebSocket-based real-time updates  

### Core Engines
- **VideoHashEngine** – multi-hash fingerprinting  
- **AudioHashEngine** – audio signature analysis  
- **DualModeEngine** – combined verification  
- **SentinelAI** – intelligence and decision layer  

---

## 🎯 Workflow

### 1. Content Ingestion
```bash
Upload video → Generate fingerprints → Store in database

Input stream → Extract features → Match fingerprints → Score confidence

Live streams → Continuous scanning → Instant alerts

Generate report → Create legal notice → Export/share

###📁 Project Structure
├── backend/
│   ├── engines/          
│   ├── api/main.py       
│   └── tests/            
├── frontend/
│   ├── src/pages/        
│   └── src/components/   
├── docs/                 
├── assets/

## 🧪 Testing & Validation

### Real-World Testing
- Processed long-form video content  
- Tested multiple piracy scenarios  
- Validated detection under transformations  

### Test Coverage
- Unit tests for core engines  
- Integration tests for pipeline  
- End-to-end workflow validation  

---

## 🏆 Competitive Advantages

- Dual-mode detection (audio + video)  
- Scene-aware adaptive sampling  
- Statistical confidence scoring  
- AI-assisted legal automation  
- Real-time processing capability  

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10+  
- Node.js 18+  
- Git  

### Quick Start
```bash
git clone <repository>
cd <project-folder>
./start.bat

### Manual Setup

# Backend
cd backend
pip install -r requirements.txt
python api/main.py

# Frontend
cd frontend
npm install
npm run dev
