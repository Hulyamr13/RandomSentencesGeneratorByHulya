# Random Sentence Generator


Project Goals
The goal of this project is to create a simple program that generates random sentences using pre-defined lists of words. This can be used for various purposes, such as generating writing prompts or testing natural language processing algorithms.

Solution

The solution uses Python programming language to write a script that generates random sentences.
The script defines a function called get_random_word that accepts a list of words as a parameter, and uses the random.choice method from the random library to randomly select and return a word from the list.
The script defines several lists of words, including names, places, verbs, nouns, adverbs, and details, which will be used to generate random sentences.
The script uses an infinite while loop to continuously generate new random sentences.
Within the loop, the script calls the get_random_word function for each of the word lists to randomly select a name, place, verb, noun, adverb, and detail for the sentence.
Finally, the script prints out the generated sentence and prompts the user to press Enter to generate another sentence.
