## **Previsão do Valor Futuro de Ações**

### **Objetivo**
O principal objetivo deste projeto é desenvolver um modelo de previsão que possa prever o valor futuro de uma determinada ação com base em seus dados históricos. Utilizaremos a biblioteca Prophet para construir e treinar nosso modelo, enquanto os dados serão adquiridos por meio da API do Yahoo Finance.


### **Sobre o Projeto**
O mercado de ações é volátil e altamente imprevisível. No entanto, com o avanço da tecnologia e o acesso a dados históricos, tornou-se possível aplicar técnicas de aprendizado de máquina para prever os movimentos futuros do mercado com certa precisão. Neste projeto, exploramos essa ideia, utilizando duas poderosas ferramentas:

* **Prophet:** Desenvolvido pelo Facebook, o Prophet é uma biblioteca de análise de séries temporais que permite realizar previsões precisas e automatizadas com base em tendências sazonais e feriados.

* **Yahoo Finance API:** A Yahoo Finance oferece uma API robusta para acessar uma ampla variedade de dados financeiros, incluindo preços históricos de ações, informações sobre empresas e muito mais.


### **Descrição do Projeto**

1.  **Coleta de Dados:** Utilizaremos a API do Yahoo Finance para obter os dados históricos da ação que desejamos prever.
2.  **Pré-processamento dos Dados:** Os dados brutos obtidos serão processados e preparados para serem alimentados ao modelo Prophet.
3. ️ **Construção do Modelo:** Utilizaremos a biblioteca Prophet para construir nosso modelo de previsão com base nos dados históricos.
4. ️ **Treinamento do Modelo:** O modelo será treinado com os dados históricos para aprender os padrões e tendências presentes nos dados.
5.  **Previsão do Valor Futuro:** Finalmente, faremos previsões do valor futuro da ação com base no modelo treinado.



## **Resultados**
O modelo Prophet foi capaz de gerar previsões para o valor da ação.
<br>

Modelo previsto!
![previsao](https://github.com/FernandaPavan/Prever-valor-de-acao./assets/110939025/18437ad5-a8e1-4fd0-b342-c90ddd5e20d4)
<br>

Analisamos o final do periodo!
![periodo](https://github.com/FernandaPavan/Prever-valor-de-acao./assets/110939025/3ffab217-c819-42fc-84bf-499bb274132a)


No período analisado, as ações experimentaram um aumento significativo para um valor de 40, De Jan/28  até Feb/25, seguido por uma defasagem ao longo do mês de março. <br>

Em abril, houve uma breve recuperação até 05 de abril, seguida por uma nova queda, resultando em períodos de volatilidade com altos e baixos. <br>

Essa movimentação pode ser atribuída a uma série de fatores, incluindo resultados financeiros, sentimentos do mercado e notícias sobre a empresa. <br>

## **Conclusão**
Este projeto demonstra uma aplicação de modelos de séries temporais, como o Prophet, para prever os preços futuros de ações. Ao combinar técnicas de aprendizado de máquina com dados históricos, este trabalho oferece uma ferramenta valiosa para investidores e pesquisadores. As previsões geradas podem auxiliar na tomada de decisões mais informadas sobre compra, venda e alocação de ativos, contribuindo para a otimização de portfólios.
