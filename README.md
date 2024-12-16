# Comparative-Blabber

Project for NLP course; Aim of it is to compare the performance of 3 distinct models in one task.

## Overview

I chose to select Machine translation. As learning languages is one of my favourite activities to do; thus it would be a nice way to meddle with how a computer does translation for us.

## Data

All data is loaded from [Hugging Face](https://huggingface.co/).

Chosen data:

- [opus-French-to-English](https://huggingface.co/datasets/kaitchup/opus-French-to-English)
- [opus-Italian-to-English](https://huggingface.co/datasets/kaitchup/opus-Italian-to-English)

All credit goes to author. Only changes to be made shall be file name for easier loading, and/or saving preprocessed data for later use in different models.

## Steps

The following is an abstract view for what steps will be followed.

### Data Loading

First time working with `.parquet` files, so it should be an experience to learn how to use such files; luckily [Polars](https://pola.rs/) offers a way to handle them.

### _More to follow_
