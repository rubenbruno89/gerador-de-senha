# Gerador de Senhas para Impressora Térmica

## Descrição
Este é um gerador de senhas para impressão em uma impressora térmica, desenvolvido em HTML, CSS e JavaScript. Ele permite ao usuário gerar uma ou várias senhas com personalizações específicas, como o comprimento da senha e a inclusão de caracteres maiúsculos, minúsculos, números e símbolos. Além disso, o sistema inclui uma opção de pré-visualização para impressão e um recurso de conexão com a impressora térmica via WebUSB.

## Funcionalidades
- **Geração de Senhas**: Gere uma ou várias senhas conforme as preferências definidas (letras maiúsculas, minúsculas, números, e símbolos).
- **Pré-visualização de Impressão**: Visualize as senhas geradas antes de imprimir.
- **Impressão Térmica**: Conexão com impressoras térmicas suportadas usando WebUSB.
- **Interface Responsiva**: Interface simples e adaptável para facilitar o uso em diferentes dispositivos.

## Estrutura do Projeto
- **HTML/CSS**: Interface de usuário estilizada e responsiva, com uso de `:root` para temas e `media print` para ajuste da visualização de impressão.
- **JavaScript**: Funções para gerar e personalizar senhas, controle de impressão e comunicação com impressoras via WebUSB.

## Requisitos
- **Navegador compatível com WebUSB**: Para imprimir diretamente na impressora térmica, é necessário um navegador com suporte a WebUSB.
- **Impressora Térmica**: Uma impressora compatível com WebUSB e que suporte o `vendorId` correto.

## Uso
1. Abra o arquivo `index.html` em um navegador com suporte a WebUSB.
2. Configure as opções de senha (quantidade, comprimento, letras, números, e símbolos).
3. Clique em **"Gerar Senhas"** para visualizar as senhas.
4. (Opcional) Para imprimir, clique em **"Imprimir Senhas"**.
5. **Conectar Impressora Térmica**: Clique no botão de impressão ou utilize a função `printToThermalPrinter()`.

## Estrutura do Código
- **HTML**: Estrutura principal e design da interface.
- **CSS**: Estilos para a interface, incluindo temas e efeitos.
- **JavaScript**:
  - Geração de senhas: Funções para configurar e gerar senhas aleatórias.
  - Comunicação com impressora: Funções para conexão e envio de comandos para a impressora térmica.
  - Função `connectThermalPrinter()` para realizar a conexão com a impressora, e `printToThermalPrinter()` para enviar o conteúdo a ser impresso.

## Licença
Este projeto está licenciado sob a licença MIT.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
