# Bibliotecas de Rede para Draw.io — 3D e Clássico/NOC

Coleção de bibliotecas para desenhar e documentar topologias de rede no [Draw.io (diagrams.net)](https://app.diagrams.net/). Contém **6 bibliotecas XML**: quatro com equipamentos 3D/isométricos e duas no padrão clássico Cisco/NOC. Os desenhos dos ícones foram preservados; somente os metadados de identificação foram ajustados para uma apresentação genérica.

## Bibliotecas disponíveis

| Padrão | Nome na barra lateral | Arquivo | Elementos |
|---|---|---|---:|
| Clássico | Clássico Cisco / NOC — Equipamentos | [01-equipamentos-cisco-noc.xml](bibliotecas/classico/01-equipamentos-cisco-noc.xml) | 8 |
| Clássico | Clássico Cisco / NOC — Serviços e Etiquetas | [02-servicos-etiquetas.xml](bibliotecas/classico/02-servicos-etiquetas.xml) | 10 |
| 3D | 3D — 01 Roteadores e Switches | [01-roteadores-switches.xml](bibliotecas/3D/01-roteadores-switches.xml) | 14 |
| 3D | 3D — 02 Acesso e Óptico | [02-acesso-optico.xml](bibliotecas/3D/02-acesso-optico.xml) | 8 |
| 3D | 3D — 03 Infraestrutura | [03-infraestrutura.xml](bibliotecas/3D/03-infraestrutura.xml) | 5 |
| 3D | 3D — 04 Redes e Serviços | [04-redes-servicos.xml](bibliotecas/3D/04-redes-servicos.xml) | 2 |

**Total: 47 elementos em 6 bibliotecas.**

## Como baixar e importar

1. No GitHub, clique em **Code → Download ZIP**, baixe o arquivo e extraia-o.
2. Acesse [app.diagrams.net](https://app.diagrams.net/) e crie um diagrama vazio.
3. Na interface em português (Portugal), selecione **Ficheiro → Abrir biblioteca de → Aparelho...**. Em inglês: **File → Open Library from → Device...**. O menu pode aparecer como **Arquivo → Abrir biblioteca de → Dispositivo** em outras traduções.
4. Dentro do material extraído, abra **`bibliotecas/classico/01-equipamentos-cisco-noc.xml`**.
5. Repita o caminho **Ficheiro → Abrir biblioteca de → Aparelho...** para importar a biblioteca clássica de serviços e os quatro XMLs da pasta **`bibliotecas/3D/`**.
6. Confira as seis bibliotecas na barra lateral esquerda. Arraste os ícones desejados para o desenho.
7. Salve seu desenho em formato `.drawio` para continuar editando posteriormente.

> **Atenção:** **Ficheiro → Abrir de → Aparelho...** abre um diagrama. Para importar estes arquivos de ícones, use **Ficheiro → Abrir biblioteca de → Aparelho...**.

## Sobre esta edição

- Edição genérica para estudo e documentação de redes, sem diagramas operacionais, endereços de clientes ou nomes de ambientes reais.
- Os nomes das bibliotecas e as tags de identificação foram ajustados. Os gráficos dos ícones foram preservados.
- Os arquivos clássicos utilizam símbolos Cisco nativos do diagrams.net e precisam do suporte correspondente na aplicação.
- **Origem verificada:** os 29 ícones 3D são ilustrações genéricas com fontes SVG no pacote original do projeto; os PNG embutidos foram comparados e 29/29 corresponderam exatamente. Os oito ícones clássicos de equipamentos referenciam formas nativas Cisco do editor, sem embutir imagens oficiais de terceiros.
- **Condições de uso:** respeite as regras aplicáveis aos símbolos Cisco (uso permitido, sem alterar seus desenhos), às formas do Draw.io e a quaisquer direitos de terceiros. Não existe vínculo oficial com fabricantes. Leia a [verificação de proveniência e direitos](PROVENIENCIA-E-DIREITOS.md) antes de redistribuir os arquivos.
- Não se trata de uma coleção oficial de fabricantes.

**Validação:** estrutura XML (`mxlibrary`) e modelos internos verificados. A importação pela interface do Draw.io deve ser testada em ambiente limpo.