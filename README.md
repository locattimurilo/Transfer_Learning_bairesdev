# Transfer_Learning_bairesdev
Projeto referente a atividade: Treinamento de Redes Neurais com Transfer Learning do bootcamp BairesDev com DIO!

No trecho de código:

"data = []

for c, category in enumerate(categories):´[..]"

A memória RAM do collab, mesmo configurada para T4 GPU, não suporta analisar todas as imagens (12.501 para gatos e 12.501 para cachorros), especialmente após configurar um limite para esse número. Outra questão é que há imagens corrompidas e a memória não consegue processar para excluí-las. Percebi isso ao limitar a quantidade de imagens. Aumentei o número de "Epochs" e "Batch_Size", mas a memória ficou menor que 1, então mantive os valores como estavam, apenas para exemplificar. Espero que a acurácia não limite minha avaliação e desempenho.

Traduzi algumas mensagens para o usuário final e pretendo agora criar um modelo com meu próprio dataset. No entanto, optei por não fugir do exemplo inicial.

Adorei o sistema e espero me aprofundar mais. Sei que bibliotecas abertas nem sempre garantem segurança avançada para empresas privadas, mas espero poder entendê-las e, quem sabe, criar as minhas próprias no futuro! Estou animado com o curso e espero ter atendido às expectativas.
