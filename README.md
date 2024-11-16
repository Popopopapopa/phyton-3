class generator:
    def __init__(self, n):
        self.n = n 

    def __iter__(self):
        for i in range(1, self.n + 1):
            yield (x for x in range(i))

iterable = generator(5)

for generator in iterable:
    print(list(generator))







    
