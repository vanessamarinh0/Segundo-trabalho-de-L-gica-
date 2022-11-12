listnome = []
listemail = []
listcpf = []
listcelular = []
listsexo = []
listsenha = []
regis = []
i = 0
u = 1
x = 1
y = 1
nome = "NÃO CADASTRADO"
cpf = "NÃO CADASTRADO"
celular = "NÃO CADASTRADO"
sexo = "NÂO CADASTRADO"
email = "NÃO CADASTRADO"
senha = "NÃO CADASTRADO"
print ("="*35,"MENU PRINCIPAL","="*35)
while i != 5:
    print ("1 - Cadastrar")
    print ("2 - Ler")
    print ("3 - Deletar")
    print ("4 - Atualizar")
    print ("5 - Sair")
    print ("-"*85)
    i = int (input("SUA OPÇÃO: "))
    print ("-"*85)
    if i == 1:
        print (" "*25, "ATENÇÃO, MÁXIMO DE 5 CADASTROS"," "*20)
        print ("-"*85)
        registros = int (input("DIGITE QUANTOS REGISTROS DESEJA CADASTRAR: "))
        print ("-"*85)
        if registros > 5:
            print ("NÚMERO DE REGISTROS ULTRAPASSA O LIMITE MÁXIMO, TENTE NOVAMENTE")
            print ("="*85)
        else:
            regis.append(registros)
            d = sum(regis)
            for a in range (registros):
                print ("CADASTRO Nº %d "%x)
                x=x+1
                if x+1 > 6:
                    x = 0
                    x = x+1
                nome = input ("Nome: ")
                listnome.append (nome)
                cpf = input ("CPF: ")
                listcpf.append (cpf)
                celular = input ("Celular: ")
                listcelular.append (celular)
                sexo = input ("Sexo: ")
                listsexo.append (sexo)
                email = input ("Email: ")
                listemail.append (email)
                senha = input ("Senha: ")
                listsenha.append (senha)
                print ("-"*85)
                print ("VOCÊ REALMENTE DESEJA CADASTRAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                op = int (input ("SUA OPÇÃO: "))
                if op == 1:
                    print ("="*85)
                    print ("CADASTRO CONCLUIDO COM SUCESSO")
                    print ("="*85)
                elif op == 2:
                    for a in range (registros):
                        nome = input ("Nome: ")
                        listnome.append (nome)
                        cpf = input ("CPF: ")
                        listcpf.append (cpf)
                        celular = input ("Celular: ")
                        listcelular.append (celular)
                        sexo = input ("Sexo: ")
                        listsexo.append (sexo)
                        email = input ("Email: ")
                        listemail.append (email)
                        senha = input ("Senha: ")
                        listsenha.append (senha)
                        print ("-"*85)
                        print ("VOCÊ REALMENTE DESEJA CADASTRAR ESSES DADOS?")
                        print ("1 - Sim")
                        print ("2 - Não")
                        op = int (input ("SUA OPÇÃO: "))
                        if op == 1:
                            print ("="*85)
                            print ("CADASTRO CONCLUIDO COM SUCESSO")
                            print ("="*85)
                        else:
                            print ("OPÇÃO INVÁLIDA")
                            print ("="*85)
                else:
                    print ("OPÇÃO INVÁLIDA")
                    print ("="*85)
    elif i == 2:
        d = sum (regis)
        if d > 0:
            print ("1 - [CADASTRO 1]")
            print ("2 - [CADASTRO 2]")
            print ("3 - [CADASTRO 3]")
            print ("4 - [CADASTRO 4]")
            print ("5 - [CADASTRO 5]")
            print ("6 - [TODOS OS CADASTROS]")
            p = int (input("QUAL CADASTRO DESEJA VISUALIZAR OS DADOS? "))
            print ("="*85)
            if p == 1:
                print ("NOME: ", listnome[0])
                print ("CPF: ", listcpf[0])
                print ("CELULAR: " ,listcelular[0])
                print ("SEXO: ", listsexo[0])
                print ("EMAIL: ", listemail[0])
                print ("SENHA: ", listsenha[0])
                print ("="*85)
            elif p == 2:
                print ("NOME: ", listnome[1])
                print ("CPF: ", listcpf[1])
                print ("CELULAR: " ,listcelular[1])
                print ("SEXO: ", listsexo[1])
                print ("EMAIL: ", listemail[1])
                print ("SENHA: ", listsenha[1])
                print ("="*85)
            elif p == 3:
                print ("NOME: ", listnome[2])
                print ("CPF: ", listcpf[2])
                print ("CELULAR: " ,listcelular[2])
                print ("SEXO: ", listsexo[2])
                print ("EMAIL: ", listemail[2])
                print ("SENHA: ", listsenha[2])
                print ("="*85)
            elif p == 4:
                print ("NOME: ", listnome[3])
                print ("CPF: ", listcpf[3])
                print ("CELULAR: " ,listcelular[3])
                print ("SEXO: ", listsexo[3])
                print ("EMAIL: ", listemail[3])
                print ("SENHA: ", listsenha[3])
                print ("="*85)
            elif p == 5:
                print ("NOME: ", listnome[4])
                print ("CPF: ", listcpf[4])
                print ("CELULAR: " ,listcelular[4])
                print ("SEXO: ", listsexo[4])
                print ("EMAIL: ", listemail[4])
                print ("SENHA: ", listsenha[4])
                print ("="*85)
            elif p == 6:
                print ("[CADASTRO - 1]")
            print ("NOME: ", listnome[0])
            print ("CPF: ", listcpf[0])
            print ("CELULAR: " ,listcelular[0])
            print ("SEXO: ", listsexo[0])
            print ("EMAIL: ", listemail[0])
            print ("SENHA: ", listsenha[0])
            print ("-"*85)
            print ("[CADASTRO - 2]")
            if registros < 2:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[1])
                print ("CPF: ", listcpf[1])
                print ("CELULAR: " ,listcelular[1])
                print ("SEXO: ", listsexo[1])
                print ("EMAIL: ", listemail[1])
                print ("SENHA: ", listsenha[1])
                print ("-"*85)
            if registros < 3:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("[CADASTRO - 3]")
                print ("NOME: ", listnome[2])
                print ("CPF: ", listcpf[2])
                print ("CELULAR: " ,listcelular[2])
                print ("SEXO: ", listsexo[2])
                print ("EMAIL: ", listemail[2])
                print ("SENHA: ", listsenha[2])
                print ("-"*85)
            print ("[CADASTRO - 4]")
            if registros < 4:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[3])
                print ("CPF: ", listcpf[3])
                print ("CELULAR: " ,listcelular[3])
                print ("SEXO: ", listsexo[3])
                print ("EMAIL: ", listemail[3])
                print ("SENHA: ", listsenha[3])
                print ("-"*85)
            print ("[CADASTRO - 5]")
            if registros < 5:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[4])
                print ("CPF: ", listcpf[4])
                print ("CELULAR: " ,listcelular[4])
                print ("SEXO: ", listsexo[4])
                print ("EMAIL: ", listemail[4])
                print ("SENHA: ", listsenha[4])
                print ("-"*85)
        else:
            print ("="*85)
            print ("NÃO HÁ CADASTRO(S) REGISTRADOS, VÁ PARA O MENU (CADASTRAR) PARA REGISTRAR UM OU MAIS CADASTRADOS")
            print ("="*85)
    elif i == 3:
        if nome != "NÃO CADASTRADO" and cpf != "NÃO CADASTRADO" and celular != "NÃO CADASTRADO" and sexo != "NÃO CADASTRADO" and email != "NÃO CADASTRADO" and senha:
            print ("DADOS ATUAIS")
            print ("-"*85)
            print ("[CADASTRO - 1]")
            print ("NOME: ", listnome[0])
            print ("CPF: ", listcpf[0])
            print ("CELULAR: " ,listcelular[0])
            print ("SEXO: ", listsexo[0])
            print ("EMAIL: ", listemail[0])
            print ("SENHA: ", listsenha[0])
            print ("-"*85)
            print ("[CADASTRO - 2]")
            if registros < 2:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[1])
                print ("CPF: ", listcpf[1])
                print ("CELULAR: " ,listcelular[1])
                print ("SEXO: ", listsexo[1])
                print ("EMAIL: ", listemail[1])
                print ("SENHA: ", listsenha[1])
                print ("-"*85)
            if registros < 3:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("[CADASTRO - 3]")
                print ("NOME: ", listnome[2])
                print ("CPF: ", listcpf[2])
                print ("CELULAR: " ,listcelular[2])
                print ("SEXO: ", listsexo[2])
                print ("EMAIL: ", listemail[2])
                print ("SENHA: ", listsenha[2])
                print ("-"*85)
            print ("[CADASTRO - 4]")
            if registros < 4:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[3])
                print ("CPF: ", listcpf[3])
                print ("CELULAR: " ,listcelular[3])
                print ("SEXO: ", listsexo[3])
                print ("EMAIL: ", listemail[3])
                print ("SENHA: ", listsenha[3])
                print ("-"*85)
            print ("[CADASTRO - 5]")
            if registros < 5:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[4])
                print ("CPF: ", listcpf[4])
                print ("CELULAR: " ,listcelular[4])
                print ("SEXO: ", listsexo[4])
                print ("EMAIL: ", listemail[4])
                print ("SENHA: ", listsenha[4])
                print ("-"*85)
            print ("QUAL DOS CADASTROS VISTOS ACIMA, DESEJA EXCLUIR?")
            print ("1 - [CADASTRO 1]")
            print ("2 - [CADASTRO 2]")
            print ("3 - [CADASTRO 3]")
            print ("4 - [CADASTRO 4]")
            print ("5 - [CADASTRO 5]")
            print ("6 - TODOS OS CADASTROS")
            op = int (input("OPÇÃO: "))
            print ("-"*85)
            if op == 1:
                listnome [0] = "NÃO CADASTRADO"
                listcpf [0] = "NÃO CADASTRADO"
                listcelular [0] = "NÃO CADASTRADO"
                listsexo [0] = "NÃO CADASTRADO"
                listemail [0] = "NÃO CADASTRADO"
                listsenha [0] = "NÃO CADASTRADO"
            elif op ==2:
                listnome [1] = "NÃO CADASTRADO"
                listcpf [1] = "NÃO CADASTRADO"
                listcelular [1] = "NÃO CADASTRADO"
                listsexo [1] = "NÃO CADASTRADO"
                listemail [1] = "NÃO CADASTRADO"
                listsenha [1] = "NÃO CADASTRADO"
            elif op == 3:
                listnome [2] = "NÃO CADASTRADO"
                listcpf [2] = "NÃO CADASTRADO"
                listcelular [2] = "NÃO CADASTRADO"
                listsexo [2] = "NÃO CADASTRADO"
                listemail [2] = "NÃO CADASTRADO"
                listsenha [2] = "NÃO CADASTRADO"
            elif op == 4:
                listnome [3] = "NÃO CADASTRADO"
                listcpf [3] = "NÃO CADASTRADO"
                listcelular [3] = "NÃO CADASTRADO"
                listsexo [3] = "NÃO CADASTRADO"
                listemail [3] = "NÃO CADASTRADO"
                listsenha [3] = "NÃO CADASTRADO"
            elif op == 5:
                listnome [4] = "NÃO CADASTRADO"
                listcpf [4] = "NÃO CADASTRADO"
                listcelular [4] = "NÃO CADASTRADO"
                listsexo [4] = "NÃO CADASTRADO"
                listemail [4] = "NÃO CADASTRADO"
                listsenha [4] = "NÃO CADASTRADO"
            elif op == 6:
                listnome [0] = "NÃO CADASTRADO"
                listcpf [0] = "NÃO CADASTRADO"
                listcelular [0] = "NÃO CADASTRADO"
                listsexo [0] = "NÃO CADASTRADO"
                listemail [0] = "NÃO CADASTRADO"
                listsenha [0] = "NÃO CADASTRADO"
                listnome [1] = "NÃO CADASTRADO"
                listcpf [1] = "NÃO CADASTRADO"
                listcelular [1] = "NÃO CADASTRADO"
                listsexo [1] = "NÃO CADASTRADO"
                listemail [1] = "NÃO CADASTRADO"
                listsenha [1] = "NÃO CADASTRADO"
                listnome [2] = "NÃO CADASTRADO"
                listcpf [2] = "NÃO CADASTRADO"
                listcelular [2] = "NÃO CADASTRADO"
                listsexo [2] = "NÃO CADASTRADO"
                listemail [2] = "NÃO CADASTRADO"
                listsenha [2] = "NÃO CADASTRADO"
                listnome [3] = "NÃO CADASTRADO"
                listcpf [3] = "NÃO CADASTRADO"
                listcelular [3] = "NÃO CADASTRADO"
                listsexo [3] = "NÃO CADASTRADO"
                listemail [3] = "NÃO CADASTRADO"
                listsenha [3] = "NÃO CADASTRADO"
                listnome [4] = "NÃO CADASTRADO"
                listcpf [4] = "NÃO CADASTRADO"
                listcelular [4] = "NÃO CADASTRADO"
                listsexo [4] = "NÃO CADASTRADO"
                listemail [4] = "NÃO CADASTRADO"
                listsenha [4] = "NÃO CADASTRADO"
            print ("="*85)
        else:
            print ("NÃO HÁ CADASTRO(S) REGISTRADOS, VÁ PARA O MENU (CADASTRAR) PARA REGISTRAR UM OU MAIS CADASTRADOS")
            print ("="*85)
    elif i == 4:
        if nome != "NÃO CADASTRADO" and cpf != "NÃO CADASTRADO" and celular != "NÃO CADASTRADO" and sexo != "NÃO CADASTRADO" and email != "NÃO CADASTRADO" and senha:
            print ("DADOS ATUAIS")
            print ("-"*85)
            print ("[CADASTRO - 1]")
            print ("NOME: ", listnome[0])
            print ("CPF: ", listcpf[0])
            print ("CELULAR: " ,listcelular[0])
            print ("SEXO: ", listsexo[0])
            print ("EMAIL: ", listemail[0])
            print ("SENHA: ", listsenha[0])
            print ("-"*85)
            print ("[CADASTRO - 2]")
            if registros < 2:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[1])
                print ("CPF: ", listcpf[1])
                print ("CELULAR: " ,listcelular[1])
                print ("SEXO: ", listsexo[1])
                print ("EMAIL: ", listemail[1])
                print ("SENHA: ", listsenha[1])
                print ("-"*85)
            if registros < 3:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("[CADASTRO - 3]")
                print ("NOME: ", listnome[2])
                print ("CPF: ", listcpf[2])
                print ("CELULAR: " ,listcelular[2])
                print ("SEXO: ", listsexo[2])
                print ("EMAIL: ", listemail[2])
                print ("SENHA: ", listsenha[2])
                print ("-"*85)
            print ("[CADASTRO - 4]")
            if registros < 4:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[3])
                print ("CPF: ", listcpf[3])
                print ("CELULAR: " ,listcelular[3])
                print ("SEXO: ", listsexo[3])
                print ("EMAIL: ", listemail[3])
                print ("SENHA: ", listsenha[3])
                print ("-"*85)
            print ("[CADASTRO - 5]")
            if registros < 5:
                print ("NÃO CADASTRADO")
                print ("-"*85)
            else:
                print ("NOME: ", listnome[4])
                print ("CPF: ", listcpf[4])
                print ("CELULAR: " ,listcelular[4])
                print ("SEXO: ", listsexo[4])
                print ("EMAIL: ", listemail[4])
                print ("SENHA: ", listsenha[4])
                print ("-"*85)
            print ("QUAL DOS CADASTROS VISTOS ACIMA, DESEJA ATUALIZAR?")
            print ("1 - [CADASTRO 1]")
            print ("2 - [CADASTRO 2]")
            print ("3 - [CADASTRO 3]")
            print ("4 - [CADASTRO 4]")
            print ("5 - [CADASTRO 5]")
            print ("6 - TODOS OS CADASTROS")
            op2 = int (input("OPÇÃO: "))
            print ("-"*85)
            if op2 == 1:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    listnome [0] = input ("Nome: ")
                    listcpf [0] = input ("CPF: ")
                    listcelular [0] = input ("Celular: ")
                    listsexo [0] = input ("Sexo: ")
                    listemail [0] = input ("Email: ")
                    listsenha [0] = input ("Senha: ")
                    print ("="*85)
                    print ("DADOS ATUALIZADOS COM SUCESSO")
                    print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
            elif op2 == 2:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    listnome [1] = input ("Nome: ")
                    listcpf [1] = input ("CPF: ")
                    listcelular [1] = input ("Celular: ")
                    listsexo [1] = input ("Sexo: ")
                    listemail [1] = input ("Email: ")
                    listsenha [1] = input ("Senha: ")
                    print ("="*85)
                    print ("DADOS ATUALIZADOS COM SUCESSO")
                    print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
            elif op2 == 3:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    listnome [2] = input ("Nome: ")
                    listcpf [2] = input ("CPF: ")
                    listcelular [2] = input ("Celular: ")
                    listsexo [2] = input ("Sexo: ")
                    listemail [2] = input ("Email: ")
                    listsenha [2] = input ("Senha: ")
                    print ("="*85)
                    print ("DADOS ATUALIZADOS COM SUCESSO")
                    print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
            elif op2 == 4:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    listnome [3] = input ("Nome: ")
                    listcpf [3] = input ("CPF: ")
                    listcelular [3] = input ("Celular: ")
                    listsexo [3] = input ("Sexo: ")
                    listemail [3] = input ("Email: ")
                    listsenha [3] = input ("Senha: ")
                    print ("="*85)
                    print ("DADOS ATUALIZADOS COM SUCESSO")
                    print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
            elif op2 == 5:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    listnome [4] = input ("Nome: ")
                    listcpf [4] = input ("CPF: ")
                    listcelular [4] = input ("Celular: ")
                    listsexo [4] = input ("Sexo: ")
                    listemail [4] = input ("Email: ")
                    listsenha [4] = input ("Senha: ")
                    print ("="*85)
                    print ("DADOS ATUALIZADOS COM SUCESSO")
                    print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
            elif op2 == 6:
                print ("VOCÊ REALMENTE DESEJA ATUALIZAR ESSES DADOS?")
                print ("1 - Sim")
                print ("2 - Não")
                opp = int (input ("SUA OPÇÃO: "))
                if opp == 1:
                    print ("[CADASTRO - 1]")
                    listnome [0] = input ("Nome: ")
                    listcpf [0] = input ("CPF: ")
                    listcelular [0] = input ("Celular: ")
                    listsexo [0] = input ("Sexo: ")
                    listemail [0] = input ("Email: ")
                    listsenha [0] = input ("Senha: ")
                    print ("[CADASTRO - 2]")
                    if registros < 2:
                        print ("NÃO CADASTRADO")
                        print ("-"*85)
                    else:    
                        listnome [1] = input ("Nome: ")
                        listcpf [1] = input ("CPF: ")
                        listcelular [1] = input ("Celular: ")
                        listsexo [1] = input ("Sexo: ")
                        listemail [1] = input ("Email: ")
                        listsenha [1] = input ("Senha: ")
                    print ("[CADASTRO - 3]")
                    if registros < 3:
                        print ("NÃO CADASTRADO")
                        print ("-"*85)
                    else:
                        listnome [2] = input ("Nome: ")
                        listcpf [2] = input ("CPF: ")
                        listcelular [2] = input ("Celular: ")
                        listsexo [2] = input ("Sexo: ")
                        listemail [2] = input ("Email: ")
                        listsenha [2] = input ("Senha: ")
                    print ("[CADASTRO - 4]")
                    if registros < 4:
                        print ("NÃO CADASTRADO")
                        print ("-"*85)
                    else:
                        listnome [3] = input ("Nome: ")
                        listcpf [3] = input ("CPF: ")
                        listcelular [3] = input ("Celular: ")
                        listsexo [3] = input ("Sexo: ")
                        listemail [3] = input ("Email: ")
                        listsenha [3] = input ("Senha: ")
                    print ("[CADASTRO - 5]")
                    if registros < 5:
                        print ("NÃO CADASTRADO")
                        print ("-"*85)
                    else:    
                        listnome [4] = input ("Nome: ")
                        listcpf [4] = input ("CPF: ")
                        listcelular [4] = input ("Celular: ")
                        listsexo [4] = input ("Sexo: ")
                        listemail [4] = input ("Email: ")
                        listsenha [4] = input ("Senha: ")
                        print ("="*85)
                elif opp == 2:
                    print ("="*85)
                    print ("ATUALIZAÇÃO DE DADOS CANCELADA")
                    print ("="*85)
    elif i == 5:
        print ("VOCÊ REALMENTE DESEJA SAIR DO PROGRAMA?")
        print ("1 - Sim")
        print ("2 - Não")
        pl = int (input ("SUA OPÇÃO: "))
        if pl == 1:
            print ("="*85)
            print ("PROGRAMA FINALIZADO")
            print ("="*85)
        elif pl == 2:
            print ("OPERAÇÃO CANCELADA")
            print ("="*85)
            i=0
        else:
            print ("="*85)
            print ("OPÇÃO INVÁLIDA")
            print ("="*85)
