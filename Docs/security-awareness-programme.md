# GRC206 Security Awareness Programme

**Scenario:** Northbridge Logistics  
**Student:** Mohammed Nazir  
**Student ID:** _Add official student ID_  
**Official email:** _Add official student email_  
**Submission date:** _Add submission date_

[Back to repository overview](../README.md)

> This report addresses a fictional academic scenario. Staffing distributions, targets and implementation details identified as assumptions or proposals must be validated before operational use.

# STEP 1 — ASSESS

The purpose of this stage is to understand Northbridge Logistics' human-related security risks, identify the employee groups most exposed to those risks and establish a baseline against which programme performance can be measured.

The course material emphasises that awareness programmes should begin with risk and audience analysis, rather than simply selecting training topics. GRC206-Designing-a-Successful-S…

## 1.1 Organisation overview and scenario analysis

Northbridge Logistics is a fictional logistics organisation with 800 employees distributed across three main working environments:

- Head office.

- Warehouses.

- Remote sales operations.

The organisation has recently experienced invoice-fraud attempts, and two employees reused passwords following a breach. It also handles regulated customer data. Its security team is small, and its training budget is modest. Leadership expects the programme to reduce security incidents within 12 months while remaining sustainable for the existing team. GRC206-Assignment-Design-a-Secu…

### Scenario facts versus assumptions

| **Category** | **Information** |
|----|----|
| Confirmed scenario facts | 800 employees across head office, warehouses and remote sales. |
| Confirmed scenario facts | Recent invoice-fraud attempts have raised concern. |
| Confirmed scenario facts | Two employees reused passwords after a breach. |
| Confirmed scenario facts | The organisation handles regulated customer data. |
| Confirmed scenario facts | Security resources and training budgets are limited. |
| Working assumption | Finance and accounts-payable employees handle supplier invoices and payment requests. |
| Working assumption | Warehouse employees use shared operational systems, handheld devices or workstations. |
| Working assumption | Remote sales employees access customer information and company systems outside the head office. |
| Proposed approach | Use short, practical training sessions and existing communication channels to minimise cost and disruption. |
| Proposed approach | Use existing IT records, incident reports and low-cost phishing simulation tools where available. |

The assumptions are planning assumptions, not additional facts supplied by the case study. They should be confirmed with management and the relevant department heads before programme implementation.

## 1.2 Identify the three highest-priority human-related security risks

Based on the scenario, three risks should receive priority during the first year.

### Risk 1: Invoice fraud and business email compromise

**Description:** Employees may be deceived by fraudulent emails, impersonated suppliers, manipulated invoices or payment-detail change requests. An employee who trusts an apparently legitimate message without independently verifying it could authorise a fraudulent payment or disclose sensitive financial information.

**Why this is a priority:**

- The organisation has already experienced invoice-fraud attempts.

- Finance and accounts-payable personnel are likely to encounter supplier invoices and payment instructions regularly.

- Employees in procurement and management may also receive requests to approve transactions.

- Successful invoice fraud could result in financial losses, operational disruption and reputational damage.

**Unsafe behaviours to address:**

- Trusting an email because the sender's name or display address looks familiar.

- Processing urgent payment requests without verification.

- Accepting changes to supplier bank details based only on email instructions.

- Opening suspicious attachments or links.

**Safer behaviours to develop:**

- Independently verify payment instructions and changes to supplier details using an established contact number or trusted channel.

- Check unusual requests with the appropriate supervisor.

- Inspect suspicious emails before opening attachments or following links.

- Report suspected invoice fraud promptly.

**Priority audience:** Finance, accounts payable, procurement, relevant managers and employees involved in payment approval.

### Risk 2: Weak password practices and credential compromise

**Description:** Employees may reuse passwords across personal and organisational accounts, choose weak passwords or disclose login credentials in response to fraudulent messages. If one password becomes compromised, reuse could allow an attacker to access other organisational accounts.

**Why this is a priority:**

- The scenario explicitly states that two employees reused passwords after a breach.

- Password reuse is an identified weakness, not merely a hypothetical concern.

- Compromised accounts could expose business information and regulated customer data.

- Employees working remotely may access company systems from different locations and networks.

**Unsafe behaviours to address:**

- Reusing the same password across multiple accounts.

- Sharing passwords with colleagues.

- Responding to messages requesting login credentials.

- Ignoring multi-factor authentication prompts or approving unexpected login requests.

**Safer behaviours to develop:**

- Use unique passwords or passphrases for organisational accounts.

- Use an organisation-approved password manager where available.

- Enable and correctly use multi-factor authentication (MFA).

- Reject unexpected authentication requests and report suspicious login activity.

**Priority audience:** All employees, particularly remote sales staff, managers, IT personnel and employees with access to sensitive systems.

### Risk 3: Accidental exposure or mishandling of regulated customer information

**Description:** Employees may unintentionally expose customer information through careless email handling, inappropriate file sharing, unsecured devices or disclosure to unauthorised individuals.

