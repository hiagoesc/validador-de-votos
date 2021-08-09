### Validador de votos

Neste jupyter notebook estão scripts em Python para validação de votos de evento gastronômico realizados com códigos aleatórios únicos.

São necessários dois arquivos em excel. O primeiro com os códigos aleatórios separados por categoria e preenchidos com estabelecimentos. Esta planilha deve ser gerada através do projeto [gerador-de-codigos-de-validacao](https://github.com/hiagoesc/gerador-de-codigos-de-validacao) e o preenchimento dos estabelecimentos manualmente no excel conforme os códigos são entregues ao estabelecimento, mas para fins de testagem pode ser realizado com estabelecimentos aleatórios através do [gerador-de-voto-ficticio](https://github.com/hiagoesc/gerador-de-voto-ficticio). O segundo arquivo a ser recebido trata-se de resultado de votação através de um Google Form. Para fins de teste, deve-se gerar uma planilha semelhante com votos fictícios através do [gerador-de-voto-ficticio](https://github.com/hiagoesc/gerador-de-voto-ficticio).

Ele cria um data frame, e salva em excel, com os dados dos votos válidos acrescidos das informações sobre a categoria e o estabelecimento de cada voto.

Este arquivo é necessário para testes de contagem de votos do evento gastronômico.