# Filtro de Dados de Geração Distribuída

Este repositório contém um script em Python para carregar, filtrar e salvar um subconjunto de dados a partir de um arquivo CSV com informações sobre empreendimentos de geração distribuída no Brasil.

## 📂 Estrutura do Projeto
- **`empreendimento-geracao-distribuida.csv`**: Arquivo de entrada contendo os dados completos.
- **`filtro_dados.py`**: Script Python para processamento e filtragem dos dados.
- **`empreendimentosGD_PI.csv`**: Arquivo de saída com dados filtrados para o estado do Piauí.
- **`Exportação`**: Os dados filtrados são exportados para um arquivo CSV.
- **`Dashboard no Power BI`**: Utiliza-se o arquivo CSV gerado para criar visualizações interativas.

## 📌 Funcionalidades
- Carregamento do arquivo CSV com encoding `latin-1` e separador `;`.
- Exibição das colunas do dataset.
- Identifica os estados presentes no conjunto de dados.
- Filtra os dados apenas para empreendimentos localizados no Piauí (`PI`).
- Salva o novo arquivo filtrado no formato CSV.

## 🚀 Como Usar
1. Clone o repositório ou baixe os arquivos.
   ```sh
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```
2. Instale as dependências necessárias.
   ```sh
   pip install pandas
   ```
3. Execute o script Python.
   ```sh
   python filtro_dados.py
   ```
4. O arquivo filtrado será salvo como `empreendimentosGD_PI.csv`.

## 📊 Bibliotecas Utilizadas
- `pandas`: Para manipulação de dados em DataFrame.

## Dashboard no Power BI

1. **Abrir o Power BI**
2. **Importar os dados:**
   - Clique em **Obter Dados** > **Texto/CSV**
   - Selecione o arquivo `empreendimentosGD_PI.csv`
3. **Criar as visualizações:**
   - Utilize **gráficos de barras**, **mapas**, **tabelas dinâmicas** e outros elementos para analisar:
     - Distribuição dos empreendimentos por cidade
     - Potência instalada por tipo de geração
     - Evolução dos empreendimentos ao longo do tempo
4. **Publicar e compartilhar o dashboard**

## Exemplo de Dashboard
Um exemplo de dashboard pode incluir:
- **Mapa interativo** com a localização dos empreendimentos
- **Gráfico de barras** mostrando a potência instalada por tipo de geração
- **Tabela dinâmica** com detalhes dos empreendimentos

## 📜 Licença
Este projeto está sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.



