# EZHome — releases

Canal público de distribuição da Home da central multimídia BYD.

[Baixar a versão mais recente](https://github.com/rrrabadan/ezhome-releases/releases/latest)

Cada release contém:

- `EZHome-<versão>.apk`: aplicativo Android assinado com a identidade já usada nas instalações existentes.
- `latest.json`: versão e endereços usados pelo botão **Verificar atualizações**.
- `SHA256SUMS`: hash do APK para conferência manual.

O código-fonte, testes e documentação técnica ficam no repositório privado `rrrabadan/ezhome`. Este repositório não recebe fontes do aplicativo. Os arquivos “Source code” adicionados automaticamente pelo GitHub contêm somente este README.

Baixe o APK e confirme a atualização no instalador Android, com o veículo estacionado. O pacote permanece `com.rabadan.homedash`; atualizações assinadas com o mesmo certificado preservam dados e configurações. Na tela BYD **Desativar AutoStart**, deixe EZHome **DESL** para permitir o início automático.

Distribuição alpha. A publicação automatizada valida assinatura, pacote e versão, mas não comprova comportamento físico na central. A primeira instalação de uma versão que contém o botão de atualização deve ser feita manualmente.

Certificado SHA-256: `a2a47c53f25faa56f096fd5ae083abf156148b70274532f5375464f045491c2a`.
