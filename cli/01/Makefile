# Nome do compilador MinGW-w64 para 64 bits
CC = x86_64-w64-mingw32-gcc
# Nome do compilador MinGW-w64 para 32 bits
#CC = i686-w64-mingw32-gcc

# Nome do arquivo executável de saída
OUTPUT = hello.exe
#OUTPUT = hello32.exe

# Arquivos fonte
SOURCES = hello.c

# Opções de compilação
CFLAGS = -Wall -Wextra -O2

# Comando padrão para compilar o executável
all: $(OUTPUT)

$(OUTPUT): $(SOURCES)
	$(CC) $(CFLAGS) -o $(OUTPUT) $(SOURCES)

# Comando de limpeza para remover o executável e outros arquivos temporários
clean:
	rm -f $(OUTPUT)
