# You Shall Not DEPLOY 🛑✨

## Descrição
**You Shall Not DEPLOY** é uma solução que ajuda equipes de desenvolvimento a evitar deploys em dias críticos, como sextas-feiras, finais de semana e feriados. Ao utilizar esta ferramenta, você pode garantir maior estabilidade em produção, evitando mudanças em horários propensos a problemas.

## Funcionalidades
- 🚫 Impede deploys em sextas-feiras.
- 🚫 Bloqueia deploys durante o fim de semana.
- 🚫 Respeita uma lista de feriados personalizáveis.
- ✅ Fácil integração com pipelines de CI/CD utilizando GitHub Actions.
- ✅ Flexível para adicionar comandos e etapas de deploy customizados.

## Como Funciona
O workflow verifica a data atual antes de iniciar o processo de deploy. Caso a data coincida com um dia bloqueado (sexta-feira, fim de semana ou feriado), o pipeline é interrompido automaticamente, evitando qualquer alteração em produção.

## Como Implementar
1. **Criação do Workflow**: Adicione um workflow específico no seu repositório que verifica a data antes de permitir o deploy.
2. **Script Python**: O repositório já contém um script que verifica a data e compara com os dias bloqueados.
3. **Customização do Deploy**: Configure os passos de deploy de acordo com suas necessidades.

## Benefícios
- 🔒 **Segurança**: Reduz o risco de problemas em produção ao evitar deploys em dias críticos.
- ⚙️ **Automação**: Integração simples com GitHub Actions para automatizar verificações de deploy.
- 📅 **Flexibilidade**: Permite adicionar novos feriados ou ajustes conforme necessário.

## Contribuições
Contribuições são sempre bem-vindas! Se você tiver ideias para novas funcionalidades ou melhorias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*. 
