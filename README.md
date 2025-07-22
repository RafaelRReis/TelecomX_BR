# 📊 Análise de Evasão de Clientes (Churn) - TelecomX_BR

## 📌 Sobre o Projeto
Este projeto tem como objetivo **analisar a evasão de clientes (Churn)** em uma empresa de telecomunicações.  
O churn é um dos maiores desafios do setor, pois a **perda de clientes** impacta diretamente a receita e aumenta os custos de aquisição de novos consumidores.  

Por meio da análise exploratória e do tratamento dos dados, foram identificados os **principais fatores que levam ao cancelamento de contratos** e sugeridas **ações estratégicas para retenção**.

---

## 🗂 Estrutura do Projeto

```
TelecomX_BR/
│
├── TelecomX_BR.ipynb        # Notebook completo com ETL, EDA e relatório final
├── data/                    # (Opcional) Pasta para armazenar datasets
├── images/                  # Gráficos e visualizações gerados
└── README.md                # Este arquivo
```

---

## 🔧 Tecnologias Utilizadas

- **Python 3.9+**
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn (para pré-processamento)
  - jupyter ou Google Colab

---

## 🚀 Como Executar

1. **Clone o repositório**  
```bash
git clone https://github.com/SEU_USUARIO/TelecomX_BR.git
cd TelecomX_BR
```

2. **Instale as dependências**  
```bash
pip install -r requirements.txt
```
*(Você pode gerar o `requirements.txt` com `pip freeze > requirements.txt` após testar o projeto).*

3. **Execute o notebook**  
- Via Jupyter:  
```bash
jupyter notebook TelecomX_BR.ipynb
```
- Ou no **Google Colab** (recomendado): basta fazer upload do notebook.

---

## 📊 Principais Insights

- **Contratos mensais** e **pagamento eletrônico (Electronic Check)** são os principais preditores de evasão.
- **Clientes com menos de 1 ano de contrato** e sem serviços adicionais cancelam com mais frequência.
- **Clientes mais antigos e com múltiplos serviços** são mais fiéis.

### 🔥 Recomendações

1. Incentivar migração para **contratos anuais** com descontos.
2. Criar **campanhas de retenção** para clientes com menos de 1 ano de contrato.
3. Melhorar a **experiência no pagamento eletrônico**.
4. Oferecer **pacotes de serviços combinados** para aumentar o engajamento.

---

## 📷 Exemplos de Visualizações

![Churn por Tipo de Contrato](images/analise_de_evasao_variaveis_categoricas.png)  
![Heatmap de Correlação](images/analise_de_evasao_variaveis_numericas.png)

---

## ✒️ Autor
Projeto desenvolvido por **Rafael R. R.**  
📫 Contato: [SEU_EMAIL] | [LinkedIn](SEU_LINKEDIN)
