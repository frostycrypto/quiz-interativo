perguntas = [
    {"pergunta": "Qual a capital do Brasil?", "resposta": "Brasília"},
    {"pergunta": "Qual linguagem é usada para web?", "resposta": "HTML"},
    {"pergunta": "Qual é 5 + 7?", "resposta": "12"}
]

def main():
    print("=== Quiz Interativo ===")
    pontos = 0
    for p in perguntas:
        resposta = input(p["pergunta"] + " ")
        if resposta.strip().lower() == p["resposta"].lower():
            print("✅ Correto!\n")
            pontos += 1
        else:
            print(f"❌ Errado! Resposta correta: {p['resposta']}\n")
    print(f"Você acertou {pontos} de {len(perguntas)} perguntas.")

if __name__ == "__main__":
    main()
