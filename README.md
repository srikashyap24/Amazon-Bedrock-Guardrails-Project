# Amazon Bedrock Guardrails Project  

This project showcases the use of **Amazon Bedrock Guardrails** to ensure safe and compliant generative AI applications. By integrating Guardrails with Bedrock models, the system is configured to block disallowed content and reduce risks related to sensitive information.  

## 🚀 Features  

- **Topic Denial**  
  - Guardrail configured to **block financial advice**.  
  - Guardrail configured to **block legal advice**.  

- **Content Filtering**  
  - Filters added to **detect and restrict unsafe or sensitive outputs**.  
  - **PII (Personally Identifiable Information) reduction** implemented to prevent sensitive data leakage.  

- **Customizable Policies**  
  - Guardrails can be extended for other use cases (e.g., healthcare advice, violent or hateful content).  

## 🛠️ Tech Stack  

- **Amazon Bedrock** – Foundation models for generative AI  
- **Amazon Bedrock Guardrails** – Governance and compliance controls  
- **AWS Management Console & CLI** – Setup and configuration  
- **Python / Boto3 (optional)** – Programmatic interaction with Bedrock  

## 📸 Screenshots  

The repository includes screenshots of the guardrail configurations:  
- Financial advice denial  
- Legal advice denial  
- PII filtering and content moderation  

<img src=""/>
<img src=""/>
<img src=""/>
<img src=""/>



## 📖 Learning Outcomes  

- Applied **governance and compliance controls** to generative AI.  
- Designed a framework for **responsible AI usage** by combining policy-based restrictions with content moderation.  
- Explored **practical use cases** where safe AI deployment is critical.  

## 🔗 References  

- [Amazon Bedrock Documentation](https://docs.aws.amazon.com/bedrock/)  
- [Amazon Bedrock Guardrails](https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html)  
