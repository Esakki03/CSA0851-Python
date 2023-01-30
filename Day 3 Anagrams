def anagram(li):
    dictionary={}
    for word in li:
        sortedword=''.join(sorted(word))
        print(sortedword)
        if sortedword not in dictionary:
            dictionary[sortedword]=[word]
        else:
           dictionary[sortedword]+=[word]
        return[dictionary[i] for i in dictionary]
li=['pop','bat','tab','opp']
print(anagrame(li))
