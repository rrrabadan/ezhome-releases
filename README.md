# EZHome — releases

Canal público de distribuição da Home da central multimídia BYD.

[Baixar a versão mais recente](https://github.com/rrrabadan/ezhome-releases/releases/latest)

Cada release contém:

- `EZHome-<versão>.apk`: aplicativo Android assinado com a identidade já usada nas instalações existentes.
- `latest.json`: versão e endereços usados pelo botão **Verificar atualizações**.
- `SHA256SUMS`: hash do APK para conferência manual.

O código-fonte, testes e documentação técnica ficam no repositório privado `rrrabadan/ezhome`. Este repositório não recebe fontes do aplicativo. Os arquivos “Source code” adicionados automaticamente pelo GitHub contêm somente este README.

A partir da **0.5.28-alpha**, o botão **Verificar atualizações** encontra uma versão nova e pede confirmação em **Atualizar agora**. Depois o EZHome baixa e confere hash, pacote, versão e certificado do APK, instala, ativa **Iniciar com a central**, confere e permite o AutoStart na tela oficial da BYD e reabre o aplicativo. Requer a depuração local já autorizada para o EZHome. Não exige P ou velocidade zero.

Na tela BYD **Desativar AutoStart**, **EZHome DESL / checked=false** significa início permitido. O atualizador verifica esse estado após a instalação, pois o fabricante pode voltar a bloquear o app ao atualizar. Se não conseguir confirmar o AutoStart, informa a pendência e oferece **Corrigir AutoStart**, sem reinstalar o APK.

Versões antigas que ainda abrem o navegador precisam de uma primeira atualização manual: baixe o APK e confirme no instalador Android. O pacote permanece `com.rabadan.homedash`; a assinatura atual preserva dados e permissões. As demais seleções e posições do app são mantidas.

Distribuição alpha. A publicação automatizada valida assinatura, pacote e versão; o fluxo completo de instalação, UI AutoStart e reabertura ainda precisa de validação física autorizada na central. Um build aprovado não comprova comportamento físico.

Certificado SHA-256: `a2a47c53f25faa56f096fd5ae083abf156148b70274532f5375464f045491c2a`.
