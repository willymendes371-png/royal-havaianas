# Royal Havaianas

## Integrantes da dupla
- willy mendes cardoso 
- Nome completo do integrante 2

## Descrição do caso escolhido
A Royal Havaianas é uma loja fictícia, baseada em um pequeno negócio local, especializada na venda de chinelos Havaianas, sandálias e acessórios de praia. Atualmente a loja vende apenas de forma presencial e por redes sociais, sem nenhum site próprio.

## Necessidade identificada
A loja não possui um site, então os clientes precisam entrar em contato diretamente para saber quais produtos estão disponíveis, o que dificulta a divulgação e a comunicação com o público.

## Público-alvo
Homens e mulheres de todas as idades que buscam conforto no dia a dia, frequentadores de praia e piscina e consumidores interessados especificamente em produtos da marca Havaianas. Esse público precisa encontrar facilmente: produtos disponíveis, preços e uma forma simples de entrar em contato.

## Objetivo do site
Permitir que o visitante conheça os principais produtos da loja e consiga entrar em contato para tirar dúvidas ou fazer um pedido. A ação principal esperada é o envio de uma mensagem pelo formulário de contato.

## Processo de desenvolvimento
1. Diagnóstico da necessidade da loja (falta de presença digital).
2. Planejamento das seções da página (Home, Sobre, Produtos, Contato).
3. Construção da estrutura HTML semântica.
4. Estilização com CSS externo, definindo paleta de cores e tipografia.
5. Uso do Bootstrap para o grid, navbar e cards.
6. Implementação das funcionalidades em JavaScript.
7. Testes de responsividade e ajustes finais.
8. Publicação no GitHub Pages.

A versão inicial tinha um visual mais elaborado (com mais seções e animações). Durante o desenvolvimento, a dupla optou por simplificar a página, mantendo apenas o essencial, para facilitar a manutenção do código e a explicação de cada parte.

## Principais decisões do projeto
- **HTML:** uso de elementos semânticos (`header`, `nav`, `main`, `section`, `article`, `footer`) para que a estrutura representasse corretamente o conteúdo, em vez de usar apenas `div`.
- **CSS:** paleta de cores em azul e amarelo, remetendo a praia e verão; tipografia simples (Arial) para garantir legibilidade.
- **Responsividade:** uso do grid do Bootstrap (`row`/`col`) para que os cards de produtos se reorganizem em telas menores.
- **Acessibilidade:** todas as imagens possuem atributo `alt` descritivo, os títulos seguem ordem hierárquica (`h1` > `h2` > `h3`) e as cores de texto/fundo têm contraste adequado.

## Funcionalidade em JavaScript
Foi implementada uma mensagem de confirmação visual no formulário de contato: ao preencher os campos e clicar em "Enviar", aparece a mensagem "Mensagem enviada com sucesso!" na tela (sem envio real para um servidor, conforme as restrições do trabalho). Se algum campo obrigatório estiver vazio, um alerta avisa o visitante antes do envio.

## Uso de Bootstrap
Foram utilizados: navbar simples no cabeçalho, sistema de grid (`container`, `row`, `col`) para organizar os produtos, `cards` para exibir cada produto e classes utilitárias de botão (`btn`, `btn-primary`, `btn-outline-primary`). O Bootstrap foi usado apenas para agilizar a responsividade e a organização visual, sem substituir o HTML/CSS escritos pela dupla.

## Testes realizados
- Redimensionamento da janela do navegador para verificar a responsividade em diferentes larguras de tela;
- Teste de todos os links do menu e do rodapé;
- Teste do formulário de contato, incluindo tentativa de envio com campos vazios;
- Verificação do carregamento das imagens e da navegação por teclado (tecla Tab);
- Teste da página já publicada no GitHub Pages, fora do ambiente local.

## Links
- Link do repositório: _(adicionar após publicar no GitHub)_
- Link do site publicado: _(adicionar após ativar o GitHub Pages)_

## Contribuição dos integrantes
- **Integrante 1:willy mendes cardoso ** diagnóstico da necessidade, estrutura HTML e organização do conteúdo,
  estilização CSS, funcionalidade JavaScript, testes e publicação.
