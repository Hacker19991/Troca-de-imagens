# **AppFotos (Troca de imagens)**

> Um aplicativo Android para troca de fotos ao vivo.

## Descrição
O **AppFotos** permite que o usuario possa trocar de imagens atrávez dos botões principais insiridos no trabalho para cada imagem.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [ ] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Troca-de-imagens
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── drawable
   │   │   │   │   ├── foto1.jpg # Primeira imagem e a princiapal
   │   │   │   │   ├── foto2.jpg # Segunda imagem que será trocada atrávez do botão
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/29534ef1-35b4-4299-9d74-31cf978de633)

Uma tela simples, um LinearLayout com um TextView para mostrar qual foto foi trocada e um ImageView onde será mostrado as imagens e onde elas serão trocadas, dois botões para processar a imagem que desejar, um botão para a primeira imagem e o segundo botão para a segunda imagem, simples e básico.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
