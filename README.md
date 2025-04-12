# IA
# Descrição do Programa

O programa inicializa um **8‑puzzle (3×3)**, identifica o espaço vazio (**0**) e permite mover peças até atingir o estado objetivo, que pode ser definido pelo usuário ou usando um padrão.

Escolhi a versão que **copia e edita o estado do nó pai**, criando cópias independentes para cada movimento e mantendo o nó original imutável. Essa abordagem simplifica a **busca em profundidade iterativa (IDDFS)**, evita a necessidade de desfazer alterações e garante a exploração correta de todos os caminhos.
