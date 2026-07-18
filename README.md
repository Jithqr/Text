'''
A tuple is a sequence of immutable Python objects which
means that the tuples cannot be changed unlike lists.
Tuples use parentheses to enclose items.
'''

tuple1 = ('samsung', 15000, 'micromax', 12000, 'lava', 10000, 'intex', 9000)
tuple2 = (1, 2, 3, 4, 5, 6, 7, 8, 9, 10)

print('First item of tuple1:', tuple1[0])
print('First 5 items of tuple2:', tuple2[0:5])
print('Second last item of tuple1:', tuple1[-2])
# using colon between indeces is called Slicing
print('Third to sixth items of tuple2:', tuple2[2:6])
print('Tuple addition:', tuple1 + tuple2)
print('Tuple multiplication:', tuple2 * 3)

# using membership operator with tuples
item = 'micromax'
if item in tuple1:
    print('tuple1 contains', item)
else:
    print('tuple1 doesn\'t contain', item)
