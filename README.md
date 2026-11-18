# Exercício de polimorfismo em Java

Projeto de console com dois exemplos de polimorfismo em programação orientada a objetos.

## Exemplos

- **Sobrescrita:** `Carro` e `Bicicleta` herdam de `Veiculo` e implementam seu próprio comportamento para `mover()`.
- **Sobrecarga:** `Calculadora` define versões de `somar()` que recebem tipos e quantidades diferentes de parâmetros.

## Tecnologias e conceitos

- Java
- Herança e sobrescrita de métodos
- Sobrecarga de métodos
- Classes abstratas e referências do tipo base

## Como executar

Com um JDK instalado, execute na pasta do repositório pelo PowerShell:

```powershell
New-Item -ItemType Directory -Force out | Out-Null
$sources = Get-ChildItem -Filter *.java | ForEach-Object { $_.FullName }
javac -d out $sources
java -cp out br.edu.fatecpg.polimorfismo.view.Main
```

Este é um exercício de estudo executado no terminal.
