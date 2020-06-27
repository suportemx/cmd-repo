# cmd-repo
página html para armazenar comandos e buscar facilmente, geralmente usado para CTFs e Pentest.

## para adicionar comando

copie um bloco de código da tag tr
  
```sh
  <tr onclick="copyCommand('nmp1')">
    <td></td>
    <td>nmap</td>
    <td id="nmp1">nmap -v X.X.X.X</td>
    <td>esse comando e apenas um exemplo</td>
  </tr>
```

lembrando que o valor da função copyCommand deverá ser o mesmo do id da tag td

```sh
  <tr onclick="copyCommand('nmp2')">
    <td></td>
    <td>nmap</td>
    <td id="nmp2">nmap -Pn X.X.X.X</td>
    <td>esse comando e apenas um outro exemplo</td>
  </tr>
```

o id deverá ser único para cada comando


