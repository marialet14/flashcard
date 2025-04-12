import random

verbs = {
    "manger": "j'ai mangé",       #comer
    "aller": "je suis allé",      #ir
    "finir": "j'ai fini",         #terminar
    "prendre": "j'ai pris",       #pegar
    "venir": "je suis venu(e)",   #vir
    "voir": "j'ai vu",            #ver
    "avoir": "j'ai eu",           #ter
    "être": "j'ai été",           #ser/estar
    "faire": "j'ai fait",         #fazer
    "lire": "j'ai lu"             #ler
}

print("Flashcards de Verbos Franceses (Infinitif - Passé Composé)")
print("Digite 'sair' para encerrar o jogo.\n")
cont = 0
while cont == 0:
    verb = random.choice(list(verbs.keys()))
    resposta = input(f"Qual é o passé composé de '{verb}'? ").strip().lower()

    if resposta == "sair":
        print("À la prochaine!")
        cont += 1
    elif resposta == verbs[verb].lower():
        print("Très bien!")
    else:
        print(f"Pas encore! A resposta correta é: '{verbs[verb]}'.")
