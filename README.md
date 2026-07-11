# -P-Sebastian-Niegel-001
ip_patch = {
    "patch_id": "ip-sebastien-niegel-001",
    "owner": {
        "name": "Sebastian Niegel",
        "alias": "EvoTransDigi",
        "role": "Creator",
        "contact": {
            "email": "sebastian.niegel@example.com",
            "website": "https://btsniegel.wixsite.com/evotransdigi"
        }
    },
    "scope": {
        "description": "IP-Patch für digitale Inhalte, Systeme und Marken von EvoTransDigi",
        "version": "1.0.0",
        "created_at": "2026-05-21T18:30:00",
        "jurisdictions": ["DE", "EU"]
    },
    "works": [
        {
            "work_id": "work-evotransdigi-system",
            "title": "EvoTransDigi System",
            "type": "Software/Framework",
            "description": "Patch-basiertes System für digitale Transformation, Agents und Container.",
            "creation_date": "2025-01-01",
            "rights_holder": "Sebastian Niegel",
            "protection": {
                "copyright": True,
                "trade_secret": True,
                "trademark_related": False
            }
        },
        {
            "work_id": "work-evotransdigi-branding",
            "title": "EvoTransDigi Branding & Logos",
            "type": "Design/Branding",
            "description": "Tech-futuristische Logos, Farbwelten und visuelle Identität.",
            "creation_date": "2025-06-01",
            "rights_holder": "Sebastian Niegel",
            "protection": {
                "copyright": True,
                "trademark_related": True
            }
        }
    ],
    "licenses": [
        {
            "license_id": "lic-internal-use-001",
            "name": "Interne Nutzung EvoTransDigi",
            "applies_to": ["work-evotransdigi-system", "work-evotransdigi-branding"],
            "license_type": "Internal",
            "granted_to": ["EvoTransDigi Projects", "Partner-Prototypen"],
            "permissions": ["use", "modify", "display"],
            "restrictions": ["no-redistribution", "no-resale"],
            "territory": ["worldwide"],
            "valid_from": "2025-01-01",
            "valid_until": None
        },
        {
            "license_id": "lic-showcase-001",
            "name": "Showcase & Portfolio",
            "applies_to": ["work-evotransdigi-branding"],
            "license_type": "Showcase",
            "granted_to": ["Sebastian Niegel"],
            "permissions": ["display", "promote"],
            "restrictions": [],
            "territory": ["worldwide"],
            "valid_from": "2025-01-01",
            "valid_until": None
        }
    ],
    "usage_events": [
        {
            "event_id": "use-001",
            "work_id": "work-evotransdigi-system",
            "context": "Client workshop",
            "description": "Verwendung des EvoTransDigi Systems als methodischer Rahmen.",
            "date": "2026-05-15",
            "licensed_under": "lic-internal-use-001"
        }
    ],
    "tariffs": [
        {
            "tariff_id": "tariff-consulting-001",
            "name": "Consulting mit EvoTransDigi IP",
            "applies_to": ["work-evotransdigi-system"],
            "model": "time-based",
            "currency": "EUR",
            "rate_per_hour": 150,
            "notes": "Nutzung der IP ist im Consulting-Honorar enthalten."
        },
        {
            "tariff_id": "tariff-license-001",
            "name": "Lizenz für Partner-Use-Cases",
            "applies_to": ["work-evotransdigi-system"],
            "model": "project-based",
            "currency": "EUR",
            "base_fee": 2000,
            "revenue_share_percent": 5
        }
    ],
    "compliance_rules": [
        {
            "rule_id": "rule-no-unauthorized-copy",
            "description": "Keine Weitergabe von Systemdokumentation oder Quellartefakten ohne schriftliche Vereinbarung.",
            "severity": "high"
        },
        {
            "rule_id": "rule-branding-integrity",
            "description": "EvoTransDigi-Branding darf nicht verändert werden ohne Fre
