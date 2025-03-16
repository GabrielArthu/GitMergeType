# Tipos de Merge no Git

## Merge
O comando `git merge` combina as mudanças de diferentes branches. Ele cria um commit de merge que une o histórico das branches envolvidas.

## Fast-Forward Merge
O `fast-forward merge` ocorre quando a branch de destino não tem commits adicionais desde que a branch de origem foi criada. O Git simplesmente move o ponteiro da branch de destino para o último commit da branch de origem, sem criar um commit de merge.

## Non Fast-Forward Merge
O `non fast-forward merge` é usado quando a branch de destino tem commits adicionais que não estão na branch de origem. O Git cria um commit de merge que une os históricos das duas branches, preservando todos os commits.

## Squash Merge
O `squash merge` combina todos os commits da branch de origem em um único commit na branch de destino. Isso simplifica o histórico, mas perde a granularidade dos commits individuais da branch de origem.