**Why this is a priority:**

- Northbridge Logistics handles regulated customer data.

- Its employees work across head office, warehouses and remote sales operations, creating different information-handling environments.

- Employees may need to access, transfer or discuss customer information as part of their daily duties.

- A lack of awareness about approved handling procedures could lead to accidental disclosure or inappropriate access.

This risk is a **reasoned priority based on the scenario**, rather than a confirmed previous incident of customer-data exposure.

**Unsafe behaviours to address:**

- Sending customer information to an incorrect recipient.

- Sharing confidential documents through unapproved applications.

- Leaving printed customer records unattended.

- Accessing sensitive information on unsecured or shared devices.

- Discussing confidential customer information in public places.

**Safer behaviours to develop:**

- Verify recipients before sending sensitive information.

- Use approved storage and file-sharing systems.

- Lock devices when unattended.

- Follow clean-desk and secure-document disposal procedures.

- Report suspected data loss or accidental disclosure immediately.

**Priority audience:** All employees, with additional emphasis on customer-facing sales staff, warehouse supervisors, administrative staff and managers.

### Summary of priority risks

| **Priority** | **Human-related risk** | **Scenario justification** | **Main desired behaviour** |
|----|----|----|----|
| 1 | Invoice fraud and business email compromise | Recent invoice-fraud attempts. | Independently verify payment requests and report suspicious emails. |
| 2 | Password reuse and credential compromise | Two employees reused passwords after a breach. | Use unique passwords, MFA and safe authentication practices. |
| 3 | Accidental exposure of regulated customer data | The organisation handles regulated customer information across different work environments. | Handle, store and share information securely. |

## 1.3 Segment employees into security awareness audiences

A single training programme for all 800 employees would be inefficient because different groups perform different duties and face different security risks.

The proposed programme will use five audience groups.

| **Audience** | **Estimated population\*** | **Main security concerns** | **Training needs** |
|----|----|----|----|
| Finance, Accounts Payable and Procurement | 60 | Invoice fraud, supplier impersonation, payment manipulation and phishing. | Invoice verification, payment-change controls, email fraud detection and reporting procedures. |
| Warehouse and Logistics Employees | 350 | Phishing, unauthorised access, mishandling of operational/customer records and unsafe device practices. | Recognising suspicious messages, device security, secure handling of records and reporting suspicious activity. |
| Remote Sales and Customer-Facing Employees | 180 | Credential theft, phishing, insecure remote access and customer-data exposure. | Password security, MFA, secure remote working, customer-data protection and safe file sharing. |
| Head Office and General Administrative Employees | 170 | Phishing, data mishandling, password reuse and inappropriate information sharing. | Email security, password practices, data classification, secure document handling and incident reporting. |
| Executives, Managers and IT/Security Personnel | 40 | Targeted impersonation, privileged-account compromise, poor security decisions and delayed incident escalation. | Executive impersonation, secure approvals, access control, incident escalation, leadership responsibilities and incident response. |
| **Total** | **800** |  |  |

*The population figures are illustrative planning assumptions, not actual staffing figures provided in the scenario. The organisation should confirm its employee distribution before implementation.*

### Why these groups require different training

- **Finance and procurement:** Their daily responsibilities make them particularly exposed to fraudulent invoices and payment manipulation. Their training must include practical supplier-verification exercises.

- **Warehouse employees:** Their training should be brief, practical and accessible during shift changes or team briefings. It should not depend entirely on access to office computers.

- **Remote sales employees:** They need guidance on securing accounts, devices and customer information while working outside the office.

- **Head office employees:** They require broad awareness of phishing, password protection and responsible handling of organisational information.

- **Executives, managers and IT/security personnel:** They require additional training because their decisions, system privileges and authority can significantly influence organisational security.

This segmentation supports the course guidance that audiences should be grouped according to their work, access and security needs. GRC206-Designing-a-Successful-S…

## 1.4 Establish a pre-launch security awareness baseline

Before launching the programme, Northbridge Logistics should establish its current security awareness and behaviour levels.

The baseline will provide a starting point for evaluating whether the programme improves employee behaviour over the 12-month period.

The proposed baseline assessment will use existing organisational records, a short employee questionnaire and an initial phishing simulation.

| **Baseline measure** | **Evidence to collect** | **Proposed data source** | **Purpose** |
|----|----|----|----|
| Phishing susceptibility | Percentage of employees who click a simulated phishing link or submit information during a controlled test. | Initial phishing simulation results. | Establish the current level of vulnerability to phishing. |
| Phishing reporting behaviour | Percentage of employees who correctly report the simulated phishing message. | Simulation platform or security reporting records. | Determine whether employees recognise and report suspicious messages. |
| Password security awareness | Percentage of employees who understand password reuse risks and the organisation's password requirements. | Anonymous baseline questionnaire and existing password-policy records. | Identify gaps in password security knowledge. |
| Data protection awareness | Percentage of employees who correctly identify approved ways to handle and share customer information. | Short knowledge questionnaire and policy-awareness assessment. | Establish understanding of customer-data protection responsibilities. |
| Previous security incidents | Number and categories of recorded human-related incidents over the previous 12 months, where records are available. | IT helpdesk, security incident register and compliance reports. | Identify recurring problems and establish an incident trend baseline. |

