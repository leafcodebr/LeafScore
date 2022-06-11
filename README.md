# 💜 LeafScore

## Dependencia
É necessário o plugin [LeafCore](https://github.com/leafcodebr/LeafCore/releases/tag/Downloads) para o funcionamento.

É necessário o plugin [PlaceholderAPI](https://www.spigotmc.org/resources/placeholderapi.6245/) para o funcionamento.

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
    - "&a&lSCORE"
    - "&f&lBOARD"
    - "&5&lLEAF"
  Linhas:
    - ""
    - "&fCargo: %leaftags_player_maxtag_preset%"
    - "&fTag atual: %leaftags_player_tag_preset%"
    - ""
    - "&fConexão: &a%player_ping%ms"
    - "&fJogadores: &a%server_online%"
    - ""
    - "&7seuservidor.com"
# Block-Mundos: Caso o jogador esteja em algum destes mundos, ele não receberá a scoreboard.
Block-Mundos:
  - "nome_do_mundo"
```

