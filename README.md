# Ficha de Herói — Parte 1

Projeto individual de Tecnologia Web (HTML + CSS).

## O personagem

**Aion Veyr**, mago arquivista de um mundo medieval no estilo D&D. Tem memória fotográfica e aprendeu toda a magia pelos livros da biblioteca de seu mestre. Essa bibleotéca era escondida dentro de uma caverna onde só que tinha a chave, que o mestre o entregou antes de morrer, poderia entrar nela. Lá havia todos os livro que um mago poderia e até aqueles que não poderiam ter acesso, texto proibidos, e que até então, eram considerados benidos e perdidos no mundon da magia. Nesta bibliotéca foi aplicado um feitiço onde dentro dela se passase 1 ano enquanto do lado de fora havia se passado apenas 1 hora, assim o jovem pode se tortar um dos magos mais poderosos que existe em algumas horas.

## O projeto

Página com 4 seções: Sobre o Herói, Atributos & Habilidades, Inventário & Conquistas e Contato com a Guilda.

- HTML semântico: `header`, `nav`, `main`, `section`, `footer`.
- CSS externo (`style.css`) organizado em blocos comentados.
- Menu com Flexbox e inventário com CSS Grid.
- Media queries: 1 coluna no celular, 2 no tablet (600px) e 3 no desktop (1000px).
- Paleta em variáveis CSS (`:root`) usada em fundo, títulos, bordas e barras.
- Barras de atributo feitas só com HTML e CSS (`div` com `width` em porcentagem).
- `transition` com mudança de cor e leve aumento (`scale`) em cards, botão e menu.
- Pseudo-elemento `::before` como selo decorativo nos cards de item.
- Fontes Cinzel e EB Garamond (Google Fonts) e ícones Font Awesome.

## Decisões de UI/UX

- **Hierarquia visual:** o nome do herói (h1, 2.6rem, dourado) e o avatar aparecem primeiro. Depois vêm os títulos de seção (h2) e, por último, o texto corrido.
- **Contraste e legibilidade:** texto claro (#eadfc8) sobre fundo escuro (#14110f) e dourado nos títulos, com contraste acima do mínimo WCAG AA. As raridades usam texto escuro sobre fundos claros.
- **Consistência:** todos os cards de item têm a mesma borda, o mesmo raio, o mesmo espaçamento e o mesmo selo; todas as barras de atributo seguem o mesmo padrão.
- **Affordance e feedback:** links e botões mudam de cor e crescem levemente no hover, e têm contorno visível no foco do teclado.
- **Área de toque (Lei de Fitts):** links do menu e botão têm no mínimo 44 a 48px de altura.
- **Proximidade (Gestalt):** ícone, nome do atributo, valor e barra ficam agrupados juntos; o item de destaque ocupa a linha inteira do inventário.
- **Fluxo de leitura:** a página segue a ordem natural, do herói (Sobre) para seus poderes (Atributos), seus objetos (Inventário) e, por fim, o contato com a guilda.

## Créditos

- Arte do Anel das Sombras: Tyler Vail.
- Ilustração do avatar: autoria a creditar.

## Como abrir

Abra o `index.html` no navegador (ou use o Live Server do VS Code).
