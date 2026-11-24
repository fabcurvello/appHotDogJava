# App Hot Dog (Java)

> Repositório didático: exercício prático de Android nativo com **Java**, desenvolvido e aplicado em sala de aula pelo Prof. Fabricio Curvello.

## Sobre o projeto

Aplicativo de pedidos de uma lanchonete de cachorro-quente: o cliente monta o seu hot dog e o app mostra o resumo do pedido.

## Contexto acadêmico

Exercício aplicado em sala de aula, usado como prática guiada com os alunos.

## Versão em Kotlin

Esta mesma aplicação também foi desenvolvida em **Kotlin**: [appHotDogFastFoodKotlin](https://github.com/fabcurvello/appHotDogFastFoodKotlin). A única diferença de conteúdo está nos acompanhamentos oferecidos. Comparar as duas versões lado a lado ajuda a entender as diferenças de sintaxe entre Java e Kotlin no Android.

## O que o app faz

- Campo para o nome do cliente.
- Escolha da proteína com `RadioGroup`.
- Escolha dos molhos (catchup, mostarda, maionese) com `CheckBox`.
- Escolha dos acompanhamentos (milho, ervilha, queijo ralado) com `SwitchCompat`.
- Botão **Realizar Pedido** que monta o resumo do pedido e mostra na tela.

## Conceitos trabalhados em aula

- Componentes de formulário: `EditText`, `RadioGroup`/`RadioButton`, `CheckBox`, `Switch`
- Leitura do estado dos componentes (`isChecked`, `getCheckedRadioButtonId`)
- Organização do código em métodos (`setupViews`, `setupListeners`)
- Montagem de texto com concatenação de *strings*

## Tecnologias

- **Java**
- **Android SDK** (Android Studio)
- **Gradle**
- `minSdk 27` / `compileSdk 34`

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fabcurvello/appHotDogJava.git
   ```
2. Abra a pasta no **Android Studio** e aguarde a sincronização do Gradle.
3. Execute em um emulador ou dispositivo físico com Android compatível com a API 27 ou superior.

## Veja também

Outros repositórios de aula com o mesmo tema:

- [appHotDogFastFoodKotlin](https://github.com/fabcurvello/appHotDogFastFoodKotlin)
- [AppHotDogFastFoodKotlinCom3Activities](https://github.com/fabcurvello/AppHotDogFastFoodKotlinCom3Activities)

## Autor

**Fabricio Curvello**: professor de desenvolvimento de software no SENAI-RJ (desde 1997) e em faculdades do grupo Ânima Educação (IBMR e UNA).

- GitHub: [github.com/fabcurvello](https://github.com/fabcurvello)
- LinkedIn: [linkedin.com/in/fabriciocurvello](https://www.linkedin.com/in/fabriciocurvello)
- YouTube: [@fabriciocurvello](https://www.youtube.com/@fabriciocurvello)