### Baseline collection procedure

The baseline should be collected during the first month, before the main training activities begin.

1.  **Review existing records:** The security team should examine available incident reports, helpdesk records, policy violations and previous phishing-related events.

2.  **Conduct a short awareness questionnaire:** Employees should answer practical questions about phishing, password practices, data protection and reporting procedures.

3.  **Run an initial phishing simulation:** A controlled simulation should measure both clicking behaviour and reporting behaviour. Employees should not be publicly identified or embarrassed.

4.  **Review existing security controls:** IT should confirm the availability of MFA, password policies and approved reporting channels.

5.  **Document the findings:** Results should be recorded by department or audience group, where the sample size permits meaningful comparison.

**Privacy and fairness:** The organisation should not collect employees' actual passwords or expose individual credentials during baseline testing. Results should be used to identify training needs and improve security controls, not to punish employees who make mistakes.

### Expected baseline output

At the end of the assessment, the security team should produce a short baseline report showing:

- The current phishing click and reporting rates.

- Employees' understanding of password and data-protection practices.

- The most common human-related security incidents.

- Differences in awareness across the five employee groups.

- Gaps in existing security policies, reporting routes and training arrangements.

These findings will inform the programme objectives and activities in Task 2.

## 1.5 Task 1 conclusion

The assessment identifies invoice fraud, password reuse and accidental exposure of regulated customer information as Northbridge Logistics' three priority human-related security risks. It also demonstrates why the organisation should not rely on a single generic awareness session for all 800 employees.

A role-based approach will allow the organisation to direct more attention towards employees who handle payments, access customer information, work remotely or have privileged responsibilities. Establishing a baseline before launch will also make it possible to assess behavioural improvements rather than relying solely on training attendance.

## Task 1 completion check

| **Assessment requirement** | **Status** |
|----|----|
| Identify three human-driven risks | Completed |
| Justify each risk using scenario facts | Completed |
| Segment at least four audiences | Completed — five audiences |
| Describe each audience's needs | Completed |
| Propose a pre-launch baseline | Completed |
| Identify where baseline evidence will come from | Completed |
| Distinguish scenario facts from assumptions | Completed |

# TASK 2 — PLAN

## 2.1 Programme aim

The aim of the Northbridge Logistics Security Awareness Programme is to reduce human-related security risks by helping employees recognise threats, make safer decisions and report suspicious activities promptly.

The programme will run for 12 months and use short, practical and role-specific learning activities. It will prioritise invoice fraud, password security and protection of regulated customer information.

The programme will use existing communication channels and internal personnel wherever possible to minimise expenditure and avoid placing an unrealistic workload on the small security team.

## 2.2 Three measurable programme objectives

The following objectives are proposed targets. They will be confirmed or adjusted after the baseline assessment in Month 1.

| **Objective** | **Proposed target** | **Deadline** | **Evidence of achievement** |
|----|----|----|----|
| 1\. Improve resistance to invoice fraud and phishing. | Reduce the phishing simulation click rate among participating employees by at least 50% relative to the Month 1 baseline, and increase the reporting rate to at least 70%. | End of Month 12 | Phishing simulation reports, reporting records and comparison with baseline results. |
| 2\. Improve password and account security behaviour. | Ensure at least 95% of in-scope employee accounts have MFA enabled, where supported by the organisation's systems, and achieve at least 85% correct responses in a practical password and MFA security assessment. | End of Month 9 | MFA coverage reports and results of role-based knowledge or scenario assessments. |
| 3\. Improve secure handling of customer information. | Achieve at least 90% correct responses in a practical data-handling assessment and reduce recorded human-related data-handling incidents by at least 25% against the baseline, where reliable incident records are available. | End of Month 12 | Scenario assessment results, incident register and comparison with baseline. |

### How the objectives will be evaluated

- **Objective 1:** A lower click rate indicates improved resistance to simulated phishing, while a higher reporting rate indicates that employees are more likely to recognise and report suspicious messages.

- **Objective 2:** MFA coverage provides evidence of a technical security control being applied, while the practical assessment checks whether employees understand how to respond to authentication requests safely.

- **Objective 3:** Scenario assessment results indicate whether employees can apply data-handling rules. Incident trends provide additional evidence of whether safer practices are reducing harmful events.

A reduction in reported incidents should not automatically be interpreted as improved security. Reporting may initially increase because employees become more willing to report suspicious activity. The organisation should therefore examine reporting rates alongside incident severity, investigation findings and simulation results.

## 2.3 Programme sponsorship and ownership

The programme requires visible leadership support and clearly assigned responsibilities. The security team should coordinate the programme but should not be expected to deliver every activity independently.

