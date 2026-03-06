# meu-primeiro-projeto: **Código em Python**
--------------------------------------------

comando = "mover", "norte", 140

match comando:
    case "decolar":
        print("Subindo!")
        
  case "pousar":
        print("Descendo!")
        
  case "girar", angulo: 
        print(f"Girando o drone em {angulo} graus.")

  case "mover", direcao, distancia:
        print(f"Indo para o {direcao} por {distancia} metros.")
