# :arrow_forward: Como executar o projeto?
  
### Inicialmente será necessário instalar: 

:arrows_counterclockwise: Compilador e gerenciador de pacotes da linguagem Haskell ([GHC e Cabal](https://www.haskell.org/platform/linux.html))

  ```
  $ sudo apt-get install haskell-platform 
  ```

:inbox_tray: Biblioteca utilizada para construção do Banco de Dados ([SQLSimple](https://hackage.haskell.org/package/sqlite-simple))

  ```
  $ cabal install sqlite-simple
  ```

### Após a etapa de instalação, basta apenas executar os comandos abaixo e o ALOKA estará à sua disposição.

  ```
  $ cd Funcional
  $ runhaskell Main.hs
  ```
