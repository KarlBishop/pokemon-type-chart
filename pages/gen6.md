---
layout: type_chart
permalink: /gen6
title: Pokémon Gen 6 Type Matchup Chart
description: Shows how damage modifiers are applied when attacking and defending against Pokémon of different types in Pokémon Generation 6 games
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
        types: [ "Dark", "Ghost" ]
      -
        amount: "none"
        types: [ "Psychic" ]
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
        types: [ "Steel" ]
      -
        amount: "none"
        types: [ "Fairy" ]
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
        types: [ "Dragon", "Elec", "Grass" ]
      -
        amount: "none"
        types: [ "Ground" ]
  -
    name: "Fairy"
    damage_from:
      -
        amount: "double"
        types: [ "Poison", "Steel" ]
      -
        amount: "half"
        types: [ "Bug", "Dark", "Fight" ]
      -
        amount: "none"
        types: [ "Dragon" ]
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
        types: [ "Bug", "Fairy", "Flying", "Poison", "Psychic" ]
      -
        amount: "none"
        types: [ "Ghost" ]
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
        types: [ "Bug", "Fight", "Grass" ]
      -
        amount: "none"
        types: [ "Ground" ]
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
        types: [ "Bug", "Poison" ]
      -
        amount: "none"
        types: [ "Normal", "Fight" ]
    damage_to:
      -
        amount: "double"
        types: [ "Ghost", "Psychic" ]
      -
        amount: "half"
        types: [ "Dark" ]
      -
        amount: "none"
        types: [ "Normal" ]
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
        types: [ "Poison", "Rock" ]
      -
        amount: "none"
        types: [ "Elec" ]
    damage_to:
      -
        amount: "double"
        types: [ "Elec", "Fire", "Poison", "Rock", "Steel" ]
      -
        amount: "half"
        types: [ "Bug", "Grass" ]
      -
        amount: "none"
        types: [ "Flying" ]
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
        amount: "none"
        types: [ "Ghost" ]
    damage_to:
      -
        amount: "half"
        types: [ "Rock", "Steel" ]
      -
        amount: "none"
        types: [ "Ghost" ]
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
        types: [ "Ghost", "Ground", "Poison", "Rock" ]
      -
        amount: "none"
        types: [ "Steel" ]
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
        types: [ "Psychic", "Steel" ]
      -
        amount: "none"
        types: [ "Dark" ]
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
        types: [ "Bug", "Dragon", "Fairy", "Flying", "Grass", "Ice", "Normal", "Psychic", "Rock", "Steel" ]
      -
        amount: "none"
        types: [ "Poison" ]
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
