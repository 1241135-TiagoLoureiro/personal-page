# personal-page

Página pessoal com apresentação, CV para descarregar e ligações para o LinkedIn e GitHub. Adaptada a PC e telemóvel, para partilha através de um QR code.

## Abrir localmente

Abrir `index.html` no navegador. Não é necessário instalar dependências nem compilar.

## Organização

- `index.html`: conteúdo e ligações.
- `css/style.css`: aspeto e disposição responsiva.
- `assets/cv.pdf`: currículo disponível para consulta e download.
- `doc/README.md`: orientações e referências visuais.
- `doc/design/`: vistas exportadas do Figma.

## Atualizar

Editar os textos e os links em `index.html`. Para atualizar o CV, substituir `assets/cv.pdf`, mantendo esse nome. As cores, dimensões e regras de disposição estão em `css/style.css`.

O conteúdo fica centrado horizontal e verticalmente quando cabe no ecrã. Em ecrãs menores, a página permite deslocação vertical sem cortar o topo.

A fonte preferida é Inter, com Arial e sans-serif como alternativas locais. Não há pedidos a serviços externos de fontes.

## Design

[Proposta editável no Figma](https://www.figma.com/design/xdso1MuNYcD5hdSc1gt7is). A implementação aplica também a centragem pedida após as exportações.

## Publicar no GitHub Pages

No repositório, abrir **Settings > Pages**, escolher **Deploy from a branch**, selecionar `main` e a pasta `/ (root)` e guardar. Esta configuração deve ser feita depois de o código estar na branch escolhida.

A publicação ainda não foi executada nem confirmada. Antes de publicar, rever o PDF e os dados pessoais que ficarão públicos. Depois, gerar o QR code para o endereço confirmado da página.

## Verificar alterações

Abrir a página em larguras de PC e telemóvel e confirmar que não existe deslocação horizontal. Testar a navegação por teclado, os perfis, a abertura e o download do PDF. Confirmar também o QR code num telemóvel após a publicação.
