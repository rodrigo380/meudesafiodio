# meudesafiodio
Neste desafio DIO Azure openAI, aprendo como configurar e trabalhar no Play ground.
Azure OpenAI no playground
Minha experiência foi ótima!
1.	Iniciamos com as configurações do Azure OpenAI “Deploy”; criamos uma conta e aprendemos sobre segurança e dados sigilosos.
Azure OpenAI Foundry/ OpenAI: catálogos e modelos;
Inferencia: “Que tipo de previsão de token o modelo faz”
Conclusão de chat, inserções, conversão de texto em fala, texto para imagem, conclusões.
	
2.	UI. Aprendi modelos de IA, implantação, configurações, etc...
Estocastico, randômico: diz se do processo que depende do acaso.
Tokenização: algo muito importante porque também é um consumo que deve ser calculado; a língua portuguesa consome mais tokens do que o Inglês. Biblioteca tiktoken, cotas.
3.	System menssage: contexto inicial do modelo, é muito importante ser especifico e estabelecer limites. Como fazer isso é através de “shots” que são perguntas que direcionam o modelo. 
Zero shot; não precisa de exemplos.
One shot: necessita um exemplo.
Existem limites de contexto, os quais precisa se tomar cuidado.
Como são escolhidas as respostas? 
4.	Temperatura x Top-p
Temperatura zero: respostas previsíveis e deterministas, técnicas geralmente.
Temperatura um: criativas, improváveis, sem sentido, mas logicas.
Top-p: seleciona as opções que vão ser selecionadas. Complementa a temperatura.
Top-p 01 considera 10% de todas as possibilidades
Top-p 09 considera 90% das possibilidades
Use top-p ou temperatura, raramente os dois juntos.
5.	Frequency Penalty x Presency Penalty.
Dall-EE: precisa se ter clareza e objetividade.
6.	Explorando o playground
Iniciei contando uma historia conforme o professor.


Ultilizando top-p alto e temperatura alta
“Complete a historia. Eu sou Leon Musk e estou 30 anos no futuro e viajo em uma nave espacial”
AI-generator
“Ao olhar pela janela da nave, vejo Marte florescendo com cidades e vegetação. A nova tecnologia de terraformação que desenvolvemos se espalhou por todo o sistema solar. Decido que é hora de anunciar a colonização de Vênus, um passo audacioso que mudará a história da humanidade para sempre.”
	
	Temperatura Baixa e Top-p baixo:
“Enquanto a nave atravessa o espaço, recebo uma mensagem de uma civilização alienígena. Eles me convidam para uma aliança intergaláctica, oferecendo tecnologia que pode salvar a Terra da crise climática. Aceito o convite, sabendo que essa decisão mudará o destino da humanidade.”

“Ao chegar em um novo planeta, Leon Musk descobre uma civilização avançada que já havia colonizado Marte. Juntos, eles desenvolvem tecnologias que transformam a Terra e o espaço, unindo as duas civilizações. No final, Leon se torna um embaixador intergaláctico, promovendo paz e inovação entre os mundos.”
	Temperatura zero e Top-p máximo:
“Ao chegar em um planeta desconhecido, Leon descobre uma civilização avançada que já havia recebido visitantes da Terra. Em vez de conquistar, ele decide compartilhar conhecimentos e tecnologias, promovendo uma aliança intergaláctica. No final, Leon se torna um embaixador da paz entre os mundos, mudando o curso da história humana.”
	Temperatura máximo e Top-p  zero:
“Ao chegar em um planeta desconhecido, descubro uma civilização avançada que já havia previsto minha chegada. Juntos, desenvolvemos tecnologias que transformam a vida na Terra e no novo mundo. No final, decido ficar e liderar a nova era de exploração intergaláctica.”
	Temperatura 0,66 e Top-p 0,82:
“Ao chegar a Marte, descubro uma civilização avançada que me revela segredos sobre a viagem no tempo. Juntos, desenvolvemos uma tecnologia que permite que eu retorne ao passado e mude o curso da história da humanidade. Com um novo propósito, decido usar esse conhecimento para promover a paz e a colaboração entre os povos da Terra.”
Nova instrução:
Você é um assistente de IA que classifica noticias e explica o porque. use no máximo 3 frases e seja objetivo .

“Classificação: Tecnologia e Educação.”
“Explicação: A notícia destaca uma plataforma de educação aberta focada em tecnologia, que promove a formação de talentos e sua conexão com empresas, alinhando-se às tendências atuais de aprendizado e mercado de trabalho.”





















