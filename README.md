### Jogo-Forca

-Função **desenha_forca()**:<br><br>
 Nesta função contém 7 **ifs()**, que indica o número de chances que o usúario tem. Onde a cada vez que o usuário errar uma letra da palavra secreta,
 ela mostra uma "animação" diferente a cada erro, assim deixando mais interativo.
 
          def desenha_forca(erros):
            print("  _______     ")
            print(" |/      |    ")

            if(erros == 1):
                print (" |      (_)   ")
                print (" |            ")
                print (" |            ")
                print (" |            ")

            if(erros == 2):
                print (" |      (_)   ")
                print (" |      \     ")
                print (" |            ")
                print (" |            ")

            if(erros == 3):
                print (" |      (_)   ")
                print (" |      \|    ")
                print (" |            ")
                print (" |            ")

            if(erros == 4):
                print (" |      (_)   ")
                print (" |      \|/   ")
                print (" |            ")
                print (" |            ")

            if(erros == 5):
                print (" |      (_)   ")
                print (" |      \|/   ")
                print (" |       |    ")
                print (" |            ")

            if(erros == 6):
                print (" |      (_)   ")
                print (" |      \|/   ")
                print (" |       |    ")
                print (" |      /     ")

            if (erros == 7):
                print (" |      (_)   ")
                print (" |      \|/   ")
                print (" |       |    ")
                print (" |      / \   ")

            print(" |            ")
            print("_|___         ")
            print()

- Função **imprime_mensagem_vencedor():**<br><br>
Já está função seria quando o usuário dentro das 7 chances da **desenha_forca()**  ele acertar todas as letras ele entra nesta condição.


      def imprime_mensagem_vencedor():
        print("Parabéns, você ganhou!")
        print("       ___________      ")
        print("      '._==_==_=_.'     ")
        print("      .-\\:      /-.    ")
        print("     | (|:.     |) |    ")
        print("      '-|:.     |-'     ")
        print("        \\::.    /      ")
        print("         '::. .'        ")
        print("           ) (          ")
        print("         _.' '._        ")
        print("        '-------'       ")


- Função **imprime_mensagem_perdedor(palavra_secreta):**<br><br>
Como na fução anterior, essa aqui acaba tendo um comportamento parecido, só que quando você acaba errando as 7 tentativas essa função é executada, mostrando uma mensagens e uma "animação".


      def imprime_mensagem_perdedor(palavra_secreta):
        print("Puxa, você foi enforcado!")
        print("A palavra era {}".format(palavra_secreta))
        print("    _______________         ")
        print("   /               \       ")
        print("  /                 \      ")
        print("//                   \/\  ")
        print("\|   XXXX     XXXX   | /   ")
        print(" |   XXXX     XXXX   |/     ")
        print(" |   XXX       XXX   |      ")
        print(" |                   |      ")
        print(" \__      XXX      __/     ")
        print("   |\     XXX     /|       ")
        print("   | |           | |        ")
        print("   | I I I I I I I |        ")
        print("   |  I I I I I I  |        ")
        print("   \_             _/       ")
        print("     \_         _/         ")
        print("       \_______/           ")

