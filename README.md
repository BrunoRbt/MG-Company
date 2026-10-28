# Sessão estratégica | Lucas Andrade

Landing page estática para o teste prático. A implementação usa apenas HTML e CSS, sem framework, JavaScript ou etapa de build.

## Recursos

- Alternância entre português e inglês sem recarregar a página, usando controles HTML nativos e CSS.
- Tema claro e escuro, também controlado por CSS.
- Layout responsivo para desktop e celular.
- Navegação móvel expansível com o elemento HTML `<details>`.

## Abrir localmente

Abra `index.html` em um navegador. Para uma prévia por servidor local, sirva a pasta raiz do repositório como conteúdo estático; não há comando de build.

## Formulário

O material do teste não informa um endereço de e-mail, API ou outro destino para receber aplicações. Por isso, o formulário é apenas visual e o botão de envio permanece desabilitado. Nenhum dado digitado é transmitido ou armazenado.

## Publicação estática

Não há etapa de build. Para publicar pelo GitHub Pages, configure `GitHub Actions` como fonte em **Settings → Pages**. O workflow em `.github/workflows/deploy.yml` publica automaticamente a cada atualização da branch `main` e envia apenas `index.html` e `styles.css` para o site.

O repositório também pode ser conectado ao Netlify ou Vercel com o comando de build vazio e a raiz do projeto como diretório de publicação. O envio do formulário exige um destino fornecido pelo responsável pelo projeto.
