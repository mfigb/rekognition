# Reconhecimento de Celebridades
Desafio de projeto para detectar celebridades em imagens

# Condições iniciais para quem utiliza windows
Python - AWS CLI - Conta AWS

# Configuração para windows.
Baixar e executar o AWS CLI MSI installer para Windows (64-bit) https://awscli.amazonaws.com/AWSCLIV2.msi Para outros sistemas, acessar a página: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

Após concluir a instalação, abra uma janela de prompt de comando e use o comando aws --version para confirmar a instalação. 
Resultado esperado:
C:\Users\usuario>aws --version aws-cli/2.23.13 Python/3.12.6 Windows/10 exe/AMD64

Configurar na conta da AWS um usuário IAM com acesso ao Rekognition.

#  Comandos necessários para instalação e configuração dos pacotes e ferramentas essenciais (windows - vscode - python).

pip install boto3 mypy-boto3 => SDK oficial da AWS para Python, o qual fornece uma interface para interagir com os serviços da AWS.
pip install mypy => Ferramenta de verificação de tipos estáticos para Python que facilita a identificação de erros antes da execução do programa. 
python -m pip install "boto3-stubs[rekognition]" => Pacote que fornece anotações de tipo para o boto3. A opção [rekognition] instala as anotações de tipo para o serviço Rekognition da AWS.
pip install dmypy "[daemon]" => Ferramenta que permite rodar o mypy em modo daemon, ou seja, em segundo plano.
pip install virtualenv => Instala o pacote virtualenv, que é uma ferramenta essencial para o gerenciamento de ambientes virtuais em Python.
