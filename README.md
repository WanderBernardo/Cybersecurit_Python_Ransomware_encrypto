# Encriptografar um arquivo
Objetivo é encriptograr um arquivo para quando alguém abrir não conseguir entender/identificar do que se trata.

### Ferramentas utilizadas:

- Kali Linux (https://www.kali.org/)
- Linguagem Python (https://www.python.org/)
- NANO (neste exemplo usaremos o NANO para construir e executar o código, mas podem usar outras ferramentas como myCompiler, CMD etc. Já tem instalado no Kali) (https://medium.com/@habbema/tutorial-do-nano-3e6aec905213)

### Resumo do que o codigo faz:

 - Acesso o Terminal Emulator (CMD)
 - Iniciar NANO: nano
 - Construir o codigo para abrir o arquivo a ser criptografado
 - Construir o codigo para remover o arquivo o arquivo original
 - Construir o codigo para chave de criptografia
 - Construir o codigo para criptografar o arquivo
 - Construir o codigo para salvar o arquivo criptografado

### Detalhamento do codigo construído:

01 - Acesso o Terminal Emulator (CMD):
![image](https://github.com/user-attachments/assets/e8537deb-7a38-4b89-8e8e-60e1cfce7d2a)

02 - Para acessar o NANO apenas digitar ``` nano ``` na tela
![image](https://github.com/user-attachments/assets/2d647809-8d8a-4d24-9228-7febcd4cd626)

03 - Antes de iniciar a digitar o codigo precisamos importar duas bibliotecas para o codigo:
 - os    - é um conjunto de funções que permite interagir com o sistema operacional na maquina.
 - pyaes - é o algoritmo que será usado para cryptograr








