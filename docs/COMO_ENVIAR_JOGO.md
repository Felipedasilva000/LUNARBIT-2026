# Como finalizar a publicação do jogo

A documentação do projeto já foi publicada neste repositório.

## Enviar o projeto Godot completo

A integração ChatGPT–GitHub permite a publicação de arquivos de texto, mas não consegue enviar diretamente o arquivo ZIP binário montado localmente. Por isso, resta **uma etapa manual** para disponibilizar todos os sprites e cenas.

### Opção rápida: disponibilizar o ZIP
1. Baixe o arquivo `LUNARBIT_GitHub_PRONTO.zip` entregue no ChatGPT.
2. Neste repositório, selecione **Add file → Upload files**.
3. Arraste o ZIP (aproximadamente 18 MB) para a página.
4. Clique em **Commit changes** na ramificação `main`.

Quem quiser testar deverá baixar o ZIP, extrair a pasta, abrir o arquivo `project.godot` pelo Godot 4 e executar com **F5**.

### Opção melhor: arquivos separados
Use o GitHub Desktop para publicar toda a pasta extraída, mantendo a estrutura de diretórios; não publique a pasta gerada `.godot/`. A pasta compactada já contém `.gitignore` para excluir os caches.

## Submissão NASA
Copie o link `https://github.com/Felipedasilva000/LUNARBIT-2026` para a página do projeto da equipe no Space Apps. Publicar o repositório por si só **não** finaliza a inscrição.

## Transparência
O protótipo contém limitações de troca de cenas e missões ainda em desenvolvimento. Consulte `docs/ESTADO_DO_PROTOTIPO.md`.
