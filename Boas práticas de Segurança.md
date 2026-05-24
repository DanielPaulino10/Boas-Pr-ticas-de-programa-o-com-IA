# Senhas com hashing forte e salt.
# MFA para admin.
# RBAC para perfis e permissões.
# Proteção contra brute force.
# Validação de entrada em toda API.
# Rate limit por rota.
# CSRF quando aplicável.
# Proteção XSS e sanitização.
# Auditoria de ações críticas.
# Backups testados com restore real.
# Segredos fora do código-fonte.

# LGPD desde o início.
* Criptografe CPF/CNPJ em repouso (pgcrypto)
* Consentimento explícito no cadastro (art. 7 LGPD)
* Rate limit por IP + por CPF (evita lead falso)
* Nunca armazene cartão. Use tokenização do gateway.
* Logs sem dados pessoais.
