# Fundamentos de Nuvem ☁️

Repositório de apoio ao curso **Fundamentos de Nuvem** desenvolvido para a Alura.

---

## Sobre o Curso

Este curso apresenta conceitos fundamentais de computação em nuvem para cientistas de dados, utilizando exemplos práticos com dados reais do e-commerce brasileiro. Exploramos um pouco de todas as principais clouds do mercado, mas com foco especial no Google Cloud Platform (GCP).


## Conteúdo

### Aula 1: Introdução e Dados

- **Base de dados:** [Olist Brazilian E-Commerce Public Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)  
  > Dados de 100 mil pedidos da Olist Store entre 2016 e 2018.
- **Feriados nacionais:** [JSON de feriados](https://date.nager.at/api/v3/PublicHolidays/2025/BR)
- [O que é computação em nuvem?](https://cloud.google.com/learn/what-is-cloud-computing?hl=pt-br)

- Modelos de serviços em nuvem:  [PaaS vs IaaS vs SaaS](https://cloud.google.com/learn/paas-vs-iaas-vs-saas?hl=en)
- **Google Colab** pode ser considerado um modelo SaaS, mas também tem algumas referências que trazem ele como um [misto/hibrido de SaaS e PaaS](https://prof-frenzel.medium.com/kb-cloud-part-i-google-colab-for-data-projects-78fe3d079027).
  - É considerado principalmente um Software as a Service (SaaS), pois oferece um ambiente de desenvolvimento de notebooks Jupyter pronto para uso diretamente no navegador. Você usa o software sem se preocupar com a infraestrutura. No entanto, ele também possui características de Platform as a Service (PaaS), pois permite que desenvolvedores criem e executem seu próprio código (modelos de Machine Learning, análises de dados, etc.) em uma plataforma gerenciada pelo Google.
  

### Aula 2: Primeiros Passos na Nuvem

- Criando conta gratuita no Google Cloud:  
  [Google Cloud Free](https://cloud.google.com/free?hl=pt-br)


### Aula 3: Armazenamento de Dados

- Buckets no GCP:  
  [Documentação](https://cloud.google.com/storage/docs/buckets?hl=pt-br)
- BigQuery:  
  [Documentação](https://cloud.google.com/bigquery/docs?hl=pt-br)


### Aula 4: Python e Nuvem

- Notebook: [`_Aula_4_Python_e_Nuvem.ipynb`](https://github.com/letpires/FundamentosNuvem/blob/main/%F0%9F%93%93_Aula_4_Python_e_Nuvem.ipynb)


### Aula 5: IAM e Segurança

- IAM no GCP:  
  [Visão geral de princípios](https://cloud.google.com/iam/docs/principals-overview?hl=pt-br)
- [Contas de serviço](https://cloud.google.com/compute/docs/access/service-accounts?hl=pt-br)
- [Permissões e papéis do IAM](https://cloud.google.com/compute/docs/access/service-accounts?hl=pt-br)



## Estrutura do Repositório

```
📓 _Aula_4_Python_e_Nuvem.ipynb
📁 dados/
    ├── BR.json
    ├── olist_customers_dataset.csv
    ├── olist_geolocation_dataset.csv
    ├── olist_order_items_dataset.csv
    ├── olist_order_payments_dataset.csv
    ├── olist_order_reviews_dataset.csv
    ├── olist_orders_dataset.csv
    ├── olist_products_dataset.csv
    ├── olist_sellers_dataset.csv
    └── product_category_name_translation.csv
```


## Como Usar

1. Clone este repositório.
2. Explore os notebooks e os dados na pasta `dados/`.
3. Siga as instruções de cada aula para acompanhar o curso.