| **Role** | **Proposed responsibility** |
|----|----|
| Executive Sponsor — Chief Operating Officer (COO) or equivalent | Approves the programme, supports implementation, provides resources and communicates the importance of security awareness to employees. |
| Programme Owner — Security/GRC Lead | Coordinates the 12-month programme, manages the calendar, prepares learning materials, oversees simulations and reports progress to leadership. |
| IT Manager / Systems Administrator | Provides MFA coverage information, supports password-security controls, manages technical reporting tools and assists with phishing simulations. |
| Finance Manager | Coordinates invoice-fraud awareness, reinforces supplier verification and payment-change procedures, and supports finance-team exercises. |
| Human Resources (HR) Manager | Includes security awareness in employee onboarding, maintains training completion records and supports staff communication. |
| Department and Warehouse Supervisors | Organise short team briefings, make training accessible across shifts and reinforce secure working practices. |
| Data Protection or Compliance Representative | Advises on the safe handling of regulated customer information and supports assessment of relevant compliance obligations. |

**Resource consideration:** These are proposed responsibilities, not a recommendation to recruit a new department. Where Northbridge does not have a dedicated Data Protection Officer or GRC specialist, an appropriately authorised compliance representative or existing manager can perform the coordination role.

The COO or equivalent should act as the executive sponsor because the programme affects all departments and requires cooperation beyond the security function. The Security/GRC Lead should remain accountable for programme coordination and measurement.

## 2.4 Role-based awareness topics

Training topics will be linked directly to the three risks identified in Task 1.

| **Audience** | **Priority topics** | **Risks addressed** |
|----|----|----|
| Finance, Accounts Payable and Procurement | Recognising supplier impersonation; detecting fraudulent invoices; verifying bank-detail changes independently; checking unusual payment requests; reporting suspicious emails. | Invoice fraud and business email compromise. |
| Warehouse and Logistics Employees | Recognising suspicious messages; safe use of workstations and operational devices; protecting printed records; locking unattended devices; reporting suspicious activity. | Phishing, credential compromise and data mishandling. |
| Remote Sales and Customer-Facing Employees | Unique passwords; MFA; secure remote access; phishing and fake login pages; safe handling and sharing of customer information. | Credential compromise and customer-data exposure. |
| Head Office and General Administrative Employees | Email security; password and MFA practices; data classification; checking recipients; approved file-sharing methods; reporting mistakes. | All three priority risks. |
| Executives, Managers and IT/Security Personnel | Executive impersonation; secure approval of payments; privileged-account protection; incident escalation; secure handling of sensitive information. | All three risks, with emphasis on high-impact decisions and access. |

The programme will use common core messages for everyone, supported by additional training for groups with greater exposure to specific risks.

This approach follows the course material's recommendation to set measurable objectives, assign programme ownership and select topics according to employee roles and risks.

# TASK 3 — DELIVER

## 3.1 Training and awareness delivery methods

Northbridge Logistics has 800 employees across different work environments and a modest training budget. Therefore, the programme will combine short digital learning, team briefings, practical exercises and visual reminders rather than relying on expensive external training or lengthy classroom sessions.

| **Delivery method** | **Target audience** | **Frequency** | **Purpose** |
|----|----|----|----|
| Short digital learning modules | Head office, remote sales and employees with suitable system access | Quarterly | Provide consistent learning on phishing, passwords and data protection. |
| Toolbox talks and shift briefings | Warehouse and logistics employees | Monthly, using short sessions | Deliver practical awareness without requiring every employee to attend a computer-based course. |
| Finance fraud-prevention workshops | Finance, accounts payable and procurement | Quarterly | Practise invoice verification and identify supplier impersonation. |
| Phishing simulations | All employees, with additional scenarios for high-risk teams | Baseline and quarterly | Assess whether employees recognise, avoid and report suspicious messages. |
| Posters and awareness notices | Warehouses, offices and common areas | Refreshed quarterly | Reinforce key messages, reporting instructions and safe behaviours. |
| Management and executive briefings | Executives, managers and supervisors | Quarterly | Reinforce leadership responsibilities, incident escalation and secure approval practices. |
| Practical data-handling exercises | Employees who access customer information | Twice yearly | Practise checking recipients, sharing files securely and reporting accidental disclosure. |

### Why these delivery methods are appropriate

- **Short modules** are suitable for employees who regularly use computers and can complete learning activities at convenient times.

- **Warehouse briefings** accommodate shift-based workers who may not have regular access to computers or corporate email.

- **Finance workshops** focus on the specific fraud techniques relevant to payment and supplier processes.

- **Phishing simulations** provide behavioural evidence rather than relying only on employees' claims that they understand phishing.

- **Posters and notices** reinforce learning between formal sessions.

- **Management briefings** help ensure supervisors support the programme and reinforce the expected behaviour.

The course material recommends combining short modules, simulations, posters and team briefings, while providing role-based learning and supporting all learners.

