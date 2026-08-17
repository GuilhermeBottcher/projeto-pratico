# \## Versionamento Semântico

# 

# Este projeto segue o \[Versionamento Semântico (SemVer)](https://semver.org/lang/pt-BR/), um padrão para numerar versões de software de forma clara e previsível.

# 

# \### O que é Versionamento Semântico?

# 

# É uma convenção que define como as versões de um software devem ser numeradas, permitindo que desenvolvedores e usuários entendam rapidamente o impacto de uma atualização apenas olhando o número da versão.

# 

# \### Formato: MAJOR.MINOR.PATCH

# 

# O número da versão segue o formato `X.Y.Z`, onde:

# 

# \- \*\*MAJOR (X)\*\* — versão principal

# \- \*\*MINOR (Y)\*\* — versão secundária

# \- \*\*PATCH (Z)\*\* — versão de correção

# 

# Exemplo: `v1.4.2`

# 

# \### Quando incrementar cada parte

# 

# \- \*\*MAJOR\*\*: incremente quando fizer mudanças incompatíveis com versões anteriores (\*breaking changes\*), ou seja, alterações que quebram a compatibilidade com quem já usa o projeto.

# &#x20; - Exemplo: `1.4.2` → `2.0.0`

# 

# \- \*\*MINOR\*\*: incremente quando adicionar uma nova funcionalidade que seja compatível com versões anteriores (não quebra nada que já existia).

# &#x20; - Exemplo: `1.4.2` → `1.5.0`

# 

# \- \*\*PATCH\*\*: incremente quando fizer correções de bugs compatíveis com versões anteriores, sem adicionar novas funcionalidades.

# &#x20; - Exemplo: `1.4.2` → `1.4.3`

