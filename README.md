# Transfer_Learning_bairesdev
Projeto referente a atividade: Treinamento de Redes Neurais com Transfer Learning do bootcamp BairesDev com DIO!

No trecho de código:

"data = [ ]

for c, category in enumerate(categories):´[..]"

A memória RAM do collab, mesmo configurada para uso no T4 GPU, não suporta analisar todas as imagens (12.501 para gatos e 12.501 para cachorros), especialmente após configurar um limite para esse número. Outra questão é que há imagens corrompidas e a memória não consegue processar para excluí-las. Percebi isso ao limitar a quantidade de imagens. Aumentei o número de "Epochs" Batch_Size(aumentei para 256), mas a memória GPU não suportou novamente, então mantive os valores como estavam, apenas para exemplificar (epochs deixei em 20). 

Traduzi algumas mensagens para o usuário final e pretendo agora criar um modelo com meu próprio dataset. No entanto, optei por não fugir do exemplo inicial neste projeto.
