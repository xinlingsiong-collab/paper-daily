---
name: Research Interests
about: Update the research interests used for daily paper discovery
title: "[Research Interests] "
labels: research-interests
assignees: ""
---

请修改下面 JSON 中的研究方向。每个方向建议保留 5–10 个高信息密度 keywords，并维护 domain_terms / exclude_terms，用于减少 computer architecture 等歧义词造成的误抓。

```json
{
  "topics": [
    {
      "id": "east_asian_architectural_history",
      "name": "东亚历史建筑与建筑史",
      "description": "关注中国、日本、韩国历史建筑与传统建筑的历史发展、建筑形式、类型、地域特征及比较建筑史研究。",
      "keywords": ["East Asian architectural history", "historic architecture", "traditional architecture", "Chinese architecture", "Japanese architecture", "Korean architecture", "architectural history", "comparative architectural history"],
      "domain_terms": ["architectural history", "historic architecture", "traditional architecture", "historic building", "traditional building", "architectural heritage", "vernacular architecture", "building history"],
      "exclude_terms": ["computer architecture", "software architecture", "system architecture", "neural architecture", "model architecture", "network architecture", "hardware architecture", "microarchitecture", "processor architecture", "instruction set architecture", "machine learning", "deep learning"]
    },
    {
      "id": "sino_japanese_korean_architectural_exchange",
      "name": "中日韩建筑文化交流",
      "description": "关注中国、日本、韩国之间建筑形式、建造技术、城市规划、宗教建筑及建筑知识的传播、交流、适应与本土化。",
      "keywords": ["East Asian architectural exchange", "Sino-Japanese architectural exchange", "China-Korea architectural exchange", "architectural transmission", "architectural diffusion", "cultural exchange", "architectural adaptation", "architectural influence"],
      "domain_terms": ["East Asian architectural exchange", "architectural exchange", "architectural transmission", "architectural diffusion", "cultural exchange", "architectural adaptation", "architectural influence", "Chinese architecture", "Japanese architecture", "Korean architecture"],
      "exclude_terms": ["computer architecture", "software architecture", "system architecture", "neural architecture", "model architecture", "network architecture", "hardware architecture", "microarchitecture", "processor architecture", "instruction set architecture", "machine learning", "deep learning"]
    },
    {
      "id": "historical_architectural_evolution_typology",
      "name": "历史建筑演变与类型学",
      "description": "关注历史建筑和传统建筑形式的演变、转型、延续及类型学发展，包括建筑形态、空间组织、功能变化与建造体系的历史演化。",
      "keywords": ["architectural evolution", "architectural transformation", "architectural typology", "historical building typology", "architectural morphology", "architectural continuity", "traditional architectural forms", "architectural development"],
      "domain_terms": ["architectural evolution", "architectural transformation", "architectural typology", "building typology", "architectural morphology", "architectural continuity", "traditional architectural forms", "historic building", "building history", "architectural development"],
      "exclude_terms": ["computer architecture", "software architecture", "system architecture", "neural architecture", "model architecture", "network architecture", "hardware architecture", "microarchitecture", "processor architecture", "instruction set architecture", "machine learning", "deep learning"]
    },
    {
      "id": "historic_building_conservation_settlements",
      "name": "历史建筑与历史城镇保护",
      "description": "关注历史建筑、历史城镇、历史街区、传统村落与传统聚落的保护、修复、再利用、遗产管理及历史城市景观。",
      "keywords": ["historic building conservation", "architectural conservation", "heritage conservation", "historic building restoration", "historic towns", "historic settlements", "historic districts", "adaptive reuse"],
      "domain_terms": ["historic building conservation", "architectural conservation", "heritage conservation", "historic building restoration", "historic buildings", "historic towns", "historic settlements", "historic districts", "traditional villages", "adaptive reuse", "historic urban landscape"],
      "exclude_terms": ["computer architecture", "software architecture", "system architecture", "neural architecture", "model architecture", "network architecture", "hardware architecture", "microarchitecture", "processor architecture", "instruction set architecture", "machine learning", "deep learning"]
    },
    {
      "id": "architectural_archaeology_digital_heritage",
      "name": "建筑考古与数字遗产",
      "description": "关注建筑考古、建筑年代与建造史研究，以及3D扫描、摄影测量、HBIM、数字重建等数字技术在历史建筑与建筑遗产记录、分析和保护中的应用。",
      "keywords": ["architectural archaeology", "building archaeology", "building history", "architectural chronology", "historic building survey", "digital heritage", "HBIM", "3D documentation"],
      "domain_terms": ["architectural archaeology", "building archaeology", "building history", "architectural chronology", "historic building survey", "digital heritage", "heritage documentation", "HBIM", "3D documentation", "photogrammetry", "laser scanning", "digital reconstruction"],
      "exclude_terms": ["computer architecture", "software architecture", "system architecture", "neural architecture", "model architecture", "network architecture", "hardware architecture", "microarchitecture", "processor architecture", "instruction set architecture", "machine learning", "deep learning", "computer vision"]
    }
  ]
}
```
