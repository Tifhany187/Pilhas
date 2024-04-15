# Pilhas
#Aula 06- pilhas
class Stack:
    def __init__(self):
        self.stack = []

    def push(self, objeto):
        self.stack.append(objeto)

    def pop(self):
        return self.stack.pop() if self.stack else None

    def is_empty(self):
        return not self.stack

def reverse_string(o):
    stack = Stack()
    
    [stack.push(char) for char in o]

    
    return ''.join(stack.pop() for _ in range(len(stack.stack)))


if __name__ == "__main__":
    strings = ["Tifhany Dias", "438118", "Eu sei dançar na chuva", "Teste 321"]
    for string in strings:
        print("A lista dos objetos origináis é: ", string)
        print("A lista dos objetos reversos é: ", reverse_string(string))
        print ()
