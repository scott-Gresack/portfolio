<!--
Portfolio of Scott Gresack – Adobe Experience Platform (AEP) Expert | Martech Implementation | Tealium iQ | Adobe Launch | Real-Time CDP | Customer Journey Analytics | GitHub for Martech Tagging and Data Architecture
-->
# 👋 Scott Gresack

**Martech Implementation Leader | Adobe Experience Platform Expert | Data Governance Strategist**

📧 **Email:** gresack.scott@gmail.com  
🔗 **LinkedIn:** [linkedin.com/in/scottgresack](https://linkedin.com/in/scottgresack)  
🌐 **Live Portfolio:** [scott-gresack.github.io/portfolio](https://scott-gresack.github.io/portfolio)  
📞 **Phone:** ‪(440) 390-3237‬

---

## 🚀 About Me

I'm a results-driven Martech and Data Governance Specialist with deep experience designing and implementing enterprise-scale data collection strategies across web and mobile ecosystems. 

I specialize in Adobe Experience Platform (AEP), Tealium iQ, Google Tag Manager (GTM), and Customer Journey Analytics (CJA), with expertise in scalable tagging frameworks, identity resolution, and real-time personalization.

I thrive at the intersection of engineering, analytics, and architecture — turning complex customer data flows into actionable, compliant, and revenue-driving outcomes.

---

## 💼 Professional Experience

**CVS Health** — *Manager, Data Collection & Tagging* (2023–Present)  
- Led the enterprise migration of CVS web and mobile applications to Adobe Web SDK and Mobile SDK through Tealium iQ and Adobe Launch, boosting data collection precision and enabling scalable, real-time personalization.
- Designed and executed advanced SQL validation queries in Adobe Experience Platform (AEP) Query Service, ensuring 1:1 field-level integrity across migrated customer datasets.
- Established enterprise data validation frameworks to streamline event QA, datastream verification, and cross-channel session stitching across web and mobile surfaces.
- Proactively resolved Adobe Launch, Tealium iQ, and JavaScript integration challenges, refining workflows, optimizing tag management execution, and improving page load performance.
- Created comprehensive documentation for Adobe Web SDK, Mobile SDK (iOS/Android), Adobe Launch, and Tealium iQ implementations, empowering faster internal enablement and onboarding.
- Leveraged Adobe Experience Platform’s Data Prep and Adobe Assurance to strengthen real-time debugging, data enrichment, and customer profile accuracy across journey orchestration use cases.
- Built and optimized AEP Real-Time Customer Profiles by managing identity stitching across streaming and batch datasets, creating dynamic audiences for activation across AJO, Adobe Target, and personalized marketing channels.
- Pioneered best practices for datastream configuration, profile governance, and WebSDK/Mobile SDK QA, ensuring HIPAA-compliant customer data collection pipelines for analytics and personalization activation.

**BlastX** — *Analytics Implementation Consultant II* (2020–2023)  
- Migrated enterprise clients from Google Analytics to Adobe stack using Tealium iQ and GTM.
- Designed consent-compliant data collection architectures leveraging XDM schemas and RTCDP.
- Delivered CDP-driven audience activation, segmentation, and campaign optimization strategies.

**Search Discovery** — *Analytics Implementation Engineer* (2020)  
- Built data pipelines with Adobe Analytics and Google Marketing Platform.
- Developed reporting apps using Domo and completed a full-stack analytics engineering training program.

---

## 🛠️ Core Skills

- **Platforms:** AEP, Adobe Launch, Adobe Analytics, Tealium iQ, GA4, GTM, CJA, AJO, Server-side tagging
- **SDKs:** Adobe Web SDK (Alloy.js), Adobe Mobile SDK (iOS/Android), Firebase, AppMeasurement
- **Languages:** JavaScript, Swift, Kotlin, SQL, HTML, CSS
- **Tools:** Adobe Assurance, Omnibug, Charles Proxy, Microsoft Clarity, Medallia, OneTrust, Meta Pixel
- **Data & Identity:** Real-Time CDP (RTCDP), XDM event/identity schemas, Dataprep, Identity Stitching

---

## 🎓 Certifications & Education

- Tealium iQ – Certified (Basic & Advanced)
- Google Analytics IQ – Certified (GAU & GA4)
- Coding Bootcamp – Cleveland Codes (C#, .NET, SQL, JavaScript)
- MTA Certifications – HTML/CSS, JavaScript, Database Fundamentals
- Master’s in Talmudic Law — Telshe Rabbinical College

---

## 📂 Featured Projects

- 🧰 [Mobile Tag Spec Builder](https://scott-gresack.github.io/portfolio/)  
  Vue-based tool to generate `trackAction`, `trackState`, and `Edge.sendEvent` payloads for Swift/Kotlin apps using XDM schemas.

- 🔍 [Adobe Web SDK Debug Monitor (CodePen)](https://codepen.io/)  
  Parses Adobe Alloy calls, extracts ECIDs, events, XDM, and displays validation outputs with a developer-friendly UI.

- 🧾 [Network Request Logger & Modal Debugger](https://scott-gresack.github.io/portfolio/)  
  Built-in modal overlays that capture native and WebView fetch/XHR calls for AEP Edge, allowing interactive inspection of headers, payloads, and Assurance status.

- 🧬 [XDM Schema Comparator Tool](https://scott-gresack.github.io/portfolio/xdm_comparator)  
  Automatically detects schema diffs across versions or projects with eVar/prop/event mapping insights.

- 🧠 HIPAA-Compliant Schema Strategy – Risk Analysis Framework  
  Swimlane-style diagram exploring schema reuse strategies between mobile and web, highlighting potential gaps in field coverage, identity stitching implications, and trade-offs between speed and completeness. Designed to aid decision-making when evaluating schema reuse vs. rebuilding in any HIPAA-compliant system.

- 🧠 Identity Stitching for Healthcare: App Arrival via Branch + Email  
  Tracks the lifecycle of a user arriving from an email or Branch deep link, detailing identity capture across ECID, email hash, and proxyID in Adobe Experience Platform. Highlights mobile-first resolution strategy, campaign attribution, and activation use cases for medical insurance apps.

- 📈 [AEP Validation Plugin Explorer](https://scott-gresack.github.io/portfolio/)  
  Implementation based on public plugin APIs for Assurance validation with support for modal tooltips, debugging hints, and test data generation.

- ⚙️ Hybrid Personalization: Server-first (Edge API) + Client-side Web SDK  
  Swimlane diagram showcasing a hybrid personalization model. The server-side sends ECID and region-based content from Adobe Target via Edge API, while the client-side refines experiences with alloy.js `sendEvent()` and decision scopes. Highlights include benefits like faster page load, progressive rendering, and unified identity stitching between backend and browser flows.

- 🧩 AEP Identity Decision Flow – Primary vs Non-Primary vs identityMap  
  Swimlane diagram outlining how to decide when to use primary vs non-primary identities in Adobe Experience Platform’s identityMap. Provides a logical flow for determining stability, uniqueness, and stitching value of an ID. Clarifies best practices for ECID, CRM ID, hashed email, and loyalty identifiers.

- 🛡️ Adobe Web SDK Initialization with OneTrust CMP via Tealium iQ  
  Technical swimlane diagram showing a compliant initialization sequence for Adobe Web SDK with OneTrust consent enforcement via Tealium iQ. Highlights early `alloy.js` injection, defaultConsent handling, and conditional triggering of `setConsent()` + `sendEvent()` based on user opt-in group `C0001`. Ensures compliant personalization and instant rendering for Adobe Target and RTCDP.

- 🗃️ Patient Data ERD for Cross-Channel Integration  
  Entity Relationship Diagram modeling the integration of healthcare demographics, clickstream activity, and experience event bridging. Uses pseudonymized identifiers to demonstrate joins across datasets for use cases like senior targeting, session history, and identity stitching. Emphasizes AEP-based data model design and analytical query structuring.

- 🧵 Recommended Identity Stitching Pipeline  
  Diagram detailing a best-practice flow for identity stitching across Kafka, Adobe Experience Platform (AEP), and Customer Journey Analytics (CJA). Demonstrates how raw events with ECID and profile data are ingested via Edge and Batch into AEP, which maintains the real-time identity graph. Profiles are then published to CJA with person ID configuration for native joins—eliminating legacy Snowflake dependency and nested identityMap workarounds.

- 🔁 Journey Orchestration: Frustration Recovery Flow  
  Swimlane diagram modeling a real-time recovery journey using Adobe Experience Platform (AEP), Journey Optimizer (AJO), and integrated behavioral signals. Captures user frustration across channels (login, search, chatbot, Medallia), segments users in AEP, and triggers AJO-based nudges (site banners, emails, support alerts). Includes logic for escalation, fallback paths, and journey exit conditions. Built as a pseudonymous healthcare experience—no proprietary data included.

- 📊 AEP SQL Query Decision Tree  
  A structured library of SQL queries designed for Adobe Experience Platform (AEP) datasets. Includes categorized sections for table metadata, ingestion monitoring, identity resolution, session analysis, funnel performance, data quality, campaign tracking, and web analytics. Ideal for analysts and architects looking to validate data, monitor trends, and optimize customer journeys in a compliant, pseudonymized environment.

---

## 🤝 Let’s Connect

I'm open to consulting opportunities, speaking engagements, and collaborations across Martech, CDP architecture, and data governance. Feel free to reach out!

---

---

## 📌 Strategic Outlook: GenAI’s Role in Martech’s Next Wave

We’re in the midst of a modern industrial shift—one where *data and AI are not just tools*, but foundational infrastructure for how digital experiences are designed, delivered, and optimized. As this wave accelerates, two core practices are becoming indispensable for Martech professionals: **supervised fine-tuning** and **retrieval-augmented generation (RAG)**.

These aren't just buzzwords—they represent a tangible path toward contextual, reliable, and organization-specific intelligence:

- **Supervised Fine-Tuning** empowers teams to align large language models with their own tone, structure, or compliance needs. You’re not feeding it *more* knowledge, you’re refining how it interprets and responds within your operational reality. It’s a light lift for technical teams, requiring configuration logic and structured examples—not deep ML expertise.

- **Retrieval-Augmented Generation (RAG)** takes it a step further by letting models *reference* internal knowledge rather than hallucinate. With RAG, the model retrieves relevant content from your proprietary datasets at query time. It’s one of the most strategic ways to operationalize trusted data, and it rewards teams who already know how to manage metadata, tagging, and identity graphs.

Together, these patterns are redefining what it means to "own" your data—and you can explore a hands-on example of this using my [Alloy Payload Inspector](https://scott-gresack.github.io/portfolio/tool2.html), a tool that visualizes and interprets Adobe Web SDK network calls and identity stitching behavior. And for Martech leaders, the opportunity isn’t just about automation—it’s about establishing *intelligent pipelines* that connect customer behavior, internal knowledge, and decision-making in real time.

Those who understand these methods early will help shape the standards for personalization, governance, and value delivery in the GenAI-powered enterprise.
