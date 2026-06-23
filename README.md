Implementação prática de infraestrutura para balanceamento de carga utilizando Docker e Nginx.

## Arquitetura
* **Proxy Reverso:** Container Nginx exposto na porta 80.
* **Backend:** Dois containers isolados rodando em uma rede interna.
* **Algoritmo:** Round Robin.

## Como reproduzir
1. Clone o repositório.
2. Execute docker compose up -d.
3. Acesse o IP do host no navegador e atualize a página para visualizar o balanceamento entre as instâncias.
EOF
