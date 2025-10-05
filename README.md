# SubStorm ⚡

Script de descoberta / brute‑DNS (subdomain brute) — direto, minimal e focado no programa.

> ⚠️ Uso apenas em ambiente autorizado (lab/VM). Não execute contra terceiros sem permissão.

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
