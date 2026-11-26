# Painel MP — Horas e Financeiro

Aplicação web em HTML, CSS e JavaScript para organizar horas trabalhadas, valores por turma/empresa e controles financeiros.

## Como abrir

1. Abra a pasta [painel-horas-financeiro](./painel-horas-financeiro/).
2. Clique em [index.html](./painel-horas-financeiro/index.html).
3. Baixe o arquivo e abra no navegador (Chrome, Edge ou Firefox).

O painel é uma aplicação estática: não precisa instalar dependências nem executar um servidor para uso local.

## Recursos incluídos

- Cadastro de turmas/empresas, dias da semana, horários e valor por hora.
- Cálculo de horas trabalhadas e valores.
- Acompanhamento de situação e datas de pagamento.
- Lançamentos financeiros de receitas e retiradas.
- Resumos mensais e relatório diário para impressão/PDF.
- Precificação de aulas particulares com estimativa de combustível.
- Calculadora avulsa.
- Backup e restauração dos dados em JSON.

## Armazenamento e observações

Os dados do painel são mantidos no armazenamento do navegador (localStorage). O arquivo também contém uma tentativa de integração opcional com serviços de nuvem disponibilizados pelo ambiente original; fora desse ambiente, essa integração pode não estar disponível. Para preservar os registros, use regularmente **Baixar backup** e guarde o arquivo JSON em local seguro.

O repositório contém o código-fonte da aplicação; ele não recebe automaticamente os dados cadastrados no navegador.

## Estrutura

```
.
├── README.md
├── docs/
│   └── GUIA-DE-USO.md
└── painel-horas-financeiro/
    └── index.html
```

Consulte [o guia de uso](./docs/GUIA-DE-USO.md) para instruções adicionais.
