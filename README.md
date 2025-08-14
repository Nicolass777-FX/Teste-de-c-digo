# Teste-de-c-digo
Testando códigos
cargo = input("Digite o cargo do funcionário (gerente, analista, estagiário): ")
dia = input("Digite o dia da semana: ")
dias_uteis = ["segunda-feira", "terça-feira", "quarta-feira", "quinta-feira", "sexta-feira"]


acesso = False

if cargo == "gerente":
  acesso = True
elif cargo == "analista" and dia in dias_uteis:
  acesso = True
elif cargo == "estagiário" and dia in dias_uteis:
  acesso = True


if acesso:
  print("Acesso permitido ao escritório.")
else:
  print("Acesso negado ao escritório.")

Esse código é dos bons.

:)
