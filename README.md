# MedTech Industries CorpLaw Risk Assessment Project

## 📌 Project Overview

This project focuses on the risk assessment and change management processes within MedTech Industries' CorpLaw application environment. It assesses procedural compliance, potential security risks, and operational impacts related to user changes and emergency change implementations. The primary focus was on Change Request CH150, submitted on February 7, 2022, concerning the addition of VP Mike Williams as an approver.

## 📁 Files Included

- CorpLaw Dev and Imp User List  
  Detailed list of development and implementation users, their roles, and access levels for CorpLaw.

- Task 3_CorpLaw MedTech Industries ToD and OE
  Time of Day (ToD) access review and Operational Environment (OE) mapping for each CorpLaw user.

- MedTech CorpLaw - ITS Change Management Form 
  Official form documenting the emergency change request CH150, including impact analysis, test plans, sign-offs, and noted compliance exceptions.

## ✅ Objectives

- Evaluate the change control process and identify gaps or non-compliances.
- Perform access and role-based risk assessments on the CorpLaw user base.
- Review ToD and OE configurations to ensure proper access control and segregation of duties.
- Provide recommendations to mitigate high-priority risks and enhance change governance.

## 🔍 Key Findings

- Emergency Change CH150 was implemented without full IT Director or CAB approval.
- UAT Sign-off and rollback procedures were documented but lacked real-time audit tracking.
- User access analysis revealed role overlaps and extended privileges for some users.
- Some users had unrestricted production environment access outside approved ToD windows.

## 🛠️ Tools Used

- Microsoft Excel – Data analysis and user access mapping
- Adobe Acrobat – Review and annotation of change forms
- Internal Audit Templates – Used for risk scoring and mitigation planning

## 🔐 Risk Ratings

| Risk Category         | Description                                     | Rating  |
|-----------------------|-------------------------------------------------|---------|
| Change Management     | Lack of CAB approval and formal approvals       | High    |
| Access Control        | Over-privileged user roles in production        | Medium  |
| Time of Day Access    | Inconsistent enforcement of access windows      | Medium  |
| Documentation Gaps    | Missing signatures and tracking logs            | Low     |

## 📋 Recommendations

- Enforce mandatory CAB approvals for all emergency changes.
- Reassess all user roles in CorpLaw and remove excess privileges.
- Automate ToD access enforcement through identity governance tools.
- Require IT Director sign-off prior to any emergency implementation.
- Maintain a centralized log for UAT and rollback outcomes.

## 👨‍💼 Contributors

- Harvey Jones – Head of Law Department (Requestor)
- Melissa Smith – CorpLaw Dev Team Leader (Approver)
- Rex Johnson – Implementer

## 📅 Date of Completion

June 2025

## 📝 Notes

This risk assessment was conducted in compliance with standard IT change management protocols and best practices aligned with ISO/IEC 27001:2013 control objectives.
