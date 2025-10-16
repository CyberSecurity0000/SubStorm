# SubStorm ⚡

Script de descoberta / brute‑DNS (subdomain brute) — direto, minimal e focado no programa.

## ⚠️ Aviso: Labs, Ética e Metodologia

**Uso Exclusivo para *Labs* (Estudo, Pentest Ético e Revisão).**

*O uso desta ferramenta fora de um **escopo autorizado (com consentimento legal e explícito)** é **invasão** e de total responsabilidade do usuário. Seja sempre **metódico (MrRobot)** no escopo e na intenção.*

---

## 🔎 O que faz
Tenta resolver subdomínios a partir de uma **wordlist**.  
Por padrão busca **A records** (IPs). Pode ser trocado para `MX`, `CNAME` ou outros tipos.

---

## 🧾 Requisitos
- Python 3.8+  
- Biblioteca: `dnspython`

Instalar:
```bash
python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows PowerShell
.\venv\Scripts\Activate

pip install -r requirements.txt
