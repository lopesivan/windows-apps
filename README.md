# Compilação com MinGW no Linux

Este projeto fornece exemplos simples de como compilar programas C para Windows usando MinGW no Linux. Ele contém exemplos para programas de linha de comando (`cli`) e para uma aplicação GUI (`gui`).

## Estrutura de Diretórios

```
.
├── cli
│   ├── 01                       64 bits
│   │   ├── hello.c
│   │   └── Makefile
│   └── 02                       32 bits
│       ├── hello.c
│       └── Makefile
└── gui
    └── 01
        ├── gui_app.c
        └── Makefile

5 directories, 6 files
```

## Exemplos de Linha de Comando (`cli`)

Os programas de linha de comando (`cli`) incluem dois exemplos simples que imprimem "Hello, World!" no console.

### 01 - `hello.c`

Este diretório contém um exemplo básico de programa `hello.c` com um `Makefile` para compilar.

1. Navegue até a pasta `cli/01`.
2. Compile usando o `Makefile`:
   ```bash
   make
   ```
3. O binário `hello.exe` será gerado.

4. Limpe os arquivos temporários usando:
   ```bash
   make clean
   ```

### 02 - `hello.c`

Esta pasta é semelhante ao exemplo `01`, mas você pode personalizar os arquivos `Makefile` e `hello.c` conforme necessário.

## Exemplo GUI (`gui`)

Este projeto também inclui um exemplo de aplicação GUI usando a Win32 API nativa do Windows.

### 01 - `gui_app.c`

O exemplo contém um programa GUI (`gui_app.c`) que cria uma janela simples exibindo "Hello, Windows!".

1. Navegue até `gui/01`.
2. Compile usando o `Makefile`:
   ```bash
   make
   ```
3. Um binário `gui_app.exe` será gerado.

4. Limpe os arquivos temporários com:
   ```bash
   make clean
   ```

## Requisitos

Para compilar os exemplos fornecidos, certifique-se de que você tenha o compilador MinGW-w64 instalado no seu sistema Linux. Para instalá-lo em sistemas baseados em Ubuntu/Debian:

```bash
sudo apt update
sudo apt install mingw-w64
```

## Instruções de Uso

- **Transfira** os arquivos binários (`.exe`) para um sistema Windows.
- **Execute** os binários diretamente no Windows para verificar os resultados.
