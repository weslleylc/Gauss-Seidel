# Gauss-Seidel
Método de Gaus  Seidel para resolução de sistemas lineares

# Funções:
gauss_seidel(n, A, b, p, maxI)

Tamanho da matriz nxn.
Matriz de equações A.
Matriz resposta B.
Precisão para parada p.
Máximo de iterações maxI.

# Exemplo de uso.
Entrada: 
A = [ [6.0, 0.0, -3.0, 0.0, 0.0],
      [3.0, -3.0, 0.0, 0.0, 0.0],
      [0.0, -1.0, 9.0, 0.0, 0.0],
      [0.0, 1.0, 8.0, -11.0, 2.0],
      [3.0, 1.0, 0.0, 0.0, -4.0]
     ]
b = [50.0, 0.0, 160.0, 0.0, 0.0]

Chamada da função:
gauss_seidel(5, A, b, 0.001, 500)
