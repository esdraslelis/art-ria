# Arteris — publicação na Hostinger

O site é HTML estático, **não é WordPress** e não deve ser enviado pelo serviço de migração/importação automática.

## Publicar
1. Abra hPanel → Arquivos → Gerenciador de Arquivos.
2. Acesse `public_html/` do domínio correto.
3. Faça backup de arquivos antigos e remova a versão anterior.
4. Envie `Arteris_SITE_PUBLICAR_Hostinger.zip`, extraia **dentro de `public_html`**.
5. Confira que `public_html/index.html`, `public_html/slide1.html`, `public_html/Fotos/` e `public_html/Rota28/` existem. **Não** deve existir uma pasta intermediária `Arteris/`.
6. Visite `https://seu-dominio/` e `https://seu-dominio/slide1.html`.

O pacote contém `.htaccess` com `DirectoryIndex index.html`. **Não publicar** pastas de contratos/documentos confidenciais em um site público. Revise fotografias e informações pessoais antes de expor.

O ZIP pronto para Hostinger foi entregue no chat e ainda precisa ser enviado à hospedagem. O repositório ainda não contém todos os ativos do site.
