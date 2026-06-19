# Uso de Sistemas de Informação em Empresas

## 1. Identificação do Problema de Negócio Original
No início dos anos 2000, a Netflix operava principalmente como um serviço de locação de DVDs por correio. O modelo tradicional de locadoras físicas sofria com sérios gargalos de estoque limitado, cobrança de multas por atraso que irritavam os clientes e limitações geográficas para alcançar novos públicos. Mesmo ao começar a migração para a internet, o desafio de negócio mudou drasticamente: como reter a atenção de milhões de usuários simultâneos, diminuir o cancelamento de assinaturas e entregar conteúdos altamente personalizados sem que o usuário ficasse perdido em um catálogo gigante?

---

## 2. Descrição Técnica da Solução (SI) Adotada
Para resolver a retenção e a distribuição em massa, a Netflix desenvolveu e adotou um complexo Sistema de Informação focado em Big Data e Algoritmos de Recomendação (um tipo avançado de Sistema de Apoio à Decisão - SAD voltado ao consumidor), estruturado por:

* **Módulo de Coleta e Telemetria de Dados:** O sistema monitora cada clique do usuário, o horário que assiste, quando pausa, quando abandona um filme, o dispositivo utilizado e até os termos pesquisados.
* **Algoritmos de Aprendizado de Máquina (Machine Learning):** Mecanismos como o Cinematch analisam bilhões de pontos de dados para criar perfis de preferência exatamente pensados no usuário. O sistema renderiza capas personalizadas diferentes do mesmo filme para usuários distintos, com base no que tem mais chance de atrair o clique.
* **Infraestrutura em Nuvem (AWS) e CDN (Open Connect):** Um sistema de distribuição de conteúdo descentralizado que armazena os arquivos de vídeo em servidores instalados dentro dos próprios provedores de internet locais, garantindo carregamento rápido e sem travamentos.

---

## 3. Nível Organizacional Primariamente Afetado
A solução impacta fundamentalmente o **Nível Estratégico** da empresa. Embora a recomendação mude a interface operacional do usuário em tempo real, os dados consolidados pelo sistema de informação ditam as decisões de alta liderança da Netflix. É através dessas análises macro de dados de consumo que a diretoria decide quais novas séries ou filmes originais serão produzidos, quais licenças serão renovadas e em quais mercados globais a empresa deve investir fundos bilionários.

---

## 4. Análise de Impacto nos Resultados e na Eficiência
A implementação desse robusto sistema de informação transformou a Netflix na maior plataforma de streaming do mundo, gerando os seguintes resultados:

* **Retenção de Clientes Extrema:** O sistema de recomendação é responsável por influenciar mais de 80% do conteúdo assistido na plataforma, reduzindo drasticamente o cancelamento de assinaturas.
* **Eficiência na Produção de Conteúdo:** Em vez de produzir programas baseados em "intuição", a Netflix utiliza os dados do SI para criar sucessos previsíveis (como a escolha de elencos, diretores e gêneros que já possuem público engajado mapeado pelo sistema).
* **Escalabilidade Global:** A arquitetura em nuvem e a rede de distribuição de dados permitiram expandir o serviço para mais de 190 países de forma rápida, sem a necessidade de construir locais físicos para armazenamento a forma antiga.
