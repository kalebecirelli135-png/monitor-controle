# Controle do Monitor de Switches

Este arquivo liga e desliga o programa Monitor de Switches.

- Para **desligar**: edite `controle.txt` e deixe assim:
  ```
  BLOQUEADO
  Mensagem que aparece na tela.
  ```
- Para **religar**: deixe `controle.txt` com uma única linha: `ATIVO`

O programa confere ao abrir e a cada 10 minutos.
