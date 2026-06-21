# 🐧 Projeto 30 — Clustering de Pinguins com K-means

## Objetivo
Aplicar o algoritmo **K-means** para segmentar espécies de pinguins (Adelie, Chinstrap e Gentoo) com base em características físicas, validando o uso de clustering em dados biológicos.

## Ferramentas Utilizadas  
- **Python**  
- **Pandas | NumPy | Seaborn | Matplotlib | Scikit-learn**| **K-means|**
- **Jupyter Notebook**  

---

## Etapas
1. **Carregamento e exploração da base**  
2. **Pré-processamento**: tratamento de valores faltantes e padronização  
3. **Aplicação do K-means** para identificar clusters  
4. **Visualização dos grupos formados**  
5. **Comparação com as espécies reais**  

## Variáveis da Base de Dados (penguins - Seaborn)
- **species** → Espécie do pinguim (Adelie, Chinstrap, Gentoo)  
- **island** → Ilha onde o pinguim foi observado (Biscoe, Dream, Torgersen)  
- **bill_length_mm** → Comprimento do bico (mm)  
- **bill_depth_mm** → Profundidade do bico (mm)  
- **flipper_length_mm** → Comprimento da barbatana (mm)  
- **body_mass_g** → Massa corporal (g)  
- **sex** → Sexo do pinguim (Male, Female)  
- **year** → Ano da observação  

## Resultado
- **Cluster 0 → Adelie** (maioria, mas com alguns Chinstrap misturados)  
- **Cluster 1 → Gentoo** (separação clara por massa corporal e barbatana)  
- **Cluster 2 → Chinstrap** (bem definido, mas próximo dos Adelie)  

**Insight resumido:**  
O K-means separou bem os Gentoo, isolados por maior massa corporal e comprimento da barbatana.  
Adelie e Chinstrap permanecem próximos, com sobreposição em algumas variáveis.  
As variáveis mais relevantes foram **flipper_length_mm** e **body_mass_g** para distinguir Gentoo, e **bill_length_mm** e **bill_depth_mm** para diferenciar Adelie e Chinstrap.
  
---

## Aplicações de Clusterização
- **Segmentação de clientes** → agrupar consumidores por comportamento de compra.  
- **Agrupamento de documentos** → organizar textos em grupos temáticos.  
- **Análise genética** → identificar padrões em DNA/RNA para pesquisas médicas e evolutivas.  

---

 Este projeto demonstra uma aplicação prática de **Machine Learning não supervisionado**

---

## Autoria  
Projeto desenvolvido por **Maria Santos**, como parte da atividade do curso **Ciências de Dados - EBAC - Módulo 30**.  
