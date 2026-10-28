# SkinNexus
### An Intelligent Skincare Product and Routine Decision Support System

**SkinNexus** is a proposed cross-platform mobile application developed as a Final Year Project (FYP) for the MAL3018 Computing Project module.

The project aims to help users organise their existing skincare products, review ingredient information, plan AM/PM routines, understand selected ingredient compatibility concerns, and track product usage periods through Period After Opening (PAO) records.

## Project Objectives

- Develop an integrated mobile application for skincare product and routine management.
- Implement OCR-based ingredient extraction with user verification and correction.
- Develop a deterministic, rule-based compatibility engine for selected ingredient combinations.
- Provide understandable compatibility explanations using a **What–Why–Next** structure.
- Support AM/PM routine planning, PAO tracking, and product lifecycle reminders.
- Evaluate the system through functional testing, OCR extraction evaluation, compatibility-rule testing, and usability evaluation where feasible.

## Planned Features

- **Product Management:** Maintain a digital inventory of existing skincare products.
- **Ingredient Extraction:** Extract ingredient text from product labels using Optical Character Recognition (OCR).
- **Ingredient Verification:** Allow users to review and correct OCR results before analysis.
- **Ingredient Compatibility:** Apply documented rules to selected ingredient combinations.
- **Explainable Results:** Explain what was detected, why a rule was triggered, and what general next step users may consider.
- **AM/PM Routine Planning:** Organise products into morning and evening routines.
- **PAO Tracking:** Record opening dates, estimate PAO status, and provide reminders.
- **System Evaluation:** Test functionality, OCR extraction performance, rule execution, and usability where feasible.

## Proposed Technology Stack

| Component | Technology |
|---|---|
| Mobile application | React Native, Expo, TypeScript |
| Backend services | Supabase |
| Database | PostgreSQL |
| Ingredient extraction | Cross-platform OCR library, to be confirmed after feasibility testing |
| Compatibility analysis | Custom deterministic rule-based engine |
| Development tools | Visual Studio Code, Android Studio, Git, GitHub |
| Testing | Jest, React Native Testing Library, and predefined test cases |

The final OCR library and platform-specific implementation details will be confirmed through early technical feasibility testing.

## Software Engineering Approach

SkinNexus will follow an iterative Agile development approach. The system will be developed in modules, beginning with product management and manual ingredient entry, followed by ingredient processing, compatibility analysis, routine planning, and PAO tracking.

The compatibility engine will use a curated set of documented rules. Its outputs will be tested against predefined expected results. Successful rule-test results will indicate implementation correctness against the specified rules, not clinical validation or a guarantee of product safety.

## Project Scope and Limitations

SkinNexus is intended for general skincare organisation and decision support. It is not designed to provide medical diagnosis, treatment recommendations, or guarantees of product safety. It will focus on selected ingredient relationships rather than attempting to cover every skincare ingredient or product.

The application is intended to help users manage products they already own. E-commerce, purchasing features, and product recommendations are outside the project scope.

## Sustainable Development Goal

The project aligns with **United Nations Sustainable Development Goal 12: Responsible Consumption and Production**. Product inventory and PAO tracking are intended to help users monitor existing products and make more informed use of them. Any actual reduction in product waste would require further evaluation.

## Project Status

**Current stage:** Project initiation and proposal planning.

The application features and technology choices described above are planned deliverables. Implementation details, screenshots, test results, and setup instructions will be added as development progresses.

## Project Information

- **Module:** MAL3018 Computing Project
- **Project title:** SkinNexus - An Intelligent Skincare Product and Routine Decision Support System
- **Programme:** BSc (Hons) Computer Science (Software Engineering)
- **Student:** Low Jia Hui
- **Supervisor** Ts. Amir Rasyadan
- **Development period:** September 2026 – April 2027

## Repository

This repository will contain the project source code, documentation, system design materials, and testing artefacts as they become available.
