# Risk Register - Score risks based on their likelihood and severity

### Overview
In this activity, you will practice performing a risk assessment by evaluating vulnerabilities that commonly threaten business operations. Then, you will decide how to prioritize your resources based on the risk scores you assign each vulnerability.

You might recall that the purpose of having a security plan is to be prepared for risks. Assessing potential risks is one of the first steps of the NIST Cybersecurity Framework (CSF), a voluntary framework that consists of standards, guidelines, and best practices to manage cybersecurity risk. Risk assessments are how security teams determine whether their security operations are adequately positioned to prevent cyber attacks and protect sensitive information.

### Scenario
Review the following scenario. Then complete the step-by-step instructions.

You've joined a new cybersecurity team at a commercial bank. The team is conducting a risk assessment of the bank's current operational environment. As part of the assessment, they are creating a risk register to help them focus on securing the most vulnerable risks.

A risk register is a central record of potential risks to an organization's assets, information systems, and data. Security teams commonly use risk registers when conducting a risk assessment.

Your supervisor asks you to evaluate a set of risks that the cybersecurity team has recorded in the risk register. For each risk, you will first determine how likely that risk is to occur. Then, you will determine how severely that risk may impact the bank. Finally, you will calculate a score for the severity of that risk. You will then compare scores across all risks so your team can determine how to prioritize their attention for each risk.

### Step 1: Access the template
To use the template for this course item, click the following link and select Use Template. 

Link to template:
<a href="https://docs.google.com/document/d/1R7GdZumP7gXRNjD1dOaMuMlB3dD0gRmX/edit?usp=sharing&ouid=105064495821226407439&rtpof=true&sd=true">Risk register</a>

### Step 2: Understanding the operating environment
When conducting a risk assessment, it's important to consider the factors that could cause a security event. This often starts with understanding the operating environment.

In this scenario, your team has identified characteristics of the operating environment that could factor into the bank's risk profile:

The bank is located in a coastal area with low crime rates. Many people and systems handle the bank's data—100 on-premise employees and 20 remote employees. The customer base of the bank includes 2,000 individual accounts and 200 commercial accounts. The bank's services are marketed by a professional sports team and ten local businesses in the community. There are strict financial regulations that require the bank to secure their data and funds, like having enough cash available each day to meet Federal Reserve requirements.

### Step 3: Consider potential risks to assets
Security events are possible when assets are at risk. The source of a risk can range from malicious attackers to accidental human errors. A risk source can even come from natural or environmental hazards, such as a structural failure or power outage.

The bank's funds are one of its key assets. Your team has listed five primary risks to the bank's funds:
  * Business email compromise
  * Compromised user database
  * Financial records leak
  * Theft
  * Supply chain attack

Consider these potential risks in relation to the bank's operating environment.

### Step 4: Score risks based on their likelihood 
As you might recall, risk can be calculated with this simple formula:

### Likelihood x Impact = Risk

In order to calculate the score for a security risk, you must first estimate and score the likelihood of the risk causing a security event. The likelihood of a risk can be based on available evidence, prior experience, or expert judgment. A common way to estimate the likelihood of the risk is to determine the potential frequency of the risk occurring:
  * Could the risk happen once a day?
  * Could the risk happen once a month?
  * Could the risk happen once in a year?

For example, the bank must have enough funds available each day to meet its legal requirements. A potential risk that could prevent the bank from replenishing its funds is a supply chain disruption. Being located in a coastal area, there's a likelihood that the bank may experience supply chain disruptions caused by hurricanes. However, a hurricane might only impact the bank every few years, so you can score the likelihood as low.

In this instance, the team is scoring the likelihood of an event on a scale of 1-3:

  * **1** represents an event with a low chance of occuring.
  * **2** represents an event with a moderate chance of occuring.
  * **3** represents a high chance of occuring.

Review the **Risk(s)**, **Description**, and **Notes** of the risk register template. Refer to the risk matrix and use it to estimate a likelihood score for each risk. Then, enter a **score (1-3)** for each risk in the **Likelihood** column of the register.

### Step 5: Score risks based on their severity
A severity score is an estimate of the overall impact that might occur as a result of an event. For example, damage can occur to a company's reputation or finances and there may be a loss of data, customers, or assets. Evaluating the severity of a risk helps businesses determine the level of risk they can tolerate and how assets might be affected. 

When evaluating the severity of a risk, consider the potential consequences of that risk occurring:

  * How would the business be affected?
  * What's the financial harm to the business and its customers?
  * Can important operations or services be impacted?
  * Are there regulations that can be violated?
  * What is the reputational damage to the company's standing?

