# DAS ESCOLHAS

## DevContainer

O objetivo dessa escolha foi padronizar o ambiente de desenvolvimento, garantindo consistência entre diversas máquinas e equipes. Ele permite que todas as dependências, ferramentas e configurações do projeto sejam definidas e versionadas, simplificando a integração de novos desenvolvedores e evitando problemas relacionados à configuração de ambientes locais. Além disso, ele facilita o desenvolvimento em ambientes isolados, tornando mais prático trabalhar com múltiplos projetos sem a interferência entre versões de bibliotecas ou outras dependências.

## Husky

A escolha de usar o Husky se deu pela necessidade de garantir a execução de scripts automatizados durante eventos do Git, como commits ou push. Isso permite manter um padrão de qualidade no código ao rodar testes, linters ou verificações de formatação automaticamente antes de as alterações serem enviadas ao repositório.

## Commitizen

O Commitizen foi escolhido para padronizar as mensagens de commit, facilitando a geração de changelogs e mantendo o histórico do projeto organizado. Com a sua implementação, os desenvolvedores são guiados na escrita de mensagens mais claras e consistentes, o que ajuda na manutenção do projeto a longo prazo.

## Commitlint

O uso do Commitlint garante que as mensagens de commit sigam o padrão estabelecido. Ele atua como uma camada adicional de verificação, rejeitando commits que não estão no formato correto, alinhando o histórico de commits e garantindo uma base de código mais organizada.

## Lint-staged

Para otimizar a execução de scripts no código que está sendo versionado, o Lint-staged foi escolhido. Ele possibilita rodar linters e formatadores apenas nos arquivos modificados em cada commit, o que aumenta a eficiência e velocidade do processo de verificação de código, garantindo que somente os arquivos relevantes sejam processados.

## Depcheck

O Depcheck foi escolhido para identificar dependências não utilizadas no projeto, ajudando a manter o código enxuto e eficiente. Com ele, é possível garantir que o projeto não acumule dependências desnecessárias, melhorando o desempenho e facilitando a manutenção do ambiente de desenvolvimento.
