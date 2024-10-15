📊 Tabela SVG no Power BI
= 

Este repositório contém um exemplo de visualização de uma tabeka SVG, desenvolvido usando DAX e SVG. O visual exibe informações sobre colaboradores, como nome, status, cargo, data de admissão e pontuação de performance, além de uma barra de progresso dinâmica que representa a performance do colaborador.

👤 Autor
=

Nome: Reed Iury

LinkedIn: linkedin.com/in/reediury

📦 Arquivos
=

tabela_svg.pbix: Exemplo de relatório Power BI com a visualização de status dos colaboradores.

README.md: Este arquivo de documentação.

🚀 Instruções de Uso
=

Para usar este visual no Power BI, você pode incorporar o código DAX fornecido em um cartão ou tabela que suporte a renderização de SVG. O código gera um SVG dinâmico que exibe informações atraentes sobre o status dos colaboradores.

Arquivo de Exemplo:
=

O arquivo tabela_svg.pbix contém um exemplo completo com o código aplicado.

Explicação do Código:
=
O código é estruturado para gerar uma visualização SVG que mostra:

Status do Colaborador:

O status é determinado pela coluna [Status], onde 1 representa "Ativo" e 0 representa "Inativo".
As cores são atribuídas com base no status, utilizando verde (#4CAF50) para "Ativo" e laranja (#FF9800) para "Inativo".

Informações do Colaborador:

O nome do colaborador é exibido em texto negrito.
O cargo do colaborador e a data de admissão são apresentados abaixo do nome, formatando a data como "dd/MM/yyyy".

Performance:

A pontuação de performance é obtida da coluna [PerformanceScore], que varia de 0 a 100.
A barra de performance muda de cor com base na pontuação:
Verde (#4CAF50) para pontuação ≥ 80.
Amarelo (#FFC107) para pontuação entre 50 e 79.
Vermelho (#F44336) para pontuação < 50.

Animações:

A barra de progresso é animada para crescer de 0 até a pontuação de performance ao longo de 2 segundos, criando uma visualização dinâmica.
O texto percentual dentro da barra muda de cor durante a animação, destacando a performance.

Variáveis Principais:
=

Status: Coluna que indica se o colaborador está "Ativo" ou "Inativo".
Position: Cargo do colaborador.
HireDate: Data de admissão do colaborador.
PerformanceScore: Pontuação de performance do colaborador, que varia de 0 a 100.

Funções Principais:
=

SVG Animation: Gera um SVG dinâmico que exibe o nome, status, cargo, data de admissão e pontuação de performance do colaborador com animações visuais.

Dynamic Colors: As cores da barra de progresso e do status mudam dinamicamente com base nas condições definidas (ativo/inativo e pontuação de performance).

🛠 Como Personalizar
=

Modifique as cores e estilos das animações no SVG para atender às suas preferências.
Ajuste a lógica para integrar outras métricas ou informações sobre os colaboradores, conforme necessário.
Para testar e visualizar, você pode ajustar os dados de exemplo no Power BI.

🌟 Demonstração do Visual
=

https://github.com/user-attachments/assets/db051097-37db-445f-9857-dfe8b3030f7b

Se tiver dúvidas ou sugestões, entre em contato comigo pelo LinkedIn.
