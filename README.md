# AbMapper
A simple python program to extract [abbreviation:full names] pairs from a list to text snippets.

# Mapper
A java version of to extract all [abbreviation:full names] pairs from a text input. the algorithm is based on the paper "A Simple Algorithm for Identifying Abbreviation Definitions in Biomedical Text" by A.S. Schwartz, M.A. Hearst
How to use? just copy the Mapper.java to your project and call the function with "Mapper.mapper(input_text)", the output would be a LinkedHashMap with key as the abbreviation and value as the corresponding full name.
