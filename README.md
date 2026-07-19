# UltraemojiCombat

Jogo de simulacao de luta em Java com resultados aleatorios.

## Descricao

Aplicacao console que modela um torneio de artes marciais ficticio ("Ultra Emoji Combat"). Lutadores sao cadastrados, categorizados por peso e combatem com resultados aleatorios.

## Funcionalidades

- Cadastro de lutadores com atributos (nome, nacionalidade, idade, peso, vitorias, derrotas)
- Categorizacao automatica por peso (Leve, Medio, Pesado)
- Marcacao de lutas entre lutadores da mesma categoria
- Simulacao de luta com resultado aleatorio (empate, vitoria do desafiante, vitoria do campeo)
- Exibicao de estatisticas dos lutadores

## Tecnologias

- **Linguagem:** Java (pura)
- **Dependencias:** java.util.Random
- **IDE:** IntelliJ IDEA

## Como Rodar

```bash
# Compile
javac -d out/production/UltraemojiCombat src/Lutador.java src/Luta.java src/Main.java

# Execute
java -cp out/production/UltraemojiCombat Main
```

Ou abra no IntelliJ IDEA e execute `Main.java`.

## Estrutura

```
src/
├── Main.java      # Ponto de entrada
├── Lutador.java   # Classe lutador
└── Luta.java      # Classe luta
```

## Categorias de Peso

- **Leve:** ate 70.3 kg
- **Medio:** ate 83.9 kg
- **Pesado:** ate 120.2 kg

## Licenca

MIT License - Diego Vieira
