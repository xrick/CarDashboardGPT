# CarDashboardGPT

Project Architectures

car_dashboard/
│
├── backend/
│   ├── api/
│   │   ├── routes/
│   │   │   ├── whitelist.py
│   │   │   ├── blacklist.py
│   │   │   ├── events.py
│   │   │   └── rules.py
│   │   └── app.py
│   │
│   ├── core/
│   │   ├── config.py
│   │   └── database.py
│   │
│   ├── models/
│   │   ├── whitelist.py
│   │   ├── blacklist.py
│   │   ├── event.py
│   │   ├── alert.py
│   │   └── rule.py
│   │
│   ├── schemas/
│   │   ├── whitelist.py
│   │   ├── blacklist.py
│   │   └── event.py
│   │
│   ├── repositories/
│   │   ├── whitelist_repo.py
│   │   ├── blacklist_repo.py
│   │   └── event_repo.py
│   │
│   ├── services/
│   │   ├── whitelist_service.py
│   │   ├── blacklist_service.py
│   │   ├── event_service.py
│   │   └── alert_service.py
│   │
│   ├── rule_engine/
│   │   ├── engine.py
│   │   └── rules/
│   │       └── blacklist_rule.py
│   │
│   └── requirements.txt
│
├── frontend_pyqt/
│   ├── widgets/
│   │   ├── alert_panel.py
│   │   ├── whitelist_widget.py
│   │   └── blacklist_widget.py
│   │
│   ├── services/
│   │   └── api_client.py
│   │
│   └── main.py
│
└── README.md

