#RECEITAS MJE

        self.nome = nome
        self.ingredientes = ingredientes
        self.passos = passos
    
    def exibir_receita(self):
        print("Receita de", self.nome)
        print("Ingredientes:")
        for ingrediente in self.ingredientes:
            print("-", ingrediente)
        print("Passos:")
        for i, passo in enumerate(self.passos, 1):
            print(i, ".", passo)
        print("\n")
