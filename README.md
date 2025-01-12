# Phishing para captura de senhas do Facebook

# Objetivo do Projeto:

O objetivo deste projeto é demonstrar a implementação de uma técnica de phishing para captura de credenciais usando o Kali Linux e o Social-Engineer Toolkit (SET). Este projeto foi realizado exclusivamente para fins educacionais e de teste de segurança, com todas as permissões necessárias.

# Ferramentas Utilizadas:

Kali Linux: Sistema operacional voltado para testes de penetração e segurança da informação.

Social-Engineer Toolkit (SET): Ferramenta de código aberto projetada para realizar testes de engenharia social.

# Procedimentos Executados:

Obtenção de Acesso Root:

# Acesso root foi obtido utilizando o comando: sudo su no terminal do Kali Linux.

Início do Social-Engineer Toolkit (SET):

# A ferramenta SET foi iniciada com o comando: setoolkit.
 
Configuração do Tipo de Ataque:

Seleção do tipo de ataque de Engenharia Social (Social-Engineering Attacks) dentro da interface do SET.

Seleção do Vetor de Ataque:

Escolha do vetor de ataque de Websites (Web Site Attack Vectors).

Configuração do Método de Ataque:

Configuração do método de Colheita de Credenciais (Credential Harvester Attack Method) para capturar as credenciais inseridas pelas vítimas.

# Clonagem do Site:

Utilização do Clonador de Sites (Site Cloner) para replicar a página de login do Facebook.

Obtenção do endereço IP da máquina utilizando o comando ifconfig.

Definição da URL a ser clonada: http://www.facebook.com.

# Resultados: A configuração foi concluída com sucesso, e a página clonada está preparada para capturar credenciais inseridas pelos usuários, demonstrando a eficácia das técnicas de phishing em um ambiente controlado.

![Alt text](./passwd.png "Optional title")

Considerações Éticas: Este projeto foi realizado com o objetivo de educar sobre as vulnerabilidades de segurança e a importância de métodos preventivos. A prática de phishing para fins maliciosos é ilegal e antiética. Recomenda-se o uso dessas técnicas somente em ambientes controlados e com a devida permissão.

