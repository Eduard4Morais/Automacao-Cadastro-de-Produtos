# Automação de Cadastro de Produtos

## Descrição
Um projeto de automação em Python que visa simplificar e otimizar o processo de cadastro de produtos em um sistema web. O script utiliza a biblioteca `pyautogui` para simular interações humanas com a interface do usuário, permitindo a adição de dados de forma automatizada e eficiente.

## Estrutura do Projeto
- **Python Power Up**: Diretório principal contendo o código do projeto.
   - **codigo.py**: Arquivo principal que controla o fluxo do programa e realiza o cadastro automatizado.
   - **auxiliar.py**: Módulo de suporte contendo informações auxiliares para processamento dos dados.
- **data**: Pasta de dados onde os arquivos necessários para a automação estão armazenados.
   - **produtos.xlsx**: Planilha contendo os dados dos produtos que serão cadastrados automaticamente 

## O Desafio
O projeto busca resolver a falta de produtividade de registrar produtos manualmente, o que pode ser demorado e propenso a erros. Com a automação, espera-se aumentar a eficiência e a precisão no cadastro de produtos

## Como
Esta seção oferece uma visão geral de como utilizar o código Python para automatizar o cadastro de produtos. O código foi projetado para ser fácil de usar e modificar conforme necessário.

## Funcionalidades
1. **Preparação do Ambiente**: Configuração e inicialização do ambiente para o cadastro de produtos no sistema web, garantindo que o ambiente esteja pronto para receber os dados.
2. **Leitura de Dados**: Importação de dados da planilha `produtos.xlsx`.
3. **Processamento de Dados**: Processamento dos dados para garantir que estejam formatados corretamente antes do cadastro.
4. **Cadastro Automático**: Execução do cadastro dos produtos simulando a adição dos dados no sistema desejado. 

### Pré-requisitos
Antes de usar este código, certifique-se de ter o seguinte instalado:
* Python (versão recomendada: 3.6+)
*  Bibliotecas necessárias:
    * `pyautogui`
    * `pandas` (caso utilize arquivos CSV)
    * `openpyxl`

 Instale as bibliotecas necessárias usando o seguinte comando:
 ```
pip install pyautogui openpyxl pandas
```
Essas bibliotecas são fundamentais para manipulação de dados, integração com planilhas Excel e automação da interface gráfica do usuário.

## Como Executar o Projeto

1. **Configurar os Dados**: Certifique-se de que o arquivo `produtos.xlsx` na pasta `data` está atualizado com os dados corretos dos produtos.
2. **Executar o Script Principal**: Para iniciar o processo de cadastro automatizado de produtos, execute o arquivo `codigo.py` localizado no diretório `Python Power Up`. No terminal, navegue até a pasta do projeto e execute o seguinte comando:
```
python "Python Power Up/codigo.py"
```
3. **Observações**:
   * Verifique se todas as dependências estão instaladas.
   * Certifique-se de que os `produtos.xlsx` estão no diretório `data` conforme especificado.

## Links Úteis
* Documentação do **PyAutoGUI**: [PyAutoGUI Documentation](https://pyautogui.readthedocs.io/en/latest)
* Tutorial de Automação com Python: [Tutorial](https://automatetheboringstuff.com)
