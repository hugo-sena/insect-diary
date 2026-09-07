# Projeto — Sistema de Registo e Identificação de Insetos

Pretende-se desenvolver uma aplicação para registar, consultar e organizar observações de insetos, permitindo ao utilizador manter um diário das espécies encontradas.
Cada vez que o utilizador encontra um inseto, deve poder criar uma observação, registando informações como a data e hora, local onde o inseto foi encontrado, planta onde estava, sexo e fase de vida, caso sejam conhecidos.
O utilizador deve poder associar uma ou mais fotografias a cada observação. As fotografias serão utilizadas não só para documentar a observação, mas também futuramente para auxiliar na identificação do inseto.
A aplicação deverá possuir informação sobre as diferentes espécies de insetos observadas. Para cada espécie poderão ser registados o nome científico, nome comum, família, género, ordem e outras informações relevantes, como características de identificação, ciclo de vida, curiosidades e importância ecológica.
Nem sempre será possível identificar um inseto até à espécie. Por isso, o sistema deverá permitir guardar uma observação mesmo quando a identificação é incompleta, por exemplo, quando apenas a família ou género é conhecido.
O utilizador deverá poder consultar e pesquisar as observações, podendo filtrá-las por diferentes critérios, como espécie, data, local, família, sexo ou fase de vida, e ordenar os resultados.
Deverá também ser possível editar e eliminar observações e consultar todos os detalhes associados a uma determinada observação, incluindo as suas fotografias e identificação.
A aplicação deverá permitir ao utilizador registar e corrigir identificações. Quando uma identificação for feita manualmente, deverá ser possível indicar o grau de confiança dessa identificação.
Como funcionalidade adicional, pretende-se desenvolver um sistema de pesquisa através de imagens. O utilizador poderá fornecer uma fotografia de um inseto e o sistema irá compará-la com fotografias de observações existentes, apresentando possíveis correspondências ordenadas de acordo com a sua similaridade.
O sistema deverá apresentar, por exemplo, várias possíveis correspondências em vez de assumir obrigatoriamente que existe uma única resposta correta. O utilizador poderá posteriormente confirmar ou corrigir a identificação sugerida.
A aplicação deverá ainda possuir uma página inicial com informações resumidas sobre as observações, como observações recentes, espécies registadas e outras estatísticas relevantes.
Por fim, deverá ser possível exportar uma observação, ou eventualmente um conjunto de observações filtradas, para utilização fora da aplicação.


# Algumas regras/necessidades importantes
- Uma observação pode ter várias fotografias.
- Uma espécie pode estar associada a várias observações.
- Uma observação pode existir sem uma espécie identificada.
- A identificação pode ser posteriormente alterada ou corrigida.
- Algumas informações são específicas da espécie, enquanto outras são específicas de uma observação.
- O sistema deve permitir guardar informação mesmo quando esta é desconhecida.
- As fotografias devem ser armazenadas separadamente dos restantes dados da observação.
- A pesquisa por imagem deve poder apresentar vários resultados possíveis, com um valor de similaridade.