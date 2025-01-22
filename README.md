Projeto Ransomware - Santander Bootcamp Cibersegurança
Este projeto foi desenvolvido como parte do Santander Bootcamp Cibersegurança, realizado pela DIO em parceria com o Santander Universidades.

Sobre o Projeto
Este é um desafio prático que demonstra a criação de um ransomware básico utilizando a linguagem Python. O projeto faz uso da biblioteca pyaes para realizar a criptografia de arquivos. O objetivo é oferecer uma introdução prática à criptografia e segurança cibernética.

Arquivos do Projeto
encrypter.py: Código responsável por criptografar o arquivo teste.txt, alterando sua extensão para teste.txt.ransomwaretroll e deixando seu conteúdo inacessível (criptografado).
decrypter.py: Código responsável por descriptografar o arquivo teste.txt.ransomwaretroll, restaurando o arquivo original.
Como Utilizar
Requisitos
Certifique-se de que você tenha o Python instalado na sua máquina e que a biblioteca pyaes esteja instalada. Caso não tenha, você pode instalá-la com o comando:

bash
Copiar
Editar
pip install pyaes
Passos para Executar
Criptografar o arquivo:

Certifique-se de que o arquivo teste.txt esteja no mesmo diretório que o encrypter.py.
Execute o script encrypter.py:
bash
Copiar
Editar
python encrypter.py
Após a execução, o arquivo será renomeado para teste.txt.ransomwaretroll e seu conteúdo será criptografado.
Descriptografar o arquivo:

Certifique-se de que o arquivo criptografado teste.txt.ransomwaretroll esteja no mesmo diretório que o decrypter.py.
Execute o script decrypter.py:
bash
Copiar
Editar
python decrypter.py
Após a execução, o arquivo original teste.txt será restaurado.
Aviso Importante
Este projeto tem fins puramente educacionais e não deve ser utilizado para fins maliciosos. O uso indevido deste conhecimento pode acarretar sérias penalidades legais. Use este projeto de forma ética e responsável.
