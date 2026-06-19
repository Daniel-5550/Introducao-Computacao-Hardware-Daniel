# Desafio: Throttling Térmico (Superaquecimento)

## 1. Como o Throttling Térmico afeta o tempo de resposta do software?
Quando o processador chega perto do limite de temperatura (como 95°C), ele reduz a sua velocidade (frequência de clock) de forma automática para não queimar ou causar qualquer dano. Para o software, isso se traduz em lentidão imediata. O aplicativo começa a travar, demora muito mais para responder ou parece congelado para o usuário.

---

## 2. O que acontece com os dados na fila de processamento?
Como o processador passa a trabalhar em câmera lenta, o fluxo de dados congestiona:
* **No ciclo de instrução:** A parte que resolve as tarefas (ULA) fica lenta, acumulando as novas ordens que chegam da memória.
* **Na memória:** Os dados travam nos níveis mais rápidos (Registradores e Cache), esperando uma vaga para serem processados.
* **Nos barramentos:** As "avenidas" de comunicação da placa entopem, pois a memória RAM continua enviando dados, mas a CPU não consegue dar vazão.

---

## 3. Como desenvolvedores podem evitar esse problema no código?
Para evitar que o software sobrecarregue a CPU e cause esse superaquecimento, o engenheiro de software pode:
* **Escrever códigos mais leves:** Otimizar os algoritmos para reduzir o número bruto de cálculos que a CPU precisa fazer.
* **Organizar melhor os dados:** Criar estruturas de dados sequenciais (como vetores) que facilitam a leitura direta na memória Cache, economizando energia e esforço do sistema.
* **Dividir o trabalho (Multithreading):** Espalhar tarefas pesadas entre vários núcleos do processador para não sobrecarregar e esquentar apenas um deles.
