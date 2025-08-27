# curso-de-Python
desafios do curso
#banco de dados 
usuario_senha ={
    "ana":2598,
    "bia":2314,
    "Dani":4582,
    "ca":6822,
    "paula":6587,
    "fabiana":5895,
    "bruna":7725
}

#perguntar para o usuario

nome = input("Digite o nome do usuario: ")
senha = int(input("Digite a senha: "))

#condição 
if nome in usuario_senha:
    if usuario_senha[nome] == senha:
        print("Login realizado com sucesso.")

    else:
        print("Senha incorreta, tente novamente.")
else:
    print("Usuario não encontrado.")
