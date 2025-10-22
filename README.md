# <img src="logo.png" alt="Logo QuantImport" width="70"> [QuantImport](https://quantimportbrazil.github.io/Sobre/)

---

# Fator mais Importante — Demonstração

> O nosso sistema de aprendizado de máquinas (ML) não somente faz a previsão como permite que se liste e quantifique a importância de cada fator que a afeta.  

**[Home](https://quantimportbrazil.github.io/Sobre/)**  

---

Para demonstrar a importância de diferentes fatores sobre uma previsão, dentre as previsões demonstrativas, escolhemos a que apresentou a maior variação percentual em relação ao ano anterior:  
* Produto NCM 31054000 - Município de Paranaguá-PR - MÊS 09/2026

Ela pode ser observada no gráfico a seguir:

![Gráfico de Previsão](31054000.png)

No mês 09 de 2025, note que:  
* Não esta presente a marcação com "X" verde no centro da previsão. Isso indica que o sistema prevê que essa determinada importação provavelmente não ocorrerá.
* A previsão quantitativa foi de aproximadamente 5 kt. Isso indica que o sistema prevê que, se a importação ocorrer, será de aproximadamente 5 kt.

No mês 09 de 2026, note que:
* O "X" verde aparece ao centro e com o tamanho máximo permitido. Isso indica que o sistema prevê que a importação muito provavelmente ocorrerá.
* A previsão quantitativa para esse momento é de aproximadamente 50 kt. 

O sistema indicou que vários fatores causaram essa grande mudança quantitativa percentual. Ele também indicou que, dentre os fatores, o que mais influente neste caso foi a intensa queda nas importações de determinado grupo de produtos na região de Barreiras/BA. Essa forte queda na importação pode ser vista no gráfico a seguir:

![Fator mais Importante](fator_mais_importante.png)  

Note que a queda na Bahia foi em grupo de produto que inclui o produto que esta sendo previsto no Paraná.

Isso é um exemplo claro da importância de se analisar conjuntamente todos os dados do Brasil para se prever as importações de um único município.  

---

## Notas Técnicas
* `*` Mesmo os valores aqui considerados reais são estimativas de nosso sistema, pois os dados divulgados não apresentam tal granularidade.  
* Formato das saídas: importância relativa dos fatores (scores) e, quando aplicável, séries temporais com intervalos de confiança.  
* A imagem acima (fator_mais_importante.png) está salva neste repositório; mantenha o nome e a capitalização exatos.

---

## Contato
**André Coutinho Bueno**  
Cientista de Dados e Fundador  
[andre.bueno@quantimport.com.br](mailto:andre.bueno@quantimport.com.br)
