# Aula 11 – Redes de Computadores: Topologias, Dispositivos e Meios

### 1. Diagramas de Topologias
- Representação das principais topologias de rede:
![Quadro comparativo](./diagrama1.png)

### 2. Quadro Comparativo de Dispositivos
![Quadro comparativo](./comparativo.png)

### 3. Meios de Transmissão
### Meios Guiados (Com fio)
1.  **Par Trançado (UTP/STP):** Um entrelaçado de fios de cobre, largura da banda depende da epsessura do cabo, muito utilizado em lan, utiliza conectores RJ45.
2.  **Cabo Coaxial:** Utilizado para TV a cabo e algumas conexões de banda larga, melhor blindagem do que o trançado, assim podendo se estender por maiores distâncias e oferencendo melhor conexão, é um fio de cobre ao centro protegido por algum materia isolante onde o mesmo é envolvido por um material condutor (normalmente uma malha) assim sendo envolvido na camada de plástico protetora.
3.  **Fibra Óptica:** Utiliza um feixe de luz que percorre toda a extensão do cabo. Oferece as maiores velocidades e não sofre interferência eletromagnética, é chamada de "guiada" pois as ondas eletromagnéticas são guiadas pela fibra, as fibras são feitas de plástico ou normalmente vidro (por absorver menos as ondas), Para transmitir dados pela fibra ótica são necessários equipamentos especiais que contém um componente fotoemissor que pode ser um diodo emissor de luz (LED) ou um diodo laser, é uma tecnologia muito boa para velocidade porém com custo elevado.

### Meios Não Guiados (Sem fio)
1.  **Wi-Fi (802.11):** Transmissão por ondas de rádio para redes locais sem fios, alta velocidade, permite conexão de múltiplos dispositivos a um ponto central, sinal atravessa paredes, porém sofre ao atravessar objetos densos e altas distâncias, segurança alta porém complexa, custo moderado, porém pode sofrer de interferências por alta taxa de conexão.
2.  **Bluetooth:** Comunicação de curto alcance para dispositivos periféricos (PAN), baixo consumo de energia para a conexão, alta segurança no emparelhamento, é consideravelmente mais lento do que o WI-FI, é eficiente apenas em curtas distâncias (em torno de 10 metros).
3.  **Satélite:** Ideal para áreas remotas onde cabos não chegam; possui latência mais elevada, pode ser usada em grandes distâncias, o custo não depende da distância da comunicação, porém o custo é elevado e a instalação de antenas parabólicas é difícil.
4.  **Infravermelho:** Requer contato direto e curta distância, comum em controlos remotos, freqência extremamente alta, largura de banda alta, não atravessam paredes logo podem ser isoladas, tendo pouca interferência, sendo segura e de alta velocidade, porém pode sofrer interferência dos raios solares e não funciona a longas distâncias.
5.  **Rádio:** São ondas eletromagnéticasde frequência muito baixa que se transmitem em todas as direções dentro do seu alcance (entre 3Khz a 1Ghz), antenas não precisam ter um alinhamento estratégico, rede adequada para uso em longas distâncias, o sinal atravessa paredes, porém não é possivel isolar a comunicação e também pode sofrer de interferência se outra frequência igual ou parecida estiver próxima.
6.  **micro-ondas:** Nesse tipo de transmissão por micro-ondas, as antenas do transmissor e do receptor estão em linha reta uma com a outra, custo baixo por não precisar de torre de comunicação, conexão lenta e sujeita a interferência, pode ser implementada em zonas de difícil acesso como montanhas, porém é pouco segura sujeita a escutas.
- Esquema visual mostrando como os meios conectam os dispositivos.
![Quadro comparativo](./meios_transmissao.png)

fontes: 
[Redes de computadores (TANENBAUM)](https://plataforma.bvirtual.com.br)

[Meios de transmissão não guiados](https://beginnersbook.com/2021/12/types-of-transmission-media-guided-and-unguided/)

[Meios de transmissão guiados](https://estudoderedes.wordpress.com/2012/01/17/meios-de-transmissao-guiados/)

[curiosidades e informações adicionais](https://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)


