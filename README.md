# Demonstração Educacional: Como um Ataque de Phishing Funciona

Neste laboratório, apresentarei de forma didática como um ataque de phishing pode ocorrer. O objetivo é aumentar a conscientização sobre esse tipo de ameaça e mostrar por que devemos ter cuidado com links suspeitos. Este material faz parte do Bootcamp 'Santander - Cibersegurança 2025' e não tem a intenção de incentivar atividades ilícitas, mas sim contribuir para o entendimento de técnicas usadas por atacantes, possibilitando que nos defendamos melhor. Para fins de demonstração, será utilizada uma aplicação gratuita disponível publicamente na internet. 

#### 1. Clonando o repositório da ferramenta
git clone https://github.com/htr-tech/zphisher.git 

#### 2. Acessando o diretório e executando a aplicação
No terminal, entre na pasta clonada e execute o script principal: cd zphisher ./zphisher.sh 

#### 3. Escolhendo o serviço a ser simulado
A ferramenta exibirá uma lista de serviços comuns usados em ataques de phishing. Para esta demonstração, será selecionado o Instagram. 

#### 4. Selecionando a página a ser replicada
Em seguida, escolhe-se qual tipo de página será emulada. Aqui, utilizaremos a página de login do Instagram. 

#### 5. Selecionando o método de hospedagem do link
A aplicação também oferece opções de provedores para gerar a URL temporária. Para esta demonstração, costuma-se utilizar o Cloudflared, por sua praticidade. 

#### 6. Recebendo as URLs geradas
Após a configuração, a ferramenta fornecerá três URLs diferentes, que representam o link da página falsificada. 

#### 7. Visualizando a página simulada
Ao acessar um dos links, será exibida uma cópia da página de login do Instagram, exatamente como configurado anteriormente. Tudo o que for digitado nos campos de “usuário” e “senha” aparecerá no terminal da máquina onde a ferramenta está sendo executada — mostrando como atacantes podem capturar credenciais em um cenário real de phishing. 

#### Conclusão
Esse laboratório mostra claramente como páginas falsas podem ser criadas para enganar usuários desatentos. Reforça-se, portanto, a importância de: 
- verificar cuidadosamente URLs antes de inserir credenciais;
- desconfiar de links enviados por e-mail, mensagens ou redes sociais;
- utilizar autenticação multifator (MFA);
- manter-se atualizado sobre técnicas de engenharia social.