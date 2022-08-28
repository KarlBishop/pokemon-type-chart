---
layout: type_chart
permalink: /pogo_old
title: Pokémon Go Type Matchup Chart
description: Shows how damage modifiers are applied when attacking and defending against Pokémon of different types in Pokémon Go
lang: en
pokemon:
  -
    name: "bug"
    damage_from:
      -
        amount: "double"
        types: [ "fire", "flying", "rock" ]
      -
        amount: "half"
        types: [ "fight", "grass", "ground" ]
    damage_to:
      -
        amount: "double"
        types: [ "dark", "grass", "psychic" ]
      -
        amount: "half"
        types: [ "fairy", "fight", "fire", "flying", "ghost", "poison", "steel" ]
  -
    name: "dark"
    damage_from:
      -
        amount: "double"
        types: [ "bug", "fairy", "fight" ]
      -
        amount: "half"
        types: [ "dark", "ghost", "psychic" ]
    damage_to:
      -
        amount: "double"
        types: [ "ghost", "psychic" ]
      -
        amount: "half"
        types: [ "dark", "fairy", "fight" ]
  -
    name: "dragon"
    damage_from:
      -
        amount: "double"
        types: [ "dragon", "ice", "fairy" ]
      -
        amount: "half"
        types: [ "elec", "fire", "grass", "water" ]
    damage_to:
      -
        amount: "double"
        types: [ "dragon" ]
      -
        amount: "half"
        types: [ "fairy", "steel" ]
  -
    name: "elec"
    damage_from:
      -
        amount: "double"
        types: [ "ground" ]
      -
        amount: "half"
        types: [ "elec", "flying", "steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "flying", "water" ]
      -
        amount: "half"
        types: [ "dragon", "elec", "grass", "ground" ]
  -
    name: "fairy"
    damage_from:
      -
        amount: "double"
        types: [ "poison", "steel" ]
      -
        amount: "half"
        types: [ "bug", "dark", "dragon", "fight" ]
    damage_to:
      -
        amount: "double"
        types: [ "dark", "dragon", "fight" ]
      -
        amount: "half"
        types: [ "fire", "poison", "steel" ]
  -
    name: "fight"
    damage_from:
      -
        amount: "double"
        types: [ "fairy", "flying", "psychic" ]
      -
        amount: "half"
        types: [ "bug", "dark", "rock" ]
    damage_to:
      -
        amount: "double"
        types: [ "dark", "ice", "normal", "rock", "steel" ]
      -
        amount: "half"
        types: [ "bug", "fairy", "flying", "ghost", "poison", "psychic" ]
  -
    name: "fire"
    damage_from:
      -
        amount: "double"
        types: [ "ground", "rock", "water" ]
      -
        amount: "half"
        types: [ "bug", "fairy", "fire", "grass", "ice", "steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "bug", "grass", "ice", "steel" ]
      -
        amount: "half"
        types: [ "dragon", "fire", "rock", "water" ]
  -
    name: "flying"
    damage_from:
      -
        amount: "double"
        types: [ "elec", "ice", "rock" ]
      -
        amount: "half"
        types: [ "bug", "fight", "grass", "ground" ]
    damage_to:
      -
        amount: "double"
        types: [ "bug", "fight", "grass" ]
      -
        amount: "half"
        types: [ "elec", "rock", "steel" ]
  -
    name: "ghost"
    damage_from:
      -
        amount: "double"
        types: [ "ghost", "dark" ]
      -
        amount: "half"
        types: [ "bug", "normal", "fight", "poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "ghost", "psychic" ]
      -
        amount: "half"
        types: [ "dark", "normal" ]
  -
    name: "grass"
    damage_from:
      -
        amount: "double"
        types: [ "bug", "fire", "flying", "ice", "poison" ]
      -
        amount: "half"
        types: [ "elec", "grass", "ground", "water" ]
    damage_to:
      -
        amount: "double"
        types: [ "ground", "rock", "water" ]
      -
        amount: "half"
        types: [ "bug", "dragon", "fire", "flying", "grass", "poison", "steel" ]
  -
    name: "ground"
    damage_from:
      -
        amount: "double"
        types: [ "grass", "ice", "water" ]
      -
        amount: "half"
        types: [ "elec", "poison", "rock" ]
    damage_to:
      -
        amount: "double"
        types: [ "elec", "fire", "poison", "rock", "steel" ]
      -
        amount: "half"
        types: [ "bug", "flying", "grass" ]
  -
    name: "ice"
    damage_from:
      -
        amount: "double"
        types: [ "fight", "fire", "rock", "steel" ]
      -
        amount: "half"
        types: [ "ice" ]
    damage_to:
      -
        amount: "double"
        types: [ "dragon", "flying", "grass", "ground" ]
      -
        amount: "half"
        types: [ "fire", "ice", "steel", "water" ]
  -
    name: "normal"
    damage_from:
      -
        amount: "double"
        types: [ "fight" ]
      -
        amount: "half"
        types: [ "ghost" ]
    damage_to:
      -
        amount: "half"
        types: [ "ghost", "rock", "steel" ]
  -
    name: "poison"
    damage_from:
      -
        amount: "double"
        types: [ "ground", "psychic" ]
      -
        amount: "half"
        types: [ "bug", "fairy", "fight", "grass", "poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "grass", "fairy" ]
      -
        amount: "half"
        types: [ "ghost", "ground", "poison", "rock", "steel" ]
  -
    name: "psychic"
    damage_from:
      -
        amount: "double"
        types: [ "bug", "dark", "ghost" ]
      -
        amount: "half"
        types: [ "fight", "psychic" ]
    damage_to:
      -
        amount: "double"
        types: [ "fight", "poison" ]
      -
        amount: "half"
        types: [ "dark", "psychic", "steel" ]
  -
    name: "rock"
    damage_from:
      -
        amount: "double"
        types: [ "fight", "grass", "ground", "steel", "water" ]
      -
        amount: "half"
        types: [ "fire", "flying", "normal", "poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "bug", "fire", "flying", "ice" ]
      -
        amount: "half"
        types: [ "fight", "ground", "steel" ]
  -
    name: "steel"
    damage_from:
      -
        amount: "double"
        types: [ "fight", "fire", "ground" ]
      -
        amount: "half"
        types: [ "bug", "dragon", "fairy", "flying", "grass", "ice", "normal", "poison", "psychic", "rock", "steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "fairy", "ice", "rock" ]
      -
        amount: "half"
        types: [ "elec", "fire", "steel", "water" ]
  -
    name: "water"
    damage_from:
      -
        amount: "double"
        types: [ "elec", "grass" ]
      -
        amount: "half"
        types: [ "fire", "ice", "steel", "water" ]
    damage_to:
      -
        amount: "double"
        types: [ "fire", "ground", "rock" ]
      -
        amount: "half"
        types: [ "dragon", "grass", "water" ]
---
