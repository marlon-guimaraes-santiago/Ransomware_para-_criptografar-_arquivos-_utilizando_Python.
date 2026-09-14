# Ransomware_para-_criptografar-_arquivos-_utilizando_Python.
# encrypter.py
- Esse código pega um arquivo chamado teste.txt, lê tudo o que está dentro dele e guarda esse conteúdo temporariamente na memória. Depois disso, ele apaga o arquivo original do computador. Em seguida, utiliza uma chave chamada testeransomwares para criptografar o conteúdo usando o algoritmo AES, fazendo com que as informações fiquem ilegíveis para quem tentar abrir o arquivo normalmente. Por fim, ele cria um novo arquivo chamado teste.txt.ransomwaretroll e salva nele o conteúdo já criptografado.
 # decrypter.py 
- Esse código faz o processo contrário ao anterior: ele descriptografa o arquivo. Primeiro, abre o arquivo teste.txt.ransomwaretroll e lê todo o conteúdo criptografado. Depois, utiliza a mesma chave testeransomwares usada na criptografia para configurar o AES e recuperar os dados originais por meio do comando decrypt. Em seguida, o arquivo criptografado é apagado e o programa cria novamente um arquivo chamado teste.txt, gravando nele o conteúdo já descriptografado.
  
