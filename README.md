# Face-Safety
Este é um programa em Python que usa a biblioteca de reconhecimento facial "face recognition". Ele permite adicionar fotos ao banco de dados, excluir pessoas do banco de dados e ativar o modo scanner que apresenta o nome da pessoa ao entrar de frente a câmera. O programa pode ser usado para segurança ou controle de acesso caso seja adaptado.

# Como Baixar:

### Para esse código você precisa baixar algumas coisas obrigatórias que as bibliotecas pedem:

-  Vá na loja do Windows e baixe o ultimo python disponível, caso queira usar o mesmo que foi usando nesse codigo só entrar nesse linke ["Py-3.11"](https://apps.microsoft.com/store/detail/python-311/9NRWMJP3717K)

-  Segundo baixa esse programa: ["Visual Studio"](https://visualstudio.microsoft.com/pt-br/visual-cpp-build-tools/), ao executar ele abrirá uma pagina de download, nessa pagina selecione a opção "Desenvolvimento para desktop com C++" que geralmente é a primeira opção e aperte em instalar.

-  Terceiro passo, voce precisa baixar esse programa: ["CMake"](https://cmake.org/download/), durante a instalação é importante marca a opção "Add CMake to the system PATH for all users" para evitar problemas, após isso pode continuar o download do programa. "Aviso: Ao programa baixar é importante abrir ele pelo menos uma vez e pode fechá-lo após a abertura"

-  Após fazer os últimos passos recomendo reiniciar o PC para fazer essa etapa, abra seu CMD, e de esse comando: "[pip install dlib && pip install face_recognition && pip install numpy && pip install opencv-python]()"

-  Após fazer todas essas etapas voce pode abrir o arquivo do programa ["Face Safety.py"]()

# Como usar:

-  Essa parte é o lobby, onde você pode acessar as opções do programa.
<img src="https://github.com/Davicjc/Face-Safety/blob/main/Fotos/1-Lobby.jpg?raw=true" width="300">

-  Essa é a tela que aparece ao clicar no botão 'Adicionar Pessoa'. Nesse campo em branco, você irá colocar o nome da pessoa que deseja cadastrar. Após isso, a câmera será aberta e irá aguardar que você aperte qualquer tecla para tirar a foto. Caso o rosto não seja encontrado na imagem, o scanner não funcionará e você deverá apagar o cadastro na opção 'Remover Pessoa'. Depois, você pode refazer o cadastro da pessoa novamente em 'Adicionar Pessoa'. Lembrete: é importante não colocar nomes repetidos.
<img src="https://github.com/Davicjc/Face-Safety/blob/main/Fotos/2-Add.jpg?raw=true" width="500">

-  Nessa parte, você pode escolher quem você irá remover do banco de dados de fotos que fica salvo em sua área de trabalho. Para apagar uma pessoa pelo programa, ele apresentará uma lista de cadastros. Ao encontrar a pessoa que deseja apagar, basta escrever o nome exatamente como foi cadastrado e depois apertar o botão "apagar". O nome da pessoa será excluído nesse ponto do processo. Ao sair da aba "Rmv Pessoa" e entrar novamente, a pessoa não constará mais na lista, caso tenha realizado essa etapa corretamente.
<img src="https://github.com/Davicjc/Face-Safety/blob/main/Fotos/3-Rmv.jpg?raw=true" width="500">

-  Por fim, este é o scanner. Ao apertá-lo, automaticamente carregará o banco de dados de fotos e começará a verificar os rostos com seus respectivos nomes. Se houver algum erro, pode ser devido a um cadastro em que a face da pessoa está com difícil acesso, como o uso de bonés ou falta de iluminação, por exemplo.
<img src="https://github.com/Davicjc/Face-Safety/blob/main/Fotos/4-Scanner.jpg?raw=true" width="400">

