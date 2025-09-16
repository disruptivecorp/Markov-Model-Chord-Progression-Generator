# Markhords: Markov-Model-Chord-Progression-Generator
Markov Chains Chord Progression Generator Trained on Real Songs

## Overview
Markhords is a Python project that uses **Markov chains** to generate chord progressions trained on real-world music.  
By learning transition probabilities from a large dataset of chord progressions, it provides musicians with **random but stylistically grounded sequences** that serve as creative starting points.

## Background & Motivation
While datasets like **Chordonomicon (Kantarelis et al., 2024)** exist, they mainly support predictive tasks (e.g., hidden Markov models or GPT-based generation).  
However, those approaches often depend on absolute key rather than normalized **roman numeral progressions**. Markhords fills this gap by:
- Normalizing chord transitions into roman numerals.  
- Preserving **relative movement** instead of key-specific patterns.  
- Generating **randomized progressions** that feel musical but are not tied to any single song.

This is especially useful for songwriting, where musicians may want inspiration without directly imitating existing tracks.

## Objectives
1. Train a Markov chain using the **Chordonomicon** dataset (666k songs, spanning 1890s–2020s).  
2. Provide utilities for generating random progressions in different keys.  
3. Allow stylistic exploration across genres while avoiding “spoiler” influence from known songs.

## Features
- Roman numeral–based chord normalization.  
- Random but musically coherent chord progression generation.  
- Configurable for **genre-specific seeds** or broader exploration.  
