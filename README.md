# Meu Primeiro Projeto em Dart

Este é o meu primeiro projeto utilizando a linguagem Dart! Estou começando a estudá-la e desenvolvi um pequeno programa para calcular o Índice de Massa Corporal (IMC) de uma pessoa.

## Como o programa funciona?

O programa solicita ao usuário algumas informações pessoais:
- Nome
- Idade
- Altura (em metros)
- Peso (em kg)

Após coletar essas informações, ele calcula o **IMC** utilizando a seguinte fórmula:

```
IMC = peso / (altura * altura)
```

Por fim, o programa exibe o nome do usuário e o seu IMC. Para evitar que a janela feche imediatamente, ele aguarda o usuário pressionar **ENTER** antes de encerrar.

## Como baixar e rodar o executável

Caso queira apenas rodar o programa sem precisar instalar o Dart, siga os passos abaixo:

### 1️⃣ Baixar o executável

1. Acesse o repositório no GitHub.
2. Vá até a seção **Releases**.
3. Baixe o arquivo `imc_calculate.exe`.

### 2️⃣ Executar o programa

1. Abra o terminal (`cmd` ou `PowerShell`).
2. Navegue até a pasta onde baixou o `imc_calculate.exe`.
3. Execute o comando:
   ```sh
   ./imc_calculate.exe
   ```
4. Insira as informações solicitadas.
5. O programa calculará e mostrará seu IMC!

## Como compilar o projeto a partir do código fonte

Se quiser compilar o programa por conta própria, siga estes passos:

### 1️⃣ Instalar o Dart SDK

Baixe e instale o **Dart SDK** no site oficial:
- [Dart SDK](https://dart.dev/get-dart)

### 2️⃣ Clonar o repositório

```sh
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

### 3️⃣ Compilar o código para gerar um `.exe`

No terminal, execute:
```sh
dart compile exe bin/dart_imc_calculate.dart -o build/imc_calculate.exe
```

Isso gerará o executável em `build/imc_calculate.exe`, que poderá ser rodado diretamente.

---
### Autor

- Kaiqui Benevenutti

