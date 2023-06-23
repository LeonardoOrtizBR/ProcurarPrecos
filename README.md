# 🚀 Procurar preço de produtos

Este repositório contém um projeto desenvolvido no Jupyter Notebook, chamado `Procurar preço de produtos.ipynb`, que automatiza a busca de preços de produtos nas plataformas Google Shopping e Buscaé. O objetivo desse projeto é fornecer uma solução simples para encontrar os melhores preços de produtos desejados, utilizando a biblioteca Selenium para controlar o navegador e o Pandas para interpretar planilhas.

## 📋 Como funciona o código

O projeto utiliza um arquivo auxiliar chamado `buscas.xlsx`, que contém uma tabela com as seguintes colunas:

- Nome de produtos: Permite ao usuário informar o nome do produto que deseja pesquisar.
- Termos banidos: Permite ao usuário especificar termos que devem ser evitados na busca, para evitar retornar produtos indesejados.
- Preço mínimo: Permite ao usuário estipular um valor mínimo para encontrar o produto desejado.
- Preço máximo: Permite ao usuário estipular um valor máximo para encontrar o produto desejado.

Após preencher as informações na tabela e salvar, o usuário deve também configurar o e-mail para onde deseja receber os resultados da pesquisa. Se receber um e-mail sem uma tabela de produtos e links, significa que não foram encontrados itens com o nome desejado ou dentro da faixa de preço estipulada.

Ao executar o código, que requer a instalação das bibliotecas necessárias, ele realizará automaticamente a busca dos preços dos produtos, permitindo ao usuário realizar outras tarefas no computador. Para simplificar o processo, é possível transformar o código em um executável.

⚙️ Execução do código

Para executar o código, siga as etapas abaixo:

1. Certifique-se de ter o programa Jupyter instalado em sua máquina.
2. Faça o download do arquivo `Procurar preço de produtos.ipynb` neste repositório.
3. Abra o arquivo no Jupyter Notebook.
4. Verifique se todas as bibliotecas necessárias estão instaladas no seu ambiente Python.
5. Certifique-se de ter o arquivo `buscas.xlsx` no local correto, preenchido com as informações dos produtos desejados.
6. Configure o e-mail de destino para receber os resultados da pesquisa.
7. Execute as células do notebook na ordem adequada.

📦 Arquivos gerados

Após a execução do código, um arquivo chamado `Ofertas.xlsx` será gerado. Esse arquivo conterá os resultados da pesquisa, incluindo os produtos encontrados e seus respectivos links.

Abaixo, uma imagem de como o e-mail é recebido:

![PrintEmail](https://github.com/LeonardoOrtizBR/ProcurarPrecos/assets/135072424/a1cbed9c-fea8-494a-93c5-e0d82e9cee16)

---

*Nota: O projeto apresentado é uma demonstração simples e pode ser aprimorado conforme suas necessidades. Sinta-se à vontade para personalizá-lo e adicionar recursos adicionais conforme desejado.*