## 3.2 Employee onboarding

All new employees should receive basic security awareness training as part of the organisation's onboarding process.

The proposed onboarding process will include:

1.  **During the first working week:** Introduce the organisation's acceptable-use requirements, password practices, MFA, phishing awareness and incident-reporting procedures.

2.  **Role-specific induction:** Provide additional guidance relevant to the employee's duties. For example, finance employees should learn supplier-verification procedures, while warehouse employees should learn safe workstation and document-handling practices.

3.  **Practical confirmation:** Ask new employees to complete a short knowledge check or scenario exercise to confirm their understanding.

4.  **Record completion:** HR and the Programme Owner should maintain a training record showing completion and any required follow-up.

Existing employees who change roles should also receive relevant role-specific awareness training where their new responsibilities introduce additional security risks.

## 3.3 Phishing simulation approach

Phishing simulations will be used to evaluate whether employees can recognise and report suspicious messages.

The proposed approach is:

**Stage 1 — Baseline simulation:** Conduct a controlled simulation during Month 1 before the main awareness programme begins. Record the number of employees who receive, click, submit information or report the simulated message.

**Stage 2 — Targeted learning:** Provide additional training to teams with higher click rates or lower reporting rates. Finance employees should receive examples of supplier impersonation and fraudulent invoice requests.

**Stage 3 — Quarterly simulations:** Conduct further simulations using different realistic scenarios, such as:

- A fake supplier requesting a change to bank details.

- An urgent invoice requiring immediate payment.

- A message pretending to come from senior management.

- A fake password-reset or MFA notification.

**Stage 4 — Supportive follow-up:** Employees who interact with a simulated phishing message should receive a short explanation of the warning signs and the correct action to take. Repeated difficulties should lead to supportive coaching rather than public embarrassment or punishment.

**Stage 5 — Review and improvement:** Compare simulation results with the baseline and previous quarters to identify whether employees are becoming better at recognising and reporting suspicious messages.

Simulation results should be treated as indicators of behaviour, not as proof that an individual employee is careless. Simulations should be authorised, proportionate and designed to avoid disrupting essential operations.

## 3.4 No-blame security reporting route

Northbridge Logistics should establish a simple and accessible reporting process that allows employees to report suspicious messages, possible fraud, lost devices and accidental disclosure without fear of automatic punishment.

The proposed reporting arrangements are:

| **Reporting route** | **How it will be used** |
|----|----|
| Dedicated security email address | Employees with email access can forward suspicious messages to the security team. |
| Existing IT helpdesk or ticketing system | Employees can log suspicious activity, lost devices or possible security incidents. |
| Supervisor or manager | Warehouse employees and staff without convenient computer access can report concerns directly to their supervisor. |
| Telephone contact | Employees can contact the designated IT/security representative when digital reporting channels are unavailable. |

### Reporting procedure for employees

Employees should be encouraged to:

1.  Stop interacting with a suspicious message or request.

2.  Avoid clicking links, opening attachments or providing credentials.

3.  Report the message or incident using an approved reporting route.

4.  If they have already clicked a link, shared information or approved an unexpected MFA request, report it immediately.

5.  Follow instructions from the IT/security team and avoid attempting unauthorised repairs.

### Management's responsibility

The security team should acknowledge reports, assess their urgency and provide appropriate guidance. Employees who report genuine mistakes promptly should be supported in limiting the impact.

A no-blame approach does not mean ignoring deliberate misconduct. It means encouraging early reporting and treating honest mistakes as opportunities to improve security controls and employee awareness.

# TASK 4 — MEASURE

## 4.1 Measurement approach

The purpose of measurement is to determine whether the programme is changing employee behaviour and reducing human-related security risks.

Northbridge should not use training attendance as its only measure of success. Attendance indicates that employees have been reached, but it does not establish that they can recognise threats or act safely.

The course material distinguishes three measurement categories:

- **Reach:** Who participated?

- **Behaviour:** What changed?

- **Outcomes:** Is the risk falling?

It also recommends comparing results with the pre-launch baseline and reporting progress in terms that leadership can act on.

## 4.2 Proposed programme performance indicators

The following six indicators will be used to assess programme performance.

| **No.** | **Metric and category** | **Calculation** | **Data source** | **Owner** | **Review frequency** |
|----|----|----|----|----|----|
| 1 | Training completion rate — Reach | (Number of employees completing required training ÷ Number of employees assigned training) × 100 | HR training records or learning platform | HR Manager | Monthly |
| 2 | Phishing click rate — Behaviour | (Number of simulation recipients who click the simulated phishing link ÷ Number of employees who received the simulation) × 100 | Phishing simulation reports | Security/GRC Lead | After each simulation; quarterly summary |
| 3 | Phishing reporting rate — Behaviour | (Number of employees who correctly report the simulated phishing message ÷ Number of employees who received the simulation) × 100 | Simulation platform and security reporting records | Security/GRC Lead | After each simulation; quarterly summary |
| 4 | MFA coverage — Behaviour/control adoption | (Number of in-scope employee accounts with MFA enabled ÷ Total number of in-scope employee accounts) × 100 | Identity and access management records | IT Manager | Monthly |
| 5 | Secure data-handling assessment score — Behaviour | (Number of correct answers or safe decisions ÷ Total questions or decisions assessed) × 100 | Scenario-based assessments and questionnaires | Compliance Representative and Programme Owner | Quarterly or after relevant training |
| 6 | Human-related security incident trend — Outcomes | Number of recorded human-related incidents during the review period, compared with the baseline and equivalent previous periods | Security incident register, helpdesk records and compliance reports | Security/GRC Lead | Monthly monitoring; quarterly leadership review |

