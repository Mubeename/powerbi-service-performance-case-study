# 📊 Service Performance Reporting — Case Study

> Automated Power BI dashboards on case and customer interaction data, replacing manual Excel reporting.

![Case Study](https://img.shields.io/badge/Type-Case%20Study-0F766E?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge)
![Dataverse](https://img.shields.io/badge/Dataverse-088142?style=for-the-badge)

---

## 🧩 Business problem

Service performance was reported **manually in Excel**. Pulling case and customer interaction data together by hand took time and gave no live view of case volumes, resolution times or SLA compliance.

## 💡 Solution overview

**Automated Power BI dashboards** built on **Dataverse** case and customer interaction data, covering:

- 📦 **Case volumes**
- ⏳ **Resolution times**
- ⏱️ **SLA compliance**
- 📈 **Complaint trends**

## 🏗️ Workflow / architecture

```mermaid
flowchart LR
    D[(Dataverse<br/>cases + customer interactions)] --> M[🧮 Power BI<br/>data model]
    M --> V1[Case volumes]
    M --> V2[Resolution times]
    M --> V3[SLA compliance]
    M --> V4[Complaint trends]
    V1 & V2 & V3 & V4 --> U[👥 Managers & teams<br/>self-service dashboards]
    X[📄 Manual Excel reports] -. replaced .-> U
```

## ✨ Key features

- Automated dashboards connected directly to Dataverse
- KPIs for case volumes, resolution times and SLA compliance
- Complaint trend analysis
- Replaces manual Excel reporting

## 👩‍💼 My role

- Designed and built the Power BI dashboards on Dataverse data

## 📈 Outcomes

- ✅ Replaced manual Excel reporting
- ✅ Cut reporting time by an **estimated 30%**

## 🖼️ Screenshots

> _Screenshots coming soon._ Sample or anonymised data only.

| Overview | SLA compliance | Complaint trends |
|---|---|---|
| _placeholder_ | _placeholder_ | _placeholder_ |

## 🧠 Key learnings

- Connecting directly to Dataverse removes the copy-paste step that makes Excel reports slow and error-prone.
- A small set of clear KPIs (volume, resolution time, SLA compliance) answers most day-to-day service questions.

---

<sub>Built by [Mubeena M E](https://github.com/mubeename) · [LinkedIn](https://www.linkedin.com/in/mubeename)</sub>
