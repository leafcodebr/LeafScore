# 💜 LeafScore

## Dependencia
É necessário o plugin [LeafCore](https://github.com/leafcodebr/LeafCore/releases/tag/Downloads) para o funcionamento.

## Configuração
```yml
# Titulo_update: Tempo em (meio_segundo, segundo ou minutos) para que o titulo atualize para o próximo da lista (ANIMAÇÃO).
Titulo_update: 1
# Update_type: Tipo de tempo que será usado para o delay em 'Titulo_update'
# Disponíveis: MEIO_SEGUNDO, SEGUNDOS, MINUTOS
Update_type: MEIO_SEGUNDO
Scoreboard:
  # Titulo: Caso haja mais de um nesta lista, fará um titulo animado.
  Titulo:
    - "&f&lLEAF"
    - "&5&lL&f&lEAF"
    - "&5&lLE&f&lAF"
    - "&5&lLEA&f&lF"
    - "&5&lLEAF"
    - "&f&lLEAF"
    - "&5&lLEAF"
    - "&f&lCODE"
    - "&5&lCODE"
    - "&f&lCODE"
  Linhas:
    - ""
    - "&fCargo: %leaftags_player_maxtag_preset%"
    - ""
    - "&fMoedas: &60"
    - "&fJogadores: &a%bungee_total%"
    - ""
    - "&7redeserver.com"
# Block-Mundos: Caso o jogador esteja em algum destes mundos, ele não receberá a scoreboard.
Block-Mundos:
  - "nome_do_mundo"
```

