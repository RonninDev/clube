# Button Tracker e WP-CLI Button Tracker Report

## Instalação dos Plugins

1. Acesse o Painel Administrativo do WordPress.
2. Vá em Plugins > Adicionar Novo.
3. Inclua os arquivos .zip dos plugins e faça as duas instalações.
4. Ative ambos os plugins.

## Adicionando o Botão de Rastreamento

1. No Painel Administrativo, vá em Páginas > Adicionar Nova.
2. Adicione o shortcode `[bt_button]` no editor de conteúdo onde desejar que o botão apareça.
3. Publique a página.

## Gerando Relatório de Cliques


Em um ambiente utilizando o WP-CLI abra o terminal na raiz do seu site WordPress e execute:
wp button-tracker report
