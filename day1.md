# Securing AI-Powered DevOps: Notes

## 1. Lab vs. Production
- **Lab Use**: Public AI tools (Qwen, Claude Code, Gemini CLI, etc.) are good for learning concepts.  
- **Production Use**: External APIs are risky due to data exposure and model vulnerabilities.  
- **Best Practice**: Use internal infrastructure for secure, enterprise-grade AI deployment.  

---

## 2. Security Challenges
### Model Vulnerabilities
- High failure rate (e.g., **82% jailbreak success in Qwen**).  
- AI-assisted developers → **10x more security issues**.  
- Privilege escalation vulnerabilities ↑ **322%**.  

### Data Exposure
- Commands, queries, and error logs may expose:  
  - Infrastructure topology  
  - Security policies  
  - Proprietary methods  

### MCP Concerns
- Direct AI ↔ infrastructure access bypasses traditional security perimeters.  

---

## 3. Secure Path Forward
- Use **internal infrastructure** instead of external APIs.  
- Maintain full control of **data, operations, and compliance**.  

---

## 4. Enterprise Approaches
- **Microsoft (Azure + OpenAI)**: Enterprise-grade AI, strict data isolation, military-grade security.  
- **Amazon (AWS + Anthropic)**: $8B investment, dedicated infra, no external exposure.  
- **Google (TPU + AI-first Cloud)**: Secure + high-performance internal AI models.  

---

## 5. Deployment Strategies
- **On-Premise**: Internal models (Llama 2, Mistral) → low latency, no data leaves org.  
- **Private Cloud**: Scalable + secure cloud infra with dedicated security teams.  
- **Hybrid**: Cloud for non-sensitive ops, internal models for critical systems.  

---

## 6. Securing AI Components
### Model Context Protocol (MCP)
