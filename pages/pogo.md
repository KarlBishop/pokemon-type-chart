---
layout: type_chart
permalink: /pogo
title: Pokémon Go Type Matchup Chart
description: Shows how damage modifiers are applied when attacking and defending against Pokémon of different types in Pokémon Go
pokemon:
  -
    name: "Bug"
    damage_from:
      -
        amount: "double"
        types: [ "Fire", "Flying", "Rock" ]
      -
        amount: "half"
        types: [ "Fight", "Grass", "Ground" ]
    damage_to:
      -
        amount: "double"
        types: [ "Dark", "Grass", "Psychic" ]
      -
        amount: "half"
        types: [ "Fairy", "Fight", "Fire", "Flying", "Ghost", "Poison", "Steel" ]
  -
    name: "Dark"
    damage_from:
      -
        amount: "double"
        types: [ "Bug", "Fairy", "Fight" ]
      -
        amount: "half"
        types: [ "Dark", "Ghost", "Psychic" ]
    damage_to:
      -
        amount: "double"
        types: [ "Ghost", "Psychic" ]
      -
        amount: "half"
        types: [ "Dark", "Fairy", "Fight" ]
  -
    name: "Dragon"
    damage_from:
      -
        amount: "double"
        types: [ "Dragon", "Ice", "Fairy" ]
      -
        amount: "half"
        types: [ "Elec", "Fire", "Grass", "Water" ]
    damage_to:
      -
        amount: "double"
        types: [ "Dragon" ]
      -
        amount: "half"
        types: [ "Fairy", "Steel" ]
  -
    name: "Elec"
    damage_from:
      -
        amount: "double"
        types: [ "Ground" ]
      -
        amount: "half"
        types: [ "Elec", "Flying", "Steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "Flying", "Water" ]
      -
        amount: "half"
        types: [ "Dragon", "Elec", "Grass", "Ground" ]
  -
    name: "Fairy"
    damage_from:
      -
        amount: "double"
        types: [ "Poison", "Steel" ]
      -
        amount: "half"
        types: [ "Bug", "Dark", "Dragon", "Fight" ]
    damage_to:
      -
        amount: "double"
        types: [ "Dark", "Dragon", "Fight" ]
      -
        amount: "half"
        types: [ "Fire", "Poison", "Steel" ]
  -
    name: "Fight"
    damage_from:
      -
        amount: "double"
        types: [ "Fairy", "Flying", "Psychic" ]
      -
        amount: "half"
        types: [ "Bug", "Dark", "Rock" ]
    damage_to:
      -
        amount: "double"
        types: [ "Dark", "Ice", "Normal", "Rock", "Steel" ]
      -
        amount: "half"
        types: [ "Bug", "Fairy", "Flying", "Ghost", "Poison", "Psychic" ]
  -
    name: "Fire"
    damage_from:
      -
        amount: "double"
        types: [ "Ground", "Rock", "Water" ]
      -
        amount: "half"
        types: [ "Bug", "Fairy", "Fire", "Grass", "Ice", "Steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "Bug", "Grass", "Ice", "Steel" ]
      -
        amount: "half"
        types: [ "Dragon", "Fire", "Rock", "Water" ]
  -
    name: "Flying"
    damage_from:
      -
        amount: "double"
        types: [ "Elec", "Ice", "Rock" ]
      -
        amount: "half"
        types: [ "Bug", "Fight", "Grass", "Ground" ]
    damage_to:
      -
        amount: "double"
        types: [ "Bug", "Fight", "Grass" ]
      -
        amount: "half"
        types: [ "Elec", "Rock", "Steel" ]
  -
    name: "Ghost"
    damage_from:
      -
        amount: "double"
        types: [ "Ghost", "Dark" ]
      -
        amount: "half"
        types: [ "Bug", "Normal", "Fight", "Poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "Ghost", "Psychic" ]
      -
        amount: "half"
        types: [ "Dark", "Normal" ]
  -
    name: "Grass"
    damage_from:
      -
        amount: "double"
        types: [ "Bug", "Fire", "Flying", "Ice", "Poison" ]
      -
        amount: "half"
        types: [ "Elec", "Grass", "Ground", "Water" ]
    damage_to:
      -
        amount: "double"
        types: [ "Ground", "Rock", "Water" ]
      -
        amount: "half"
        types: [ "Bug", "Dragon", "Fire", "Flying", "Grass", "Poison", "Steel" ]
  -
    name: "Ground"
    damage_from:
      -
        amount: "double"
        types: [ "Grass", "Ice", "Water" ]
      -
        amount: "half"
        types: [ "Elec", "Poison", "Rock" ]
    damage_to:
      -
        amount: "double"
        types: [ "Elec", "Fire", "Poison", "Rock", "Steel" ]
      -
        amount: "half"
        types: [ "Bug", "Flying", "Grass" ]
  -
    name: "Ice"
    damage_from:
      -
        amount: "double"
        types: [ "Fight", "Fire", "Rock", "Steel" ]
      -
        amount: "half"
        types: [ "Ice" ]
    damage_to:
      -
        amount: "double"
        types: [ "Dragon", "Flying", "Grass", "Ground" ]
      -
        amount: "half"
        types: [ "Fire", "Ice", "Steel", "Water" ]
  -
    name: "Normal"
    damage_from:
      -
        amount: "double"
        types: [ "Fight" ]
      -
        amount: "half"
        types: [ "Ghost" ]
    damage_to:
      -
        amount: "half"
        types: [ "Ghost", "Rock", "Steel" ]
  -
    name: "Poison"
    damage_from:
      -
        amount: "double"
        types: [ "Ground", "Psychic" ]
      -
        amount: "half"
        types: [ "Bug", "Fairy", "Fight", "Grass", "Poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "Grass", "Fairy" ]
      -
        amount: "half"
        types: [ "Ghost", "Ground", "Poison", "Rock", "Steel" ]
  -
    name: "Psychic"
    damage_from:
      -
        amount: "double"
        types: [ "Bug", "Dark", "Ghost" ]
      -
        amount: "half"
        types: [ "Fight", "Psychic" ]
    damage_to:
      -
        amount: "double"
        types: [ "Fight", "Poison" ]
      -
        amount: "half"
        types: [ "Dark", "Psychic", "Steel" ]
  -
    name: "Rock"
    damage_from:
      -
        amount: "double"
        types: [ "Fight", "Grass", "Ground", "Steel", "Water" ]
      -
        amount: "half"
        types: [ "Fire", "Flying", "Normal", "Poison" ]
    damage_to:
      -
        amount: "double"
        types: [ "Bug", "Fire", "Flying", "Ice" ]
      -
        amount: "half"
        types: [ "Fight", "Ground", "Steel" ]
  -
    name: "Steel"
    damage_from:
      -
        amount: "double"
        types: [ "Fight", "Fire", "Ground" ]
      -
        amount: "half"
        types: [ "Bug", "Dragon", "Fairy", "Flying", "Grass", "Ice", "Normal", "Poison", "Psychic", "Rock", "Steel" ]
    damage_to:
      -
        amount: "double"
        types: [ "Fairy", "Ice", "Rock" ]
      -
        amount: "half"
        types: [ "Elec", "Fire", "Steel", "Water" ]
  -
    name: "Water"
    damage_from:
      -
        amount: "double"
        types: [ "Elec", "Grass" ]
      -
        amount: "half"
        types: [ "Fire", "Ice", "Steel", "Water" ]
    damage_to:
      -
        amount: "double"
        types: [ "Fire", "Ground", "Rock" ]
      -
        amount: "half"
        types: [ "Dragon", "Grass", "Water" ]
---
