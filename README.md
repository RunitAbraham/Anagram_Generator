# Anagram_Generator # Semantigram
Anagram generator using Anatree algorithm. Additionally a prototype for Hindi Nonward generator.
This repository contains the code and models developed to efficiently generate and manage anagrams using our custom Anatree structure and integrating semantic insights from WordNet and phonetic analysis.

Features
Anatree Algorithm: Implements a custom trie structure to store and search anagrams efficiently.
Semantic Pairing: Utilizes WordNet to find semantic relationships such as synonyms, antonyms, and more, enriching the anagrams with meaningful connections.
Phonetic Analysis: Incorporates phonetic comparisons to group anagrams that sound similar, enhancing the linguistic relevance of the generated anagrams.
Multi-language Support: Initially supports English with potential scaffolding for extending to other languages like Hindi.
Prototype Hindi Nonword Generator
Overview
As part of our efforts to expand the linguistic tools available through Semantigram, we have initiated a prototype Hindi nonword generator. This tool is designed to create linguistically plausible nonwords in Hindi, which can be invaluable for linguistic research, language learning applications, and testing systems where control over input data is required.

Current Development Status
The Hindi nonword generator is currently in a prototype stage. Significant work is ongoing to develop and refine the phonotactic rules that govern the construction of plausible Hindi nonwords. Phonotactic rules define permissible combinations of sounds in Hindi and are critical for ensuring that generated nonwords resemble possible Hindi words without being actual words.

Database Needs
To accurately generate nonwords, a comprehensive database of Hindi phonemes and their allowable combinations is required. We are in the process of building this database, which will serve as a foundational element for the nonword generator. This database will include:

Phonemes: A complete list of Hindi phonemes.
Combination Rules: Rules that dictate which phonemes can logically follow others in Hindi.
Tree Structure
The nonword generator utilizes a Trie (prefix tree) structure to store Hindi words efficiently. This tree structure allows for quick searches and validations, ensuring that generated nonwords do not match any real Hindi words. The Trie structure is ideal for this application due to its:

Efficiency: Fast lookups, insertions, and deletions of word elements.
Space Optimization: Reduces the space needed compared to a naive list or array of words.
Usage
Currently, the prototype can generate nonwords based on simple random selection of phonemes that adhere to basic CV (consonant-vowel) patterns. Users can specify the desired length of nonwords, and the system will generate nonwords that do not exist in the Hindi Trie but follow the tentative phonotactic rules.
Future Development
The next steps include:

Rule Expansion: Further development of sophisticated phonotactic rules.
Database Completion: Completion of the phonemic database with detailed combination rules.
Integration: Full integration of the nonword generator with the broader Semantigram project to support multilingual linguistic tools.
