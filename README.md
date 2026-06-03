# Resumo de Itens Vendidos (CSV)
 
Programa em Java que lê um arquivo `.csv` com itens vendidos e gera um novo arquivo com o valor total de cada item.
 
## O que o programa faz
 
1. Pede (ou recebe) o caminho de um arquivo `.csv` de origem.
2. Lê cada linha do arquivo. Cada linha contém:
   - **nome** do item
   - **preço unitário**
   - **quantidade**
   
   separados por vírgula.
3. Calcula o **valor total** de cada item (`preço unitário × quantidade`).
4. Gera um novo arquivo chamado `summary.csv` dentro de uma subpasta `out`, criada a partir da pasta onde está o arquivo de origem.
5. O arquivo de saída contém apenas o **nome** e o **valor total** de cada item.
## Exemplo
 
**Arquivo de entrada:**
```
TV LED,1290.99,1
Video Game Chair,350.50,3
Iphone X,900.00,2
Samsung Galaxy 9,850.00,2
```
 
**Arquivo de saída (`out/summary.csv`):**
```
TV LED,1290.99
Video Game Chair,1051.50
Iphone X,1800.00
Samsung Galaxy 9,1700.00
```
