# Nome do compilador MinGW-w64 para 64 bits
CC   = x86_64-w64-mingw32-gcc
LIBS = -mwindows

# Nome do arquivo executável de saída
OUTPUT = gui_app.exe

# Arquivos fonte
SOURCES = gui_app.c

# Opções de compilação
CFLAGS = -Wall -Wextra -O2

# Comando padrão para compilar o executável
all: $(OUTPUT)

$(OUTPUT): $(SOURCES)
	$(CC) $(CFLAGS) -o $(OUTPUT) $(SOURCES) $(LIBS)

# Comando de limpeza para remover o executável e outros arquivos temporários
clean:
	rm -f $(OUTPUT)
