# Task Command Center — protected deploy

Single-file dashboard. All task data is AES-256-GCM encrypted (PBKDF2-SHA256,
250k iterations); this repo contains only ciphertext + a generic UI shell.
Rebuild: `python3 ../make_protected.py "<passcode>"` then commit + push.
