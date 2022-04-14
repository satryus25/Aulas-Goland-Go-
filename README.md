# Aulas e Desafios na DIO
#Exercício 103

def jogador(nome, gol):
	print(f'O jogador {nome}, marcou {gol}, gols.')

nome_jogador = input('Nome do jogador:  ')
gols = input('Gols marcados:  ')

nome_jogador = 'Desconhecido' if nome_jogador == '' else nome_jogador
gols = 0 if gols == '' else gols

jogador(nome_jogador, gols)