Use the top row of the risk matrix and consider the potential impact of each risk. Estimate a severity score for each risk. Then, enter a **score (1-3)** for each risk in the Severity column of the register:

  * **1** (low severity)
  * **2** (moderate severity)
  * **3** (high severity)

For example, a leak of financial records might lead to a loss of profits, a loss of customers, and heavy regulatory fines. A risk such as this might receive a severity score of 3 because it greatly impacts the bank's ability to operate.

### Step 6: Calculate an overall risk score
Ultimately, the goal of performing a risk assessment is to help security teams prioritize their efforts and resources.

Using the risk formula, multiply the likelihood and severity score for each risk. Then, enter a priority **score (1-9)** for each of the risks in the Priority column of the register.

# Complete Parking lot USB exercise
<table>
    <tr>
      <td>Assets</td>
      <td>Risk(s)</td>
      <td>Description</td>
      <td>Likelihood</td>
      <td>Severity</td>
      <td>Priority</td>
    </tr>
    <tr>
      <td rowspan="5">Funds</td>
      <td>Business email compromise</td>
      <td>An employee is tricked into sharing confidential information.</td>
      <td>2</td>
      <td>2</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Compromised user database</td>
      <td>Customer data is poorly encrypted.</td>
      <td>2</td>
      <td>3</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Financial records leak</td>
      <td>A database server of backed up data is publicly accessible.</td>
      <td>3</td>
      <td>3</td>
      <td>9</td>
    </tr>
      <tr>
      <td>Theft</td>
      <td>The bank's safe is left unlocked.</td>
      <td>1</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Supply chain disruption</td>
      <td>Delivery delays due to natural disasters.</td>
      <td>1</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Notes</td>
      <td colspan="5">How are security events possible considering the risks the asset faces in its operating environment?<br><br>
Third-party relationships can introduce additional security risks, as they present potential avenues for data compromise. While theft is a concern, it might not be the primary risk factor in low-crime areas.</td
    </tr>
</table>

* **Asset:** The asset at risk of being harmed, damaged, or stolen.
* **Risk(s):** A potential risk to the organization's information systems and data.
* **Description:** A vulnerability that might lead to a security incident.
* **Likelihood:** Score from 1-3 of the chances of a vulnerability being exploited. A 1 means there's a low likelihood, a 2 means there's a moderate likelihood, and a 3 means there's a high likelihood.
* **Severity:** Score from 1-3 of the potential damage the threat would cause to the business. A 1 means a low severity impact, a 2 is a moderate severity impact, and a 3 is a high severity impact.
* **Priority:** How quickly a risk should be addressed to avoid the potential incident. Use the following formula to calculate the overall score: 
  * **Likelihood x Impact Severity = Risk**


### Notes
* **Third-party risk:** The bank's marketing partnerships with the sports team and local businesses introduce potential security risks. Data breaches or security incidents at these organizations could indirectly impact the bank.
* **Human error:** The large number of employees handling data increases the risk of human error, such as accidental data exposure or misconfigurations.
* **Regulatory compliance:** Failure to comply with strict financial regulations could result in significant penalties and reputational damage.
* **Physical security:** While the bank is located in a low-crime area, physical security measures, such as secure access controls and surveillance systems, are still crucial to protect against theft and unauthorized access.
* **Data privacy:** The bank must implement robust data privacy measures to protect customer information, especially given the increasing threat of cyberattacks and data breaches.

### Likelihood
A range of likelihood scores were estimated based on several factors, including the complexity of the attack, the organization's security measures, and external factors. For instance, a supply chain attack caused by a natural disaster was assigned a likelihood score of 1, as such events are unpredictable and their impact on the organization's security posture is difficult to quantify. Conversely, a compromised user database was assigned a score of 2, reflecting the increasing frequency of data breaches and the potential for human error.

### Severity
Given the bank's reliance on third-party vendors and the potential for human error, even in low-crime areas, risks such as business email compromise and data breaches cannot be entirely dismissed. While physical security measures are important, the bank must also prioritize cybersecurity measures to protect against digital threats.

### Priority 
Given the high risk score of 9 associated with the "Financial records leak" risk, it is imperative to address this issue immediately. This risk poses a significant threat to the bank's operations and customer data, making it the highest priority for remediation.

### Key takeaways 
Risk assessments are a crucial tool for identifying and prioritizing potential threats to an organization's assets. By systematically evaluating assets, identifying vulnerabilities, and assessing the likelihood and impact of potential risks, organizations can proactively implement security measures to mitigate threats and protect sensitive information.

In the provided scenario, the bank's reliance on third-party relationships, such as the professional sports team and local businesses, introduces additional security risks. While physical security measures may be sufficient to mitigate direct threats, the bank must also focus on securing digital assets and implementing robust cybersecurity practices to protect against cyberattacks.
