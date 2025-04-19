# Projeto-Health : Análise Geográfica de Centros de Tratamento Emergenciais nos EUA

## 📖 Sobre o Projeto

Em 2025, a gestão eficiente do acesso à saúde pública é mais crucial do que nunca.  
Este projeto analisa e visualiza **mais de 65.000 centros médicos de tratamento emergencial** nos Estados Unidos, utilizando dados oficiais da plataforma HealthData.gov.

O objetivo é entender a distribuição dos centros, identificar padrões de acessibilidade e disponibilizar uma visualização interativa que apoie novas pesquisas e políticas de saúde.

---

## 🎯 Objetivos

- Analisar a distribuição geográfica dos centros de tratamento emergenciais.
- Avaliar a cobertura para COVID-19 e Influenza.
- Medir a disponibilidade de serviços de Home Delivery.
- Estudar a tipologia de estabelecimentos médicos através de complementos de endereço.
- Criar visualizações impactantes para melhor compreensão espacial.
- Publicar mapa interativo acessível ao público.

---

## 📊 Estatísticas Relevantes do Estudo

| Item Analisado | Resultado |
|:--|:--|
| Centros Totais Mapeados | 65.967 centros |
| Estados com maior concentração | Flórida (FL), Texas (TX), Califórnia (CA) |
| Centros oferecendo Home Delivery | ~30% |
| Centros atendendo COVID-19 | ~100% |
| Centros atendendo Influenza | ~40% |
| Padrões de endereço detectados | "SUITE", "STE", "ROOM", "UNIT" (indicando farmácias, clínicas e shoppings) |

---

## 🗺️ Sobre o Mapa Interativo

Criamos duas versões do mapa:

- **Mapa Completo**: Inicialmente gerado com **todos os 65.967 centros**.
  - Devido ao tamanho (> 25MB), não é possível fazer upload via GitHub direto.
  - Mantido no notebook como referência para estudo completo.
  
- **Mapa Reduzido**: Versão otimizada com **5.000 centros** selecionados aleatoriamente.
  - Publicado no GitHub Pages para acesso rápido e dinâmico.
  - Ideal para visualização pública sem perda de representatividade.

### 📎 Acesse o mapa reduzido:
https://github.com/Rebelo81/ProjHealth-map.git

## 📈 Insights Estratégicos

- 🔹 **Concentração desigual**: Altos volumes em áreas urbanas contrastam com carência em zonas rurais.
- 🔹 **Possibilidades de expansão**: A falta de centros em regiões afastadas indica potenciais áreas de investimento para novas clínicas e farmácias.
- 🔹 **Importância do Home Delivery**: Com 30% dos centros oferecendo entrega de medicamentos, ampliar este serviço pode melhorar o alcance em comunidades vulneráveis.
- 🔹 **Complementos de endereço ("Suite", "Unit")**: Indicam forte presença de atendimento em shoppings e centros comerciais, não apenas em hospitais tradicionais.

---

## 🌍 Impacto Social e Futuras Aplicações

Este estudo pode:

- Apoiar políticas públicas na **expansão de serviços de saúde** em regiões carentes.
- Servir de base para **modelos preditivos** de onde instalar novos centros médicos.
- Incentivar estudos acadêmicos sobre **desigualdade no acesso à saúde**.
- Apoiar empresas farmacêuticas e redes hospitalares na **tomada de decisão estratégica** para abertura de novas unidades.

---

## 🚀 Como Executar o Projeto Localmente

```bash
git https://github.com/Rebelo81/Projeto-Health.git
cd Projeto-Health
pip install -r requirements.txt
