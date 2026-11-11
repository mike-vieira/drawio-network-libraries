# Proveniência e condições de uso

Esta nota documenta a revisão feita em 11/11/2026 para a edição pública de 6 bibliotecas XML (47 elementos) do Draw.io. É uma verificação técnica de proveniência e das condições publicadas pelas fontes, **não um parecer jurídico**.

## Padrão 3D / isométrico — 29 elementos

- Origem identificada: pacote-fonte de trabalho da coleção 3D, com **29 arquivos SVG vetoriais editáveis, 29 PNG correspondentes e um LEIA-ME**.
- O LEIA-ME do pacote-fonte descreve os itens como **ilustrações originais genéricas em perspectiva**, e não fotografias ou modelos oficiais dos fabricantes.
- Foram decodificados os 29 elementos 3D do XML, extraídas as imagens PNG embutidas e comparados seus **hashes SHA-256** com os PNG do pacote-fonte: **29/29 correspondências exatas**.
- Foi montada uma revisão visual de todos os 29 itens: **não foram identificados logotipos corporativos ou de fabricantes**. São representações genéricas de roteadores, switches, CPE, OLT, ONT, fibra, rack, POP e serviços.
- As quatro bibliotecas preservam os desenhos da coleção-fonte. Não foram utilizados os conjuntos separados de *equipamentos reais*, que continham referências a fotografias ou desenhos comerciais.

A existência das fontes SVG e a descrição original do pacote dão suporte à procedência como arte criada para este projeto. Não é possível afirmar exclusividade de todos os aspectos visuais nem garantir ausência de semelhança com obras de terceiros.

## Padrão clássico / NOC — 18 elementos

- A biblioteca de **equipamentos** contém oito elementos com referências `shape=mxgraph.cisco.*` a formas **nativas do Draw.io**. Não incorpora PNGs ou SVGs copiados da Cisco; o editor renderiza as formas a partir de seus próprios recursos.
- A biblioteca de **serviços e etiquetas** contém dez elementos de desenhos comuns do editor (nuvens, textos, etiquetas e estados), sem artes comerciais embutidas.
- A Cisco publica seus ícones de topologia com autorização de uso, **sem permitir alterações**. Para seu uso, preserve o desenho original dos símbolos. O arquivo da biblioteca contém estilos de aparência (por exemplo, cor de preenchimento), mas não altera o arquivo-fonte dos *stencils* internos.

Referência: https://www.cisco.com/c/en/us/about/brand-center/network-topology-icons.html

## Draw.io / diagrams.net

O projeto original é um editor de diagramas; seus recursos gráficos podem ter regras próprias e direitos de terceiros. Não presuma que a licença do código-fonte se estenda automaticamente a todas as artes. O README oficial também traz restrições específicas para uso de bibliotecas e derivados no ecossistema Atlassian, sem autorização por escrito.

- https://github.com/jgraph/drawio
- https://www.drawio.com/docs/manual/advanced/custom-shape-libraries/
- https://www.drawio.com/docs/manual/shapes/extra-icon-sets/

## Direitos das criações assistidas por IA

Quando uma ilustração é criada como saída de serviço da OpenAI, a titularidade dessa saída entre o usuário e a OpenAI segue os Termos de Uso, até onde a legislação permitir. Isso **não** resolve direitos de terceiros que possam estar presentes na entrada ou no conteúdo.

- https://openai.com/policies/row-terms-of-use/

## Resultado da revisão

- **Dados operacionais:** nenhum identificador textual corporativo, ASN operacional ou hostname de produção identificado na revisão dos seis XMLs e documentos.
- **3D:** 29 fontes SVG e 29 PNG originais localizados, com correspondência exata das imagens incorporadas e sem marcas visíveis identificadas.
- **Clássico:** referências a formas nativas do editor, sem redistribuição de arquivos de imagem Cisco; aplicar as condições de uso dos proprietários.
- **Importação:** estrutura dos seis arquivos `mxlibrary` validada; **não há confirmação de teste de importação interativa em instalação limpa**.
- **Limite:** esta revisão não equivale a uma autorização emitida por Cisco, Draw.io ou terceiros nem substitui uma análise jurídica, caso exigida.

O repositório apresenta bibliotecas para documentação e estudo de redes, sem afiliação ou endosso de fabricantes.
