# Sistema de Gerenciamento de Hotel

Este é um simples sistema de gerenciamento de hotel desenvolvido em C. Ele permite cadastrar hóspedes, listar hóspedes em ordem alfabética, buscar hóspedes pelo nome, editar o nome de um hóspede, liberar um quarto e mostrar quartos vazios disponíveis no hotel. Abaixo estão detalhadas as principais funcionalidades e instruções para compilar e executar o programa.

## Funcionalidades

- **Cadastro de Hóspedes**: Permite cadastrar um novo hóspede informando seu nome e o número do quarto.
- **Listagem em Ordem Alfabética**: Lista os hóspedes em ordem alfabética pelo nome.
- **Busca por Hóspede**: Permite buscar um hóspede pelo nome.
- **Edição do Nome do Hóspede**: Permite editar o nome de um hóspede cadastrado.
- **Liberação de Quarto**: Libera um quarto removendo o hóspede associado a ele.
- **Exibição de Quartos Vazios**: Mostra os quartos vazios disponíveis no hotel.
- **Salvar e Carregar Lista de Hóspedes**: Salva e carrega a lista de hóspedes de/para um arquivo.

## Como Compilar e Executar

1. **Compilação**: Utilize um compilador C, como GCC, para compilar o programa. Por exemplo:

   ```bash
   gcc hotelaria.c -o hotelaria
### Menu Principal: 
O programa exibirá um menu com as opções disponíveis. Escolha uma opção digitando o número correspondente e pressione Enter.

## Operação: 
Siga as instruções fornecidas pelo programa para realizar as operações desejadas.

## Observações:
- Limitações de Número de Quartos e Tamanho do Nome: 
  O número máximo de quartos e o tamanho máximo do nome estão definidos como macros (`MAX_QUARTOS` e `MAX_NOME`, respectivamente) e podem ser ajustados conforme necessário.
- Arquivo de Lista de Hóspedes: 
  O programa salva e carrega a lista de hóspedes de/para um arquivo chamado `hospedes.txt` no diretório atual. Certifique-se de que o programa tenha permissão para escrever neste arquivo.

Este sistema de gerenciamento de hotel oferece uma maneira simples e eficiente de gerenciar os hóspedes de um hotel. Se tiver mais perguntas ou precisar de assistência adicional, não hesite em entrar em contato!
