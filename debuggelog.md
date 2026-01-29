# 🛠️ DEBUGGE LOG - Desafio de Cartão de Perfil

## 1. Padronização e Sintaxe (DevOps Mindset)
- **O que aprendi:** Nomes de classes e arquivos devem seguir o padrão global (sem acentos ou cedilhas) para evitar erros de leitura em servidores Linux/Case-sensitive.
- **Sintaxe:** O ponto e vírgula `;` é o terminador de instrução essencial para que o navegador não ignore as regras seguintes.

## 2. Composição de Classes e Especificidade
- **O que aprendi:** Um elemento pode herdar estilos de múltiplas classes. Quando há conflito, o navegador aplica a lógica da **Cascata**: a última regra declarada no arquivo CSS sobrescreve as anteriores se tiverem o mesmo peso.

## 3. Box Model (Espaçamento)
- **O que aprendi:** - **Padding:** Controla o respiro interno, afastando o conteúdo da borda.
  - **Margin:** Controla o distanciamento externo entre os componentes.
- **Resultado:** O uso correto de ambos garante um layout harmônico e evita que elementos fiquem "grudados".

## 4. Estética e UX (User Experience)
- **O que aprendi:** O uso de `border-radius` (formato pílula) e `box-shadow` (profundidade) cria uma hierarquia visual moderna. 
- **Interação:** A propriedade `transition` em conjunto com `translateY` no estado `:hover` fornece um feedback visual suave, indicando que o elemento é interativo.