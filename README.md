# Data Scientist

This project is part of The Hacking Project curriculum.

## Description

This project focuses on manipulating arrays and hashes in Ruby.

It contains two Ruby programs:

- **00_journalists.rb**: analyzes a list of Twitter journalist handles.
- **01_cryptocurrencies.rb**: analyzes cryptocurrency data by creating and manipulating a hash.

## Project Structure

```
manipuler_donnee/
├── lib/
│   ├── 00_journalists.rb
│   └── 01_cryptocurrencies.rb
└── README.md
```

## Features

### Journalists

- Count the total number of Twitter handles.
- Find the shortest handle.
- Count handles with exactly 5 characters (excluding `@`).
- Count handles starting with an uppercase letter.
- Sort handles alphabetically.
- Sort handles by length.
- Find the position of `@epenser`.
- Display the distribution of handle lengths.

### Cryptocurrencies

- Create a hash from two arrays (currency names and prices).
- Find the cryptocurrency with the highest value.
- Find the cryptocurrency with the lowest value.
- Display all cryptocurrencies worth less than $6000.
- Find the most expensive cryptocurrency under $6000.

## How to Run

Run the following commands from the project root:

```bash
ruby lib/00_journalists.rb
ruby lib/01_cryptocurrencies.rb
```

## Language

- Ruby
