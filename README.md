# Desafio_de_codigo
Projeto desafio de godigo

# Lê os dados de entrada
entrada = input().split()

preco = float(entrada[0])
codigo = entrada[1]

# Verifica se está em promoção
if codigo == "S":
    preco_final = preco * 0.9  # aplica 10% de desconto
else:
    preco_final = preco

# Exibe o resultado com duas casas decimais
print(f"{preco_final:.2f}")