### Interpretation of the metrics

**1. Training completion rate**

This indicates programme reach. A high completion rate suggests that employees have received the planned learning activities. However, it does not prove that they have changed their behaviour.

**2. Phishing click rate**

A declining click rate suggests improved recognition of suspicious messages. Results should be compared with the baseline and interpreted in the context of simulation difficulty and delivery.

**3. Phishing reporting rate**

An increasing reporting rate suggests that employees are becoming more willing and able to identify and report suspicious messages. This is particularly important because early reporting can help the security team respond before an incident develops.

**4. MFA coverage**

An increase indicates that more in-scope accounts are protected by an additional authentication control. The measure depends on the organisation having systems that support MFA and reliable access to account-configuration records.

**5. Secure data-handling assessment score**

An improvement suggests that employees can apply data-protection rules in practical situations, rather than simply remembering training content.

**6. Human-related security incident trend**

A reduction in confirmed human-related incidents may indicate improved security behaviour. However, the organisation must consider reporting levels, incident severity and changes in detection. An increase in reports may reflect improved reporting culture rather than worsening security.

## 4.3 Reporting progress to leadership

The Security/GRC Lead should prepare a concise monthly performance summary and present a more detailed report to the executive sponsor every quarter.

The report should contain:

- Training completion by department and employee group.

- Phishing click and reporting rates compared with the baseline.

- MFA coverage and outstanding gaps.

- Results of practical data-handling assessments.

- Human-related security incidents, including trends and severity.

- Feedback from employees and supervisors.

- Recommended corrective actions and any support required from leadership.

### Proposed leadership reporting format

| **Performance area** | **Evidence to present** | **Management decision or action** |
|----|----|----|
| Employee participation | Completion rates by department and shift | Require department heads to arrange access for employees who have not completed training. |
| Phishing resistance | Click and reporting rates | Approve additional targeted learning for high-risk groups. |
| Account protection | MFA coverage and outstanding accounts | Direct IT to address technical or enrolment barriers. |
| Customer-data protection | Assessment scores and relevant incident trends | Approve refresher training or improvements to data-handling procedures. |
| Programme effectiveness | Comparison of all indicators with the baseline | Continue, revise or redirect programme activities based on evidence. |

## 4.4 Measurement limitations

The programme must recognise that no single indicator provides a complete picture of security awareness.

- Training completion measures participation, not competence.

- Phishing simulations represent controlled tests and may not fully reflect real-world attacks.

- MFA coverage demonstrates control adoption but does not guarantee safe authentication decisions.

- Incident records may be incomplete if employees do not report mistakes or suspicious activity.

- A rise in incident reports may indicate greater reporting confidence rather than an increase in actual security failures.

To address these limitations, Northbridge should interpret the indicators together, compare them with the baseline and review qualitative feedback from employees and supervisors.

The programme will therefore measure participation, safer behaviour and incident outcomes rather than treating attendance as proof of success.

# TASK 5 — IMPROVE AND SUSTAIN

## 5.1 Purpose of continuous improvement

The Improve stage ensures that Northbridge Logistics' Security Awareness Programme remains relevant, effective and sustainable throughout the 12-month period. The organisation should not treat awareness training as a one-time activity. Instead, it should use performance results, incident information and employee feedback to identify weaknesses and make appropriate adjustments.

The Security/GRC Lead will coordinate programme reviews, while department managers, HR, IT and the compliance representative will contribute evidence and implement agreed improvements.

## 5.2 Quarterly programme review

Northbridge will conduct a formal programme review at the end of every quarter: Months 3, 6, 9 and 12.

The review will be led by the Security/GRC Lead and attended by the executive sponsor or representative, IT Manager, HR Manager, Finance Manager, relevant department supervisors and the compliance representative.

The review will examine:

- Training completion rates across departments and shifts.

- Phishing simulation click and reporting rates.

- MFA coverage and outstanding account-security gaps.

- Results of practical data-handling assessments.

- Human-related security incidents and recurring weaknesses.

- Employee and supervisor feedback.

- Progress against the three programme objectives.

- Whether activities remain achievable within the available budget and staff capacity.

### Quarterly review schedule

