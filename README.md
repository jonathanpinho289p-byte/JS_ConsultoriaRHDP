# JS Consultoria RH e DP

Site institucional da JS Consultoria, com informações sobre serviços, diagnóstico, contato e radar trabalhista.

## Publicação

A Netlify publica apenas a pasta `site/`, conforme `netlify.toml`. O site é estático: não depende de compilação, banco de dados ou login de visitantes. Depois que os arquivos entrarem na branch `main`, o projeto poderá usar o fluxo de deploy do repositório conectado.

## Manutenção

- `site/index.html` reúne a página, os estilos e os scripts.
- `site/noticias.json` contém a seleção de notícias exibida no radar. Esta versão não executa coleta automática.
- O formulário do Banco de Talentos está integrado ao Formspree. O recebimento deve ser validado após a publicação. A política prevê conservação por até seis meses, salvo obrigação legal de conservação por prazo diferente; a JS deve aprovar e aplicar esse prazo aos dados no Formspree e no e-mail.
