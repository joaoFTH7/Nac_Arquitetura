Executar o playbook do GitLab na pasta raiz:

ansible-playbook auto.yml

1 - Escolha do SO:
Foi escolhido o Ubuntu por alguns fatores, um deles foi a sua larga utilização em empresas de grande porte e também no usoem geral seja doméstico até o nível empresarial, empresas como: Netflix,Uber, AT&T utilizam muito a distro Ubuntu. Por serutilizado em muitas esferas é muito mais fácil encontrar material de ajuda e fóruns falando sobre o sistema. 
Versões com LTS tem 5 anos de suporte.
Com o gerenciador de pacotes APT é possível não só instalar pacotes, como também desinstalar, atualizar o próprio SO, atualizar os pacotes, também é possível realizar operações baseadas em cache para busca de informações sobre algum pacote especifíco ou listar as dependências do mesmo, trazendo bastante flexibilidade e agilidade para o gerenciador. Utilizando-se também da ideia de repositórios que podem conter um extenso número de pacotes e variados pacotes específicos para uma determinida tarefa.


2 - Escolha da Automação:
Automação escolha foi Ansible, pela sua facilidade de implementação por não precisar instalar aplicações cliente/agente
nos hosts que serão aplicados a automação.

Dupla que construiu o trabalho:
RM83188 - João Pedro Costa de Almeida
RM82267 - Luiz Calimério Takao Dias
