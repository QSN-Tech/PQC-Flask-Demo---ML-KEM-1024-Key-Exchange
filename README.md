# PQC Flask Demo - ML-KEM-1024 Key Exchange

Simple proof-of-concept for post-quantum key encapsulation using **pqcrypto** library (ML-KEM-1024 / Kyber1024 – NIST standard).

**Features**
- Generate quantum-resistant keypair
- Key encapsulation (encap)
- Key decapsulation (decap)
- Modern quantum-themed UI with copy buttons

**Tech Stack**
- Python 3.11+
- Flask
- pqcrypto (post-quantum cryptography)

**Installation & Run**
```bash
git clone https://github.com/QSN-Tech/pqc-flask-demo.git
cd pqc-flask-demo
pip install -r requirements.txt
python app.py

curl -X POST http://127.0.0.1:4000/encap -H "Content-Type: application/json" -d "{\"public_key\": \"YOUR_PUBLIC_KEY_HEX\"}"
https://qsn-space-5342307.postman.co/workspace/Mohsen-Abbaszadehrazlighi's-Wor~00b376ea-ede0-4d0e-8268-d0f4b39752f0/request/51400148-ee7f2408-6c4d-4688-a8bd-2875da77ae6c?action=share&source=copy-link&creator=51400148&ctx=documentation



