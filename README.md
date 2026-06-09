# Busync

Busync는 서울시 버스 공공 API를 활용하여 정류장 및 버스 도착 정보를 수집하고 저장하는 데이터 엔지니어링 학습 프로젝트입니다.

## Project Goal

* 서울시 버스 공공 API 연동
* 정류장 및 노선 정보 수집
* PostgreSQL 저장
* Docker 기반 실행 환경 구축
* 데이터 파이프라인 설계
* 향후 실시간 버스 도착 예측 기능 확장

---

## Tech Stack

* Python
* Requests
* PostgreSQL
* Docker
* DBeaver
* Jupyter Notebook

---

## Project Structure

```text
busync/
├── notebooks/
├── src/
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Environment Setup

### Clone Repository

```bash
git clone https://github.com/shmoon2077/busync.git
cd busync
```

### Virtual Environment

```bash
python -m venv .venv
source .venv/bin/activate
```

### Install Packages

```bash
pip install -r requirements.txt
```

### Environment Variables

Create `key.env`

```env
BUS_API_KEY=YOUR_API_KEY
```

---

## Current Progress

* [x] Ubuntu Development Environment
* [x] Git Repository Setup
* [x] Docker PostgreSQL Container
* [x] DBeaver Connection
* [ ] Seoul Bus API Connection
* [ ] Station Data Collection
* [ ] Database Modeling
* [ ] ETL Pipeline
* [ ] Docker Compose Environment

---

## Future Plans

1. Station Search API Integration
2. Arrival Information Collection
3. PostgreSQL Data Storage
4. Data Pipeline Automation
5. Bus Arrival Prediction