| **Review** | **Main focus** | **Expected output** |
|----|----|----|
| Month 3 — First-quarter review | Evaluate the baseline, initial training reach and first simulation results. Identify departments needing additional support. | First-quarter performance report and corrective-action plan. |
| Month 6 — Mid-year review | Compare behaviour indicators with the baseline. Review invoice-fraud awareness, password practices and data-handling assessment results. | Updated training priorities and revised activities for the next six months. |
| Month 9 — Third-quarter review | Check progress towards the annual targets, assess outstanding MFA gaps and identify recurring incidents. | Targeted improvement plan for departments or behaviours below target. |
| Month 12 — Annual review | Evaluate all objectives, compare results with the baseline and assess programme sustainability. | Annual programme report and recommendations for the next 12-month cycle. |

Every review will produce an action log containing the identified issue, agreed corrective action, responsible owner, target completion date and completion status. The Security/GRC Lead will follow up outstanding actions before the next review.

## 5.3 Triggers for updating programme content

Training materials and activities should be updated whenever new evidence indicates that existing content is no longer sufficient.

The following events will trigger a review:

1.  **New security incidents:** A confirmed invoice-fraud attempt, credential compromise or customer-data exposure should trigger a review of the relevant training material and procedures.

2.  **Emerging threats:** New phishing techniques, supplier impersonation methods or fraudulent payment requests should be incorporated into relevant awareness exercises.

3.  **Repeated poor performance:** Departments with persistently high phishing click rates, low reporting rates or poor assessment results should receive targeted refresher training.

4.  **Policy or process changes:** Changes to password requirements, MFA, payment approval procedures, data-handling rules or reporting channels should be reflected in the programme.

5.  **Employee feedback:** Where employees report that instructions are unclear, inaccessible or unsuitable for their duties, the relevant materials should be revised.

6.  **Changes in work arrangements:** New systems, warehouse processes, remote-working arrangements or job responsibilities may create additional awareness requirements.

The Security/GRC Lead will coordinate updates, with technical, finance or compliance input where the subject requires specialist knowledge.

## 5.4 Collecting and using employee feedback

Northbridge should collect feedback from employees across head office, warehouses and remote sales operations. Feedback should not depend entirely on online questionnaires because some warehouse employees may have limited access to computers or corporate email.

The proposed feedback methods are:

- **Short online surveys:** Used by head office and remote sales employees after training sessions.

- **Paper feedback forms:** Made available to warehouse employees who cannot conveniently access online surveys.

- **Supervisor discussions:** Warehouse and department supervisors will collect questions and comments during team briefings and shift meetings.

- **Training feedback sessions:** The Finance Manager and other department leads will identify whether practical exercises reflect real workplace situations.

- **Anonymous feedback option:** Employees should be able to identify confusing instructions or reporting difficulties without fear of embarrassment.

The Security/GRC Lead will review feedback quarterly and group it into themes, such as unclear training content, difficulty accessing learning materials, unsuitable examples or problems using reporting channels.

Where feedback identifies a genuine problem, the Programme Owner will assign an improvement action and record its completion in the programme action log.

## 5.5 Recognising positive security behaviour

Northbridge should encourage employees to take responsibility for security by recognising useful reporting and safer decisions. Recognition should reinforce good behaviour without shaming employees who make honest mistakes.

Two recognition methods are proposed:

**1. Quarterly Security Awareness Recognition**

Each quarter, management can acknowledge an employee or team that demonstrates positive security behaviour, such as promptly reporting a suspicious invoice, identifying a phishing attempt or helping colleagues follow secure procedures. Recognition may take the form of a certificate, mention in an internal newsletter or acknowledgement during a team meeting.

**2. Team-Based Security Recognition**

Departments or warehouse teams that demonstrate improved reporting behaviour, participate actively in training and show progress in practical assessments can receive recognition during quarterly meetings. This encourages collective responsibility rather than competition based only on individual simulation scores.

Recognition should be based on constructive actions and learning, not on the number of phishing emails an employee reports alone. Employees who report genuine mistakes promptly should also be supported rather than discouraged.

## 5.6 Sustaining the programme with limited resources

To keep the programme affordable and manageable, Northbridge should:

- Reuse and update existing training materials instead of purchasing new content every month.

- Use internal managers and supervisors to deliver short awareness briefings.

- Combine awareness activities with existing departmental meetings and shift briefings.

- Use existing email, noticeboards, HR records and IT helpdesk arrangements where suitable.

- Focus specialist training on high-risk groups, particularly Finance, Procurement and employees handling customer information.

- Use quarterly reviews to discontinue activities that provide little value and prioritise those that produce evidence of safer behaviour.

The Security/GRC Lead will remain responsible for coordinating the programme, while departmental owners will support delivery and follow-up.

## 5.7 Task 5 conclusion

The Improve stage will make the programme a continuous process rather than a collection of disconnected training sessions. Quarterly reviews, employee feedback, incident-triggered updates and positive recognition will help Northbridge identify weaknesses and adjust its activities throughout the year.

