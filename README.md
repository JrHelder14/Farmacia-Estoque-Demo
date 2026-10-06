# Sistema de Controle de Estoque para Farmácia Pública

Projeto demonstrativo de um sistema web para controle de estoque, lotes, validade e dispensação de medicamentos em uma farmácia pública.

> **Aviso:** este projeto é apenas uma demonstração para fins educacionais e de portfólio. Não representa um sistema oficial da Prefeitura Municipal de Montadas. Todos os dados utilizados na demonstração são fictícios.

## Demonstração online

https://farmaciamontadas.netlify.app

## Funcionalidades

- Dashboard com indicadores de estoque
- Alertas de estoque baixo
- Alertas de medicamentos próximos do vencimento
- Cadastro, edição, pesquisa e exclusão de medicamentos
- Leitura e pesquisa por código de barras
- Registro de entradas de medicamentos
- Controle de lotes e datas de validade
- Saída e dispensação de medicamentos
- Seleção de lote na dispensação
- Validação de saldo disponível
- Cadastro e consulta de pacientes
- Cadastro de unidades de saúde
- Histórico de movimentações
- Relatórios e filtros
- Exportação CSV
- Backup e restauração de dados
- Persistência local com LocalStorage
- Layout responsivo

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- LocalStorage
- Netlify

## Como executar localmente

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em um navegador moderno.
3. O sistema carregará com dados fictícios de demonstração.

Não é necessário instalar dependências ou configurar banco de dados para esta versão demonstrativa.

## Estrutura atual

```text
farmacia-estoque-demo/
├── index.html
├── README.md
├── LICENSE
└── .gitignore
```

## Contexto do projeto

O projeto foi desenvolvido para demonstrar como um sistema digital pode facilitar o controle de medicamentos de uma farmácia pública, centralizando informações de estoque, entrada, saída, lotes, validade e dispensação.

A versão atual utiliza armazenamento local no navegador e foi pensada como protótipo funcional e demonstração de interface e regras de negócio.

## Evoluções planejadas

- Backend com API
- Banco de dados PostgreSQL
- Autenticação de usuários
- Perfis e níveis de acesso
- Registro de auditoria
- Integração com banco de dados central
- Rotina automatizada de backup
- Hospedagem de backend
- Testes automatizados adicionais

## Observação sobre identidade visual

A identidade visual utilizada na demonstração faz referência ao município apenas para contextualizar o protótipo. Este repositório não deve ser interpretado como um produto oficial, homologado ou mantido pela Prefeitura Municipal de Montadas.

## Autor

**Junior Helder**

Projeto desenvolvido para estudo, portfólio e demonstração de solução web aplicada à gestão de estoque.