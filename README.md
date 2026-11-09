# Network Labs — Laboratórios de Redes (Universidade)

Este repositório tem como finalidade apresentar e documentar os laboratórios de redes que construo como parte das avaliações da universidade. Cada laboratório está organizado numa pasta independente e inclui a topologia de rede (Cisco Packet Tracer), imagens da topologia e um `README` com os objetivos, procedimentos de configuração e instruções de utilização.

## Objetivo do projeto

Documentar de forma clara e estruturada a prática de configuração de dispositivos de rede, endereçamento IP, comutação, roteamento e serviços de rede, servindo como registo de aprendizagem e apoio para avaliações académicas da área de redes de computadores.

## Ferramentas utilizadas

- [Cisco Packet Tracer](https://www.netacad.com/) — simulação de topologias de rede (ficheiros `.pkt`)
- Markdown — documentação dos laboratórios

## Estrutura de pastas

```text
network_labs/
├── README.md              # Este ficheiro (documentação geral do projeto)
├── lab01/                 # Laboratório 01 — Configuração Básica de Dispositivos de Rede
│   ├── apk_file/
│   │   └── lab01.pkt      # Ficheiro da topologia do Cisco Packet Tracer
│   ├── images/
│   │   └── lab.png        # Imagem da topologia de rede
│   └── README.md          # Documentação detalhada do laboratório 01
└── labXX/                 # Laboratórios futuros (exemplo de estrutura)
    ├── apk_file/
    │   └── labXX.pkt
    ├── images/
    │   └── lab.png
    └── README.md
```

> Convenção de pastas: cada laboratório ocupa o seu próprio diretório (`lab01`, `lab02`, …) contendo os ficheiros de simulação em `apk_file/`, imagens da topologia em `images/` e a documentação em `README.md`.

## Laboratórios disponíveis

| Laboratório | Descrição | Topologia |
|-------------|-----------|-----------|
| [Lab 01](./lab01) | Configuração básica de dispositivos de rede (hostnames, endereçamento IP, senhas de console/privilégio, banner MOTD, acesso VTY limitado, encriptação de senhas e roteamento estático IPv4) com Cisco Packet Tracer | [ver imagem](./lab01/images/lab.png) |

## Como utilizar um laboratório

1. Instale o [Cisco Packet Tracer](https://www.netacad.com/).
2. Navegue até à pasta do laboratório pretendido (exemplo: `lab01/`).
3. Abra o ficheiro da topologia em `apk_file/labXX.pkt` no Packet Tracer.
4. Consulte a imagem da topologia em `images/lab.png` para identificar os dispositivos e os endereços IP.
5. Leia o `README.md` dentro da pasta do laboratório para conhecer os objetivos e os procedimentos de configuração detalhados.