This approach follows the course material's recommendation to review evidence, refresh learning, listen to employees and reinforce safer choices.

## STEP 6 — ONE-PAGE SECURITY AWARENESS PROGRAMME CALENDAR

The calendar below is designed to be the separate one-page programme calendar required by the assignment. It uses the same objectives, audiences, activities and owners established in Steps 2–5

# NORTHBRIDGE LOGISTICS

## 12-MONTH SECURITY AWARENESS PROGRAMME CALENDAR

**Programme duration:** 12 months  
**Programme owner:** Security/GRC Lead  
**Executive sponsor:** COO or equivalent  
**Target population:** 800 employees

| **Month** | **Main activity** | **Target audience** | **Responsible owner(s)** | **Measurement / output** |
|----|----|----|----|----|
| **1** | Conduct baseline questionnaire, review incident records and run initial phishing simulation. Confirm reporting channels. | All employees; department-specific analysis | Security/GRC Lead, IT, HR | Baseline report: click rate, reporting rate, awareness gaps and incident trends. |
| **2** | Launch core awareness training on phishing, password security, MFA and customer-data protection. | All employees | Security/GRC Lead, HR, supervisors | Training completion and knowledge-check results. |
| **3** | Conduct invoice-fraud workshop and first follow-up phishing simulation. Hold first quarterly review. | Finance, Accounts Payable, Procurement; all employees for simulation | Finance Manager, Security/GRC Lead | Click rate, reporting rate, finance exercise results; Q1 review and action log. |
| **4** | Deliver warehouse toolbox talks on suspicious messages, device security and safe handling of records. | Warehouse and logistics employees | Warehouse Supervisors, Security/GRC Lead | Shift coverage, attendance and short scenario-check results. |
| **5** | Deliver secure remote-working and customer-data protection training. | Remote sales and customer-facing employees | Security/GRC Lead, Compliance Representative | Assessment scores and feedback from remote employees. |
| **6** | Conduct second phishing simulation, review MFA coverage and run mid-year programme review. | All employees; additional review of high-risk groups | IT Manager, Security/GRC Lead | Simulation comparison, MFA coverage, Q2 review and corrective actions. |
| **7** | Run practical supplier impersonation and payment-change verification exercises. | Finance, Accounts Payable, Procurement and relevant managers | Finance Manager | Correct verification decisions and exercise results. |
| **8** | Conduct data-handling refresher and secure file-sharing exercises. | Employees handling customer information | Compliance Representative, department managers | Practical assessment scores and identified knowledge gaps. |
| **9** | Conduct third phishing simulation and quarterly programme review. | All employees | Security/GRC Lead, IT | Click/reporting trends, incident review and Q3 action log. |
| **10** | Deliver targeted refresher training based on simulation, incident and assessment findings. | Departments with identified weaknesses | Security/GRC Lead, relevant supervisors | Improvement in targeted assessment or simulation results. |
| **11** | Conduct employee feedback exercise and review onboarding and reporting arrangements. | All employee groups and new joiners | HR Manager, Security/GRC Lead | Feedback summary, onboarding records and proposed changes. |
| **12** | Conduct final phishing simulation, annual assessment and programme evaluation. Hold fourth quarterly review. | All employees and programme owners | Security/GRC Lead, IT, HR, department managers | Annual performance report, comparison with baseline, objective evaluation and next-year improvement plan. |

### RECURRING ACTIVITIES THROUGHOUT THE YEAR

- New employees receive security awareness induction during their first working week.

- Employees can report suspicious messages and security mistakes through approved reporting channels.

- Supervisors reinforce key messages during appropriate team and shift briefings.

- HR tracks training completion monthly.

- The Security/GRC Lead monitors incidents and programme performance.

- Quarterly programme reviews take place in Months 3, 6, 9 and 12.

**Measurement categories:** Reach — training completion; Behaviour — phishing click/reporting rates, MFA coverage and practical assessment scores; Outcomes — human-related incident trends.

**Resource approach:** Use existing staff, internal communication channels, short learning activities and targeted specialist sessions to keep the programme sustainable within the organisation's modest budget.

# Step 7: Critical Reflection



The design challenge was creating a programme that addresses human risks across 800 employees without overloading Northbridge Logistics’ security team or training budget. A single annual presentation would be inexpensive but would not meet the needs of finance staff, warehouse workers, remote sales employees and managers. I therefore chose role-based activities, using existing supervisors, communication channels and departmental meetings to extend delivery. Another challenge was measuring behaviour change rather than treating attendance as success. The programme combines phishing click and reporting rates, MFA coverage, data-handling assessments and incident trends, compared with a pre-launch baseline. These measures have limitations: for example, increased reporting may indicate greater awareness rather than more incidents. I also treated staffing distributions and numerical targets as proposals because the brief does not provide departmental figures or baseline results. Quarterly reviews allow the organisation to adjust activities using evidence while keeping the programme affordable and sustainable.
