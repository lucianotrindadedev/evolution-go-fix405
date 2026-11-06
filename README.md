# Evolution Go 0.7.2 com a correção do "Client outdated (405)"

Desde 02/11/2026 o WhatsApp recusa a versão de cliente embutida na Evolution Go 0.7.2
(`Client outdated (405)`), e nenhuma imagem oficial corrigida foi publicada ainda.

Este repositório só gera uma imagem: baixa o código oficial na tag `0.7.2`
([evolution-foundation/evolution-go](https://github.com/evolution-foundation/evolution-go)),
aplica as 5 linhas do [PR #227](https://github.com/evolution-foundation/evolution-go/pull/227)
(`fix-405.patch`: chama `store.SetWAVersion` com a versão atual do WhatsApp Web) e publica em:

```
ghcr.io/lucianotrindadedev/evolution-go:0.7.2-fix405
```

Quando sair uma versão oficial com a correção, volte para a imagem oficial.
