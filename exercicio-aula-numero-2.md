# Exercício Aula 2

## Alterar os atributos de cada widget do nosso ActivityLayout da aula passada para:
### 1. TextView
* Label  = “Nome do Usuário” (via código ou em tempo de execução)
* Background = “cor_branca”
* Cor = “cor_preta”
* Tamanho texto = 28sp

### 2. EditText
* Hint  = “digite o nome do usuário aqui”
* Background = “cor_branca
* Cor = “cor_preta”
* Tamanho texto = 28sp

### 3. Button
* Label = “Enviar Dados”  (via código ou em tempo de execução)
* Fundo = “cor_cinza”
* Cor = “cor_preta”
* Tamanho texto = 24sp
* Lagura = 200dp
* Altura = 40dp
* Evento onClick = “metodo_click”

####  **Boas práticas (obrigatórias):**
* Novas strings devem ficar no resource string.xml (text, hint);
* Novas cores no colors.xml;
* Tamanhos no dimens.xml;
* Nome de variáveis no layout devem ter os prefixos:
* btn_, txt_, edt_ (separadas por _ e lowercase);
* Nome de variáveis no código, no metodo onCreate, usar camelCase e práticas Clean Code:
* Exemplo: btnEnviarDadosUsuario
* Deve compilar e rodar direto no emulador sem errors ou warnings;

------------

> **Você parou para pensar que há um dia atrás você não conhecia a maioria dos termos desses exercicios?**
